# COCOMO Project Estimation Summary

## Project Overview

The project centers around the development of critical features for a healthcare app, encompassing registration, viewing doctors' schedules, appointment booking, and prescription orders.

## COCOMO Methodology

**COCOMO (Constructive Cost Model)** is a widely used software cost estimation model that helps project managers estimate the effort, time, and resources required for a software development project. It categorizes projects into three modes:

1. **Organic Mode:** Suitable for small teams with experience in the problem domain.
2. **Semi-detached Mode:** Appropriate for intermediate team size and experience.
3. **Embedded Mode:** For projects with tight constraints and high reliability needs.

## COCOMO Calculation and Formula

The estimation process involves:

1. **Lines of Code (KLOC):** An estimate based on the project's scope and complexity.
2. **Effort Multiplier (EM):** A factor accounting for project-level attributes (e.g., team experience, product complexity).
3. **Effort Calculation:** Using the formula `Effort (person-days) = KLOC * EM`.
4. **Development Time Calculation:** Utilizing the formula `Development Time = c * (Effort)^d`, with mode-specific coefficients (c, d).
5. **Person Months Calulcation :  ** Utilizing the formula `Person-Months = Effort / Development time`

## Full Report

For a more detailed analysis, including role-based effort allocation, development time calculation, and recommendations, please refer to the complete report. 

[Jupyter Notebook]: https://github.com/dikhimartin/simple-cocomo-project-estimation/blob/master/cocomo-project-estimation-approach.ipynb



## References

- [COCOMO Model - javatpoint](https://www.javatpoint.com/cocomo-model)
- [COCOMO Model Software Engineering - GeeksforGeeks](https://www.geeksforgeeks.org/software-engineering-cocomo-model/)