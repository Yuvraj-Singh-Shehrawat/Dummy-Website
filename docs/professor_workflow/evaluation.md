# Evaluation Process

Once students submit their answer sheets, professors can evaluate them manually or using automated grading.

## Steps to Start Evaluation

=== "Upload Student Answer Sheets"
    ```yaml
    Steps:
      - Navigate to the "Exams" section.
      - Select the exam.
      - Click "Upload Student Answer Sheets".
      - Select and upload scanned answer scripts.
    ```
    !!! note "Accepted Formats"
        PDF format is recommended for clear readability.

=== "Generate Grading Rubric"
    ```yaml
    Steps:
      - Navigate to the "Exams" section.
      - Select the exam.
      - Click "Generate Grading Rubric".
      - Define marking criteria.
      - Click "Save".
    ```
    !!! tip "Why Use a Rubric?"
        A grading rubric ensures fairness and consistency in evaluation.

=== "Start Evaluation"
    ```yaml
    Steps:
      - Navigate to the "Exams" section.
      - Select the exam.
      - Click "Start Evaluation".
      - Use manual grading or AI-assisted grading.
    ```
    !!! info "Grading Options"
        - **Manual Grading:** Professors review each answer manually.
        - **AI-Assisted Grading:** Automated comparison with the golden answer script.

## Evaluation Process Flowchart

```mermaid
graph TD;
    A[Upload Student Answer Sheets] --> B[Generate Grading Rubric];
    B --> C[Start Evaluation];
    C -->|Manual Grading| D[Professor Reviews Answers];
    C -->|AI-Assisted Grading| E[System Auto-Grades Answers];
    D --> F[Finalize Marks];
    E --> F;
    F --> G[Results Published];
