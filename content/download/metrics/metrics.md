---
---

## Metrics

### Average Accuracy (Acc)
Acc is the average classification accuracy of the model evaluated on all learned tasks, including the last task it was trained on. This metric is essential to show how the average performance of the model degrades as it learns new tasks. $BWF_{i} = \frac{1}{N_{i} - 1} \sum_{j=1}^{N_{i}-1} R_{j,j}-R_{N_i,j}$ 

<p><span class="math inline">\(BWF_{i} = \frac{1}{N_{i} - 1}
\sum_{j=1}^{N_{i}-1} R_{j,j}-R_{N_i,j}\)</span></p>

### Backward Forgetting (BWF)
BWF complements Acc and measures the influence of the learned task
