# Optimization for Data Science Project

**A Comparative Analysis of the Projected Gradient Method and the Frank-Wolfe Algorithm on Portfolio Optimization**
  
---

## Repository Contents
- **ODS_Report.pdf**  
  Report with theoretical background, algorithm descriptions, and empirical results.

- **ODS_project_code.ipynb**  
  Jupyter Notebook containing the Python implementation of the algorithms.  
  Note: To successfully run the code, you can find the `.xlsx` files in the `data` subfolder. They must be uploaded manually when requested during execution.

- **data/**  
  Folder containing the datasets used in the experiments:  
  - `DowJones.xlsx`  
  - `FTSE100.xlsx`  
  - `NASDAQ100.xlsx`  
  - `SP500.xlsx`

---

## Methods
- **Projected Gradient (PG)**  
  Classical gradient descent with projection onto the simplex.  

- **Frank-Wolfe (FW)**  
  Projection-free algorithm using a linear minimization oracle.  

- **Away-Step Frank-Wolfe (AFW)**  
  Extension of FW that allows moving away from previously chosen vertices.  

- **Pairwise Frank-Wolfe (PFW)**  
  Extension of FW that adjusts weights by simultaneously adding and removing vertices.
