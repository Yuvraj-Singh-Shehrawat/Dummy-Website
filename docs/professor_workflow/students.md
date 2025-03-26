# Student & TA Management

## 🎓 Adding Students & Teaching Assistants

=== "Add Students"
    ```mermaid
    graph TD;
      A[Course Page] --> B[Add Students]
      B --> C[Enter Student Details]
      C --> D[Save Student]
    ```
    - Bulk upload via CSV is supported.

=== "Add TAs"
    ```mermaid
    graph TD;
      A[Course Page] --> B[Add TAs]
      B --> C[Enter TA Details]
      C --> D[Assign Permissions]
      D --> E[Save TA]
    ```
    - Assign TAs to specific grading roles.
