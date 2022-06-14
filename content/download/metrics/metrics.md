---
---

## Metrics

### Average Accuracy (Acc)
Acc is the average classification accuracy of the model evaluated on all learned tasks, including the last task it was trained on. This metric is essential to show how the average performance of the model degrades as it learns new tasks. 

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
  \[Acc_{i} = \frac{1}{N_{i}} \sum_{j=1}^{N_{i}} R_{N_i,j}\]
  Where \(N_i\), is the number of learned tasks after learning the task \(i\), and \(R_{N_i,j}\) represents the accuracy on the task \(j\) after learning a new task the task \(i\).
</p>
</body>
</html>

### Backward Forgetting (BWF)
BWF complements Acc and measures the influence of the learned task \(i\) in the performance of the previous tasks.

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
  Where \(N_i\), is the number of learned tasks after learning the task \(i\), and \(R_{j,j}\) and \(R_{N_i,j}\) represents the accuracy on the task \(j\) after learning the task \(j\), and learning a new task the task \(i\), respectively.
</p>
</body>
</html>
