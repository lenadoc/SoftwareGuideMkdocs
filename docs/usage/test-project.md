# Test the Project

## Testing Framework

Our testing framework supports:

- Unit Testing
- Integration Testing
- End-to-End Testing

### Running Tests

```bash
# Run all tests
pytest

# Run specific test suite
pytest tests/unit/
```

!!! success "Best Practices"
    1. Write tests first
    2. Use meaningful names
    3. Test edge cases

??? example "Sample Test Code"
    ```python
    def test_project_creation():
        project = Project("Test")
        assert project.name == "Test"
        assert project.status == "Active"
    ```

See [Installation Guide](../installation.md) for setup requirements.
lsfödö