---
---
### Challenge of Remembering from fewer frames

The video instances contain a temporal dimension size that could show large variability, and some action classes do not require considering all frames to understand them. To favor fair comparisons between methods and datasets and reduce the huge memory consumption, we define the working memory size of the rehearsal methods in terms of stored frames. This creates a new unique scenario of Class Incremental Learning in video data, in which rehearsal methods must decide first what subset of frames should be selected and then decide what video to store according to selected frames per video. We encourage future works on Class Incremental Learning for Video Understanding to focus on this and beat our Temporal Consistency Regulation strategy. 

<table style="border-collapse: separate; text-align: center; vertical-align: middle; margin-left: auto;margin-right: auto;">
 <thead style="background-color: #4473c4;color: white;">
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
  <tr style="background-color: #e9ebf5">
   <th>iCaRL</th>
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
  <tr style="background-color: #cfd5ea">
   <th>iCaRL</th>
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
  <tr style="background-color: #e9ebf5">
   <th>iCaRL</th>
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
  <tr style="background-color: #cfd5ea">
   <th>iCaRL</th>
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
  <tr style="background-color: #e9ebf5">
   <th>iCaRL+TC</th>
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
  <tr style="background-color: #cfd5ea">
   <th>iCaRL+TC</th>
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
  <tr style="background-color: #e9ebf5">
   <th>iCaRL+TC</th>
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


