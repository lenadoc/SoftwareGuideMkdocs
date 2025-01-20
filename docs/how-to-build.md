# How to build the website locally

1. Clone the website
2. Make your changes and create a pull request.
3. To build the site locally, run `mkdocs serve`. The website is accessible locally at http://127.0.0.1:8000/

todo: analytics: https://squidfunk.github.io/mkdocs-material/setup/setting-up-site-analytics/?h=page#was-this-page-helpful
Add how to build page

To export to pdf with pandoc: 
C:\Sample\SoftwareGuideMkdocs>pandoc "C:\Sample\SoftwareGuideMkdocs\docs\index.md" -o output.pdf --pdf-engine=xelatex


C:\Sample\SoftwareGuideMkdocs>pandoc "C:\Sample\SoftwareGuideMkdocs\docs\usage\create-project.md" -o create3.pdf --pdf-engine=xelatex

pandoc docs/usage/create-project.md -o create3.pdf --pdf-engine=xelatex

pandoc docs/usage/create-project.md -o create3.pdf --pdf-engine=xelatex --extract-media=

pandoc docs/usage/create-project.md -o create4.pdf --extract-media=

Plugins for PDF export: https://github.com/zhaoterryy/mkdocs-pdf-export-plugin. Installation:
- pdf-export:
      combined: true

1. Install WeasyPrint:
    1. Install the latest executable from this page: https://github.com/Kozea/WeasyPrint/releases
    2. Install MSYS2:
        1. Install [MSYS2](https://www.msys2.org/#installation) keeping the default options.
        2. After installation, in MSYS2’s shell, execute `pacman -S mingw-w64-x86_64-pango`.
        3. Close MSYS2’s shell.
    3. Follow the installation procedure described [here](https://github.com/zhaoterryy/mkdocs-pdf-export-plugin?tab=readme-ov-file#installation).
