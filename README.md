# Disco-Project


# Course Allocation System - README

This Python code is designed to allocate courses to professors in a university's Course Assignment System based on their preferences and constraints. The algorithm aims to maximize the number of courses assigned while respecting individual preferences, course points, and load limits for each professor.

## Overview

The system takes into account the following details:

- Professors are categorized into three groups: X1, X2, and X3.
- Each category has specific course load capacities:
  - X1: 0.5 courses per semester
  - X2: 1 course per semester
  - X3: 1.5 courses per semester

## Execution

### Python Script

- The main script `final_code.py` contains the entire implementation.
- It sorts the course preferences within each category while maintaining the original order.
- The allocation algorithm considers professor preferences, course points, and load limits to assign courses optimally.

### Running the Script

1. Ensure Python 3.x is installed on your system.
2. Execute the `final_code.py` script in a Python environment.

### Output

- The code outputs all possible unique allocations that satisfy load constraints and professor preferences.
- It displays the professors along with their allocated courses in each allocation.

## Notes

- The code employs backtracking and permutation techniques to generate unique allocations.
- Allocations are unique not only by the order of professors but also by the specific courses assigned to them.

## Additional Resources

- No additional resources are required to run the script.
- The code is self-contained and uses Python's standard libraries.

