# PyCitySchools Analysis

## Overview

This project involves analyzing school performance data using Pandas and Jupyter Notebook. The goal is to generate various summaries and visualizations to provide insights into the school district's performance, focusing on metrics such as average test scores, passing rates, and spending per student.

## Files

- `PyCitySchools_starter.ipynb`: Jupyter Notebook containing the analysis and results.
- `schools_complete.csv`: CSV file with school information.
- `students_complete.csv`: CSV file with student information.

## Instructions

### District Summary

A high-level snapshot of the district's key metrics:
- Total number of unique schools
- Total students
- Total budget
- Average math score
- Average reading score
- % passing math (students with a math score >= 70)
- % passing reading (students with a reading score >= 70)
- % overall passing (students passing both math and reading)

### School Summary

A DataFrame summarizing key metrics about each school:
- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math score
- Average reading score
- % passing math
- % passing reading
- % overall passing

### Highest-Performing Schools (by % Overall Passing)

Top 5 schools based on the overall passing percentage.

### Lowest-Performing Schools (by % Overall Passing)

Bottom 5 schools based on the overall passing percentage.

### Math Scores by Grade

A DataFrame listing the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

A DataFrame listing the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

A table breaking down school performance based on average spending ranges (per student):
- Average math score
- Average reading score
- % passing math
- % passing reading
- % overall passing

### Scores by School Size

A DataFrame breaking down school performance based on school size:
- Small (<1000)
- Medium (1000-2000)
- Large (2000-5000)

### Scores by School Type

A DataFrame showing school performance based on the school type (Charter vs. District).

## Results and Insights

- **District Summary**: Provides an overview of the entire district's performance.
- **School Summary**: Detailed metrics for each school, allowing for comparison.
- **Top and Bottom Performing Schools**: Highlights the best and worst performing schools.
- **Scores by Grade**: Shows performance trends across different grade levels.
- **Scores by Spending**: Analyzes how spending per student impacts performance.
- **Scores by Size and Type**: Evaluates performance based on school size and type.

## Conclusion

This analysis provides valuable insights into the factors affecting school performance, highlighting areas of strength and opportunities for improvement. By understanding these metrics, stakeholders can make informed decisions to enhance educational outcomes across the district.

## Dependencies

- Python 3.x
- Pandas
- Jupyter Notebook

## Usage

1. Clone the repository:
   git clone git@github.com:endoplasmicosmic/Pandas-challenge.git
   cd Pandas-challenge/PyCitySchools
2. Open Jupyter Lab:
   jupyter lab PyCitySchools_starter.ipynb
3. Run the notebook cells to perform the analysis.

## Resources

- Markdown Guide Cheat Sheet: https://www.markdownguide.org/cheat-sheet/
- Pandas Documentation: https://pandas.pydata.org/docs/reference/index.html
