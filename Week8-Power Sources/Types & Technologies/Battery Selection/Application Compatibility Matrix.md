

## 🔋 Battery-Application Compatibility Matrix

* **Step 5:** Normalize the criteria $\mathbf{x}_{(i,j)}$ to a $0-1$ scale for comparability $\mathbf{x}'_{(i,j)}$.
    $$\mathbf{x}'_{(i,j)} = |(\mathbf{x}_{(i,j)} - \min(\mathbf{x}_{i})) / (\max(\mathbf{x}_{i}) - \min(\mathbf{x}_{i})) |$$

* **Step 6:** Assign weights $\mathbf{w}_{(i,k)}$ to each attribute per application (weights sum to 1).
    > **Weight constraint:** $\sum_{i} \mathbf{w}_{(i,k)} = 1$

* **Step 7:** Compute weighted scores for each battery–application pair.
    > **Weighted sum:** $\mathbf{S}_{(j,k)} = \sum_{i} (\mathbf{w}_{(i,k)} \times \mathbf{x}'_{(i,j)})$

* **Step 8:** Scale scores to a $0-100$ range for interpretability.
    > **Scaled score:** $\mathbf{S}_{(j,k)}^{(100)} = 100 \times \mathbf{S}_{(j,k)}$

* **Step 9:** Construct the **compatibility matrix** and interpret rankings.

---
