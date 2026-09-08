# English Academic Performance Analytics

## Project Overview
This project analyzes the Fall and Spring Semester grades from High School students' to identify performance trends, areas of classwork/test/project performance for academic support.

## Stakeholder

Special Education Department Coordinator

## Business Question

Based on the Fall and Spring semester performance trends and results, what category should be prioritized for academic support?

## Objectives

- Compare Fall and Spring performance
- Examine missing and late assignments
- Analyze performance by category

## Tools

- Excel
- PostgreSQL
- Python
- SQL
- Tableau

## Data

- StudentID
- Semester (Fall, Spring)
- Category (Classwork, Test, Project)
- Percentage (50%, 30%, 20%)
- Assignment (Comparison, Comprehension, Grammar, Graphic Organizer, Outline, Project, Summary, Test, Vocabulary, Miscellaneous)
- Score (Student's Score)
- Possible Points (Maximum Score)
- Status (Assignment Status; On time, missing, or excused)
- ScorePercent

## Grading Structure
**Subject: English Ⅲ**
| **Category** | **Weight** |
| :--- | ---: |
| Classwork | 50% |
| Test/Quizzes | 30% |
| Projects | 20% |

## Dataset Preview

Data set contains anonymized English grades including the semester, assignment, category, score, possible points, and submission status. It contains 1,430 assignments among 13 students and 2 semesters, Fall and Spring.

Example preview:

**Subject: English Ⅲ**
| **StudentID** | **Semester** |**Category** |**Percentage** |**Assignment** |**Score** |**Possible Points** |**Status** |**ScorePercent** |
| :--- | --- | --- | --- | --- | --- | --- | --- | ---: |
| Stu_001 | Fall | Classwork | 50% | Vocabulary | 18.0 | 40 | On Time | 45.0 |
| Stu_002 | Fall | Classwork | 50% | Comprehension | - | 40 | Excused | NULL |
| Stu_003 | Spring | Test | 30% | Test | 12.0 | 20 | On Time | 60.0 |
| Stu_004 | Spring | Project | 20% | Project | 100.0 | 100 | On Time | 100.0 |

## Analysis
### 1. Semester Performance
- The students' average grades are compared between the Fall and Spring semester

### 2. Category Performance
- Each category is evaluated to determine the changes

### 3. Missing Assignments
- Every student's missing assignments are evaluated in each semester and each category

### 4. Student Trends
- Performances of students' overall average grades are compared in the Fall and Spring

## Dashboard

## Key Findings
### 1. Students' Overall Performance

In Spring, there was a decline in the average assignment performance from **66.7% in Fall to 62.4%**, a difference of approximately **4.3 percentage points**.

From the 13 students:
- 3 students improved
- 10 students declined

### 3. Category Performance Averages

| Category | Fall Average | Spring Average | Change |
|---|---:|---:|---:|
| Classwork | 65.0% | 59.4% | -5.6 |
| Project | 74.5% | 64.0% | -10.6 |
| Test | 75.5% | 75.2% | -0.3 |

*Projects had the largest average decline of **74.5% to 64.0% from Fall to Spring**, a **10.6% difference**.*

### 4. Missing Assignments
The rate of missing assignments for Classwork increased **15.6% in Fall to 22.8% in Spring**. The rate of missing Projects and Tests is **0%**. Despite the rate of missing of Projects and Tests, the performances still declined from Fall to Spring.

## Recommendations

Based on the analysis, these are the following that should be prioritized for more academic support:

1.**Support for Projects**
- Projects has the largest decline from Fall to Spring of **10.6%**.
- Review and determine if instructions and expectations were executed properly, proper amount of time was given, and identify opportunities for more support.

2.**Completion of Assignments**
- Rate of missing assignments for Classwork increased **7.2%** from Fall to Spring with Spring having a missing rate of **22.8%**.
- Identify missing work by the 1st grading period to identify students who need more academic support.

