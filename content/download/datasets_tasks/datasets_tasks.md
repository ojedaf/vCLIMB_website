---
---
## Datasets

vCLIMB is a novel benchmark devised to evaluate Class Incremental Learning in video domain to promote and facilitate research in this area. Our benchmark includes three well-known video datasets: UCF101, Kinetics, and ActivityNet.

<div class="media media3">
 <img src="https://raw.githubusercontent.com/ojedaf/vCLIMB_website/main/assets/media/img_datasets.png"> 
</div>

<table style="border-collapse: separate; text-align: center; vertical-align: middle;font-size:10px; ">
 <thead style="background-color: #333;color: white;">
  <tr>
   <th>Set</th>
   <th>Tasks</th>
   <th>Classes Per Task</th>
   <th>Avg. Frames Per Video</th>
   <th>Untrimmed Videos</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <th style="background-color: #36c;color: #fff">EWC</th>
   <td>10</td>
   <td>None</td>
   <td>None</td>
   <td>5.81%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">MAS</th>
   <td>10</td>
   <td>None</td>
   <td>None</td>
   <td>7.81%</td>
  </tr>
 </tbody>
</table>

## Remembering from Down-sampled Videos.
Temporal consistency regularization (labeled TC in the table) reduces forgetting on the 10-task Kinetics split regardless of how many frames per video are stored. In particular, our best baseline (iCaRL) tested on a memory of 16, 8, or 4 frames per video is significantly improved when our temporal consistency term is added to iCaRL's loss objective. Indeed, adding the TC Loss, we achieve even better results with 4, 8, and 16 than with without TC and full-resolution videos. Likewise, we obtain even more sizable improvements on Trimmed ActivityNet with temporal consistency. Specifically, adding the regularization term with a model that has access to a memory consisting of 8 frames per video results in a massive 24% improvement, which significantly closes the 27% accuracy gap between storing 8 frames without TC and full-resolution videos. Our results show that our method is most relevant for datasets that require more sophisticated temporal reasoning like ActivityNet.

<table style="border-collapse: separate; text-align: center; vertical-align: middle;font-size:10px; ">
 <thead style="background-color: #333;color: white;">
  <tr>
   <th rowspan="2">Model</th>
   <th rowspan="2">Frames per video</th>
   <th colspan="3">Kinetics</th>
   <th colspan="3">ActivityNet-Trim</th>
   <th colspan="3">UCF101</th>
  </tr>
  <tr>
   <th>Mem. Frame Capacity</th>
   <th>Acc</th>
   <th>BWF</th>
   <th>Mem. Frame Capacity</th>
   <th>Acc</th>
   <th>BWF</th>
   <th>Mem. Frame Capacity</th>
   <th>Acc</th>
   <th>BWF</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL</th>
   <td>4</td>
   <td>3.2 × 10<sup>4</sup></td>
   <td>30.73%</td>
   <td>40.36%</td>
   <td>1.6 × 10<sup>4</sup></td>
   <td>21.63%</td>
   <td>36.98%</td>
   <td>8.08 × 10<sup>3</sup></td>
   <td>80.32%</td>
   <td>17.13%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL</th>
   <td>8</td>
   <td>6.4 × 10<sup>4</sup></td>
   <td>32.04%</td>
   <td>38.48%</td>
   <td>3.2 × 10<sup>4</sup></td>
   <td>21.54%</td>
   <td>33.41%</td>
   <td>16.16 × 10<sup>3</sup></td>
   <td>81.12%</td>
   <td>18.25%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL</th>
   <td>16</td>
   <td>12.8 × 10<sup>4</sup></td>
   <td>31.36%</td>
   <td>38.74%</td>
   <td>6.4 × 10<sup>4</sup></td>
   <td>25.27%</td>
   <td>29.71%</td>
   <td>32.32 × 10<sup>3</sup></td>
   <td>81.06%</td>
   <td>18.23%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL</th>
   <td>ALL</td>
   <td>2 × 10<sup>6</sup></td>
   <td>32.04%</td>
   <td>38.74%</td>
   <td>15.5 × 10<sup>6</sup></td>
   <td>48.53%</td>
   <td>19.72%</td>
   <td>3.69 × 10<sup>5</sup></td>
   <td>80.97%</td>
   <td>18.11%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL+TC</th>
   <td>4</td>
   <td>3.2 × 10<sup>4</sup></td>
   <td>35.32%</td>
   <td>34.07%</td>
   <td>1.6 × 10<sup>4</sup></td>
   <td>42.99%</td>
   <td>23.82%</td>
   <td>8.08 × 10<sup>3</sup></td>
   <td>73.85%</td>
   <td>26.35%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL+TC</th>
   <td>8</td>
   <td>6.4 × 10<sup>4</sup></td>
   <td>36.24%</td>
   <td>33.83%</td>
   <td>3.2 × 10<sup>4</sup></td>
   <td>45.73%</td>
   <td>18.90%</td>
   <td>16.16 × 10<sup>3</sup></td>
   <td>74.25%</td>
   <td>25.27%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL+TC</th>
   <td>16</td>
   <td>12.8 × 10<sup>4</sup></td>
   <td>36.54%</td>
   <td>33.53%</td>
   <td>6.4 × 10<sup>4</sup></td>
   <td>44.04%</td>
   <td>22.82%</td>
   <td>32.32 × 10<sup>3</sup></td>
   <td>75.84%</td>
   <td>23.23%</td>
  </tr>
 </tbody>
