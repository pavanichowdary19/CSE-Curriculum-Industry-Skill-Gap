# CSE Curriculum–Industry Skill Gap Analysis

## Project Overview

This project presents a Curriculum–Industry Skill Alignment Decision Framework for identifying employability skill gaps among Computer Science and Engineering (CSE) graduates.

The project compares the skill levels provided by the academic curriculum with the skill levels required by industry.

## Objectives

- Identify gaps between curriculum skills and industry requirements.
- Calculate skill gaps for different CSE skills.
- Calculate curriculum–industry alignment scores.
- Identify high-priority skills.
- Classify skills based on their skill gaps.
- Provide training and improvement recommendations.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Dataset

The dataset contains CSE technical and employability skills such as:

- Python
- Java
- SQL
- Data Structures
- Algorithms
- DBMS
- Computer Networks
- Git/GitHub
- Web Development
- Cloud Computing
- AWS
- Machine Learning
- Data Analysis
- Communication Skills
- Problem Solving
- Teamwork
- Interview Skills

## Methodology

```text
Curriculum Skill Level
        +
Industry Required Skill Level
        ↓
Skill Gap Calculation
        ↓
Alignment Score
        ↓
Industry Priority Analysis
        ↓
Decision Framework
        ↓
Training Recommendations














## Results

The developed framework was applied to a sample dataset containing 20 CSE and employability skills.

The analysis compares the curriculum skill level with the industry-required skill level and calculates the skill gap for each skill.

### Overall Alignment

The average curriculum–industry alignment score obtained from the dataset was:

**66%**

This indicates that, in this sample dataset, some skills show good alignment while several skills require additional improvement.

### Skill Gap Findings

The framework classified the 20 skills into the following categories:

| Gap Category | Number of Skills |
|---|---:|
| Critical Gap | 8 |
| Moderate Gap | 5 |
| No Major Gap | 7 |

### Skills Requiring Immediate Training

The framework identified the following high-priority skills with significant gaps:

- Git/GitHub
- Web Development
- Cloud Computing
- AWS
- Data Analysis
- Communication Skills
- Teamwork
- Interview Skills

These skills had a relatively larger difference between the curriculum level and the industry-required level in the sample dataset.

### Skills Requiring Priority Improvement

The following skills showed a smaller but important gap:

- Python
- SQL
- DBMS
- Problem Solving

These skills were classified as requiring priority improvement because they have high industry priority and a skill gap of one level.

### Decision Framework

The system generates decisions based on skill gap and industry priority:

```text
Skill Gap + Industry Priority
            ↓
      Decision Framework
            ↓
 ┌─────────────────────────────┐
 │ Immediate Training Required │
 │ Priority Improvement        │
 │ Recommended Improvement     │
 │ Maintain Current Level      │
 └─────────────────────────────┘
