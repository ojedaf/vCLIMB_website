---
---
### Datasets

vCLIMB is a novel benchmark devised to evaluate Class Incremental Learning in video domain to promote and facilitate research in this area. Our benchmark includes three well-known video datasets: UCF101, Kinetics, and ActivityNet.

<div class="media media3">
 <img src="https://raw.githubusercontent.com/ojedaf/vCLIMB_website/main/assets/media/img_datasets.png"> 
</div>

### Our Benchmark

This table shows the main attributes of the Continual Learning Scenarios we propose in our benchmark.

<ul>
<li>We create two sets of tasks, one with ten tasks and the other with twenty. The last one is more challenging because it has a longer series of tasks. Therefore, it offers more chances to forget.
<li>We do not leverage pretraining of the same data distribution to isolate the forgetting problem. 
<li>For the first time, we propose evaluating a more realistic and challenging scenario using untrimmed videos.
<li>The video instances contain a temporal dimension size that could show large variability. To favor fair comparisons between methods and datasets, we define the working memory size of the rehearsal methods in terms of stored frames. 
</ul>

<table style="border-collapse: separate; text-align: center; vertical-align: middle; margin-left: auto;margin-right: auto;">
 <thead style="background-color: #4473c4;color: white;">
  <tr>
   <th>Set</th>
   <th>Tasks</th>
   <th>Classes Per Task</th>
   <th>Avg. Frames Per Video</th>
   <th>Untrimmed Videos</th>
  </tr>
 </thead>
 <tbody>
  <tr style="background-color: #e9ebf5">
   <th>vCLIMB UCF101</th>
   <td>10</td>
   <td>10</td>
   <td>183</td>
   <td>✕</td>
  </tr>
  <tr style="background-color: #cfd5ea">
   <th>vCLIMB UCF101</th>
   <td>20</td>
   <td>5</td>
   <td>183</td>
   <td>✕</td>
  </tr>
  <tr style="background-color: #e9ebf5">
   <th>vCLIMB Kinetics</th>
   <td>10</td>
   <td>40</td>
   <td>250</td>
   <td>✕</td>
  </tr>
  <tr style="background-color: #cfd5ea">
   <th>vCLIMB Kinetics</th>
   <td>20</td>
   <td>20</td>
   <td>250</td>
   <td>✕</td>
  </tr>
  <tr style="background-color: #e9ebf5">
   <th>vCLIMB ActivityNet-Untrim</th>
   <td>10</td>
   <td>20</td>
   <td>3542</td>
   <td style="color: green;">✓</td>
  </tr>
  <tr style="background-color: #cfd5ea">
   <th>vCLIMB ActivityNet-Untrim</th>
   <td>20</td>
   <td>10</td>
   <td>3542</td>
   <td style="color: green;">✓</td>
  </tr>
  <tr style="background-color: #e9ebf5">
   <th>vCLIMB ActivityNet-Trim</th>
   <td>10</td>
   <td>20</td>
   <td>3879</td>
   <td>✕</td>
  </tr>
  <tr style="background-color: #cfd5ea">
   <th>vCLIMB ActivityNet-Trim</th>
   <td>20</td>
   <td>10</td>
   <td>3879</td>
   <td>✕</td>
  </tr>
 </tbody>
</table>
