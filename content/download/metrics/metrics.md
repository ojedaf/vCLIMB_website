---
---

## Metrics

### Average Accuracy (Acc)
Acc is the average classification accuracy of the model evaluated on all learned tasks, including the last task it was trained on. This metric is essential to show how the average performance of the model degrades as it learns new tasks. $BWF_{i} = \frac{1}{N_{i} - 1} \sum_{j=1}^{N_{i}-1} R_{j,j}-R_{N_i,j}$ 

<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async
          src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
  </script>
</head>
<body>
<p>
  \[BWF_{i} = \frac{1}{N_{i} - 1} \sum_{j=1}^{N_{i}-1} R_{j,j}-R_{N_i,j}\]
  Where \N_i\, there are two solutions to \(ax^2 + bx + c = 0\) and they are
</p>
</body>
</html>

### Backward Forgetting (BWF)
BWF complements Acc and measures the influence of the learned task
