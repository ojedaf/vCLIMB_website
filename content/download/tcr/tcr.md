---
---
### Temporal Consistency Regularization

We also present a novel strategy for rehearsal methods to reduce memory consumption while improving performance. It is a temporal consistency regularization loss, represented by the red dashed arrow in the figure. This loss constrains the network to estimate similar representations for the original clip and its temporally down-sampled version. Thus, it enables the network to remember from the temporally down-sampled videos of the previously learned tasks. 

<img src="https://raw.githubusercontent.com/ojedaf/vCLIMB_website/main/assets/media/tc_img.png" align="left">
