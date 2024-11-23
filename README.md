
This project implements a heuristic based on **H-max** to solve assortment optimization problems under the **Nested Logit Model**. The simulation evaluates the performance of the heuristic against:  

1. **Optimal solutions** derived in the following papers:  
   - *Assortment Optimization Under Variants of the Nested Logit Model* (focus on the standard model with dissimilarity parameters at most one; up to the end of Section 4).  
   - *The Constrained Assortment Optimization Problem for the Nested Logit Model* (up to the end of Section 4).  
   - *The Assortment Optimization under the Nested Logit Model* (up to the end of Section 4).  

2. **Brute-force solutions** for cases where cardinality constraints are imposed either:  
   - At the **nest level**, or  
   - **Overall** across all products.  

These simulations explore the performance of the heuristic under these constraints, where no known optimal solutions exist, providing a comparison baseline.
