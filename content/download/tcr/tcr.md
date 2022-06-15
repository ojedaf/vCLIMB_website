---
---
### Temporal Consistency Regularization

We also present a novel strategy for rehearsal methods to reduce memory consumption while improving performance. It is a temporal consistency regularization loss, represented by the red dashed arrow in the figure. This loss constrains the network to estimate similar representations for the original clip and its temporally down-sampled version. Thus, it enables the network to remember from the temporally down-sampled videos of the previously learned tasks. 

<img src="https://raw.githubusercontent.com/ojedaf/vCLIMB_website/main/assets/media/tc_img.png" align="left">

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
<br>
<p>
  \[L_{c} = (1-\lambda)L_{cls}(F(X), Y) + \lambda L_{cls}(F(X^d), Y)\]
  Where \(L_{cls}\), is the cross-entropy loss. \(Y\) is the ground truth label of \(X\) and \(X^d\). \(X^d\) is the temporally down-sampled version of \(X\). \(\lambda\) is the consistency regularization factor.
</p>
</body>
</html>

<img src="https://raw.githubusercontent.com/ojedaf/vCLIMB_website/main/assets/media/tc_results_img.png" align="left">
