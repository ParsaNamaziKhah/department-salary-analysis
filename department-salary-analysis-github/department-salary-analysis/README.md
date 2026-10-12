# Department Top Salaries

A small pandas exercise that joins employee and department tables and returns every employee whose salary falls within the top three **distinct** salary levels for their department.

## Concepts demonstrated

- Creating DataFrames from input records
- Joining tables with `merge`
- Finding unique department/salary pairs with `drop_duplicates`
- Grouping by department and selecting the top salary levels with sorting and `head`
- Merging selected salary levels back to all employees so ties are preserved

## Run it

```bash
pip install -r requirements.txt
```

Open `department_salary_analysis.ipynb` and run all cells from top to bottom. No external dataset is required because this course exercise supplies a small set of sample employee and department records.

## Interpretation

The handout's narrative and sample output are not fully consistent. This implementation follows the top-three-distinct-salary-level interpretation. Therefore, if a department contains fewer than three distinct salary levels, every existing level qualifies. All employees tied at a qualifying salary are included.

The records are an educational example, not real employee information.
