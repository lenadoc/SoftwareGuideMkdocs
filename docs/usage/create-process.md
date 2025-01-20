# Create a Process

## Process Types

Our platform supports various process types:

| Process Type | Use Case            | Complexity |
|--------------|---------------------|------------|
| Sequential   | Simple workflows    | Low        |
| Parallel     | Multiple streams    | Medium     |
| Conditional  | Decision-based      | High       |

## Creating a Process

1. Open your [project](crate-project.md)
2. Select "New Process"
3. Choose a process type
4. Configure steps

!!! example "Example Process"
    ```yaml
    process:
      name: Document Approval
      steps:
        - review
        - approve
        - publish
    ```

---