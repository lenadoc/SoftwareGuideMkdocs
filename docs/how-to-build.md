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
