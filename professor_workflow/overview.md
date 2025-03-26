# Workflow Overview

The professor workflow consists of the following steps:

```mermaid
graph TD;
  A[Login as Professor] --> B[Manage Courses];
  B --> C[Add Course];
  B --> D[View Course];
  B --> E[Edit Course];
  B --> F[Delete Course];
  C --> G[Add Students & TAs];
  D --> H[Manage Exams];
  H --> I[Upload Question Paper];
  H --> J[Upload Golden Answer Script];
  H --> K[Generate Grading Rubric];
  K --> L[Upload Student Answer Sheets];
  L --> M[Start Evaluation];