</table>

## Class Incremental Learning from Untrimmed Videos

We perform a set of experiments to evaluate the realistic class incremental learning scenario with untrimmed videos and make a few interesting observations. First, ActivityNet-Untrim is more challenging than ActivityNet-Trim. iCaRL baseline achieves a better performance on ActivityNet-Trim regardless of the number of frames per video stored in memory. Second, our temporal consistency regularization improves iCaRL by large margins in both ActivityNet setups.

<table style="border-collapse: separate; text-align: center; vertical-align: middle;font-size:10px; ">
 <thead style="background-color: #333;color: white;">
  <tr>
   <th rowspan="2">Model</th>
   <th rowspan="2">Frames per video</th>
   <th rowspan="2">Mem. Frame Capacity</th>
   <th colspan="2">ActivityNet-Untrim</th>
   <th colspan="2">ActivityNet-Trim</th>
  </tr>
  <tr>
   <th>Acc</th>
   <th>BWF</th>
   <th>Acc</th>
   <th>BWF</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL</th>
   <td>4</td>
   <td>1.6 × 10<sup>4</sup></td>
   <td>16.28%</td>
   <td>32.75%</td>
   <td>21.63%</td>
   <td>36.98%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL</th>
   <td>8</td>
   <td>3.2 × 10<sup>4</sup></td>
   <td>16.67%</td>
   <td>31.96%</td>
   <td>21.54%</td>
   <td>33.41%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL</th>
   <td>16</td>
   <td>6.4 × 10<sup>4</sup></td>
   <td>21.27%</td>
   <td>28.94%</td>
   <td>25.27%</td>
   <td>29.71%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL+TC</th>
   <td>4</td>
   <td>1.6 × 10<sup>4</sup></td>
   <td>36.07%</td>
   <td>22.39%</td>
   <td>42.99%</td>
   <td>23.82%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL+TC</th>
   <td>8</td>
   <td>3.2 × 10<sup>4</sup></td>
   <td>40.29%</td>
   <td>20.80%</td>
   <td>45.73%</td>
   <td>18.90%</td>
  </tr>
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL+TC</th>
   <td>16</td>
   <td>6.4 × 10<sup>4</sup></td>
   <td>40.45%</td>
   <td>21.21%</td>
   <td>44.04%</td>
   <td>22.82%</td>
  </tr>
 </tbody>
</table>
