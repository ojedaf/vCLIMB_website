---
---
### Baselines for Video CIL

In order to evaluate our benchmark, we extend four methods from image domain. The first two are EWC and MAS. These are regularized methods that penalize changes to the most relevant parameters for the previous tasks. The other two, iCaRL and BIC, are memory-based methods that select and store samples of the current task into a memory buffer for future replay. Consistent with image benchmarks, the memory-based approaches significantly outperform the regularized methods.

<table style="border-collapse: separate; text-align: center; vertical-align: middle; margin-left: auto;margin-right: auto;font-size:10px;">
 <thead style="background-color: #4473c4;color: white;">
  <tr>
   <th rowspan="2">Model</th>
   <th rowspan="2">Num. Task</th>
   <th colspan="4">Kinetics</th>
   <th colspan="4">ActivityNet-Trim</th>
   <th colspan="4">UCF101</th>
  </tr>
  <tr>
   <th>Mem. Video Instances</th>
   <th>Mem. Frame Capacity</th>
   <th>Acc</th>
   <th>BWF</th>
   <th>Mem. Video Instances</th>
   <th>Mem. Frame Capacity</th>
   <th>Acc</th>
   <th>BWF</th>
   <th>Mem. Video Instances</th>
   <th>Mem. Frame Capacity</th>
   <th>Acc</th>
   <th>BWF</th>
  </tr>
 </thead>
 <tbody>
  <tr style="background-color: #e9ebf5">
   <th>EWC</th>
   <td>10</td>
   <td>None</td>
   <td>None</td>
   <td>5.81%</td>
   <td>16.05%</td>
   <td>None</td>
   <td>None</td>
   <td>4.02%</td>
   <td>5.32%</td>
   <td>None</td>
   <td>None</td>
   <td>9.51%</td>
   <td>98.94%</td>
  </tr>
  <tr style="background-color: #cfd5ea">
   <th>MAS</th>
   <td>10</td>
   <td>None</td>
   <td>None</td>
   <td>7.81%</td>
   <td>10.12%</td>
   <td>None</td>
   <td>None</td>
   <td>8.11%</td>
   <td>0.18%</td>
   <td>None</td>
   <td>None</td>
   <td>10.89%</td>
   <td>11.11%</td>
  </tr>
  <tr style="background-color: #e9ebf5">
   <th>EWC</th>
   <td>20</td>
   <td>None</td>
   <td>None</td>
   <td>2.95%</td>
   <td>32.70%</td>
   <td>None</td>
   <td>None</td>
   <td>1.28%</td>
   <td>3.77%</td>
   <td>None</td>
   <td>None</td>
   <td>4.71%</td>
   <td>92.12%</td>
  </tr>
  <tr style="background-color: #cfd5ea">
   <th>MAS</th>
   <td>20</td>
   <td>None</td>
   <td>None</td>
   <td>4.25%</td>
   <td>5.54%</td>
   <td>None</td>
   <td>None</td>
   <td>4.61%</td>
   <td>0.1%</td>
   <td>None</td>
   <td>None</td>
   <td>5.90%</td>
   <td>5.31%</td>
  </tr>
  <tr style="background-color: #e9ebf5">
   <th>Naive</th>
   <td>10</td>
   <td>8000</td>
   <td>2 × 10<sup>6</sup></td>
   <td>30.14%</td>
   <td>41.30%</td>
   <td>4000</td>
   <td>15.5 × 10<sup>6</sup></td>
   <td>47.20%</td>
   <td>20.64%</td>
   <td>2020</td>
   <td>3.69 × 10<sup>5</sup></td>
   <td>91.42%</td>
   <td>7.43%</td>
  </tr>
  <tr style="background-color: #cfd5ea">
   <th>iCaRL</th>
   <td>10</td>
   <td>8000</td>
   <td>2 × 10<sup>6</sup></td>
   <td>32.04%</td>
   <td>38.74%</td>
   <td>4000</td>
   <td>15.5 × 10<sup>6</sup></td>
   <td>48.53%</td>
   <td>19.72%</td>
   <td>2020</td>
   <td>3.69 × 10<sup>5</sup></td>
   <td>80.97%</td>
   <td>18.11%</td>
  </tr>
  <tr style="background-color: #e9ebf5">
   <th>BiC</th>
   <td>10</td>
   <td>8000</td>
   <td>2 × 10<sup>6</sup></td>
   <td>27.90%</td>
   <td>51.96%</td>
   <td>4000</td>
   <td>15.5 × 10<sup>6</sup></td>
   <td>51.96%</td>
   <td>24.27%</td>
   <td>2020</td>
   <td>3.69 × 10<sup>5</sup></td>
   <td>78.16%</td>
   <td>18.49%</td>
  </tr>
  <tr style="background-color: #cfd5ea">
   <th>Naive</th>
   <td>20</td>
   <td>8000</td>
   <td>2 × 10<sup>6</sup></td>
   <td>23.47%</td>
   <td>48.05%</td>
   <td>4000</td>
   <td>15.5 × 10<sup>6</sup></td>
   <td>40.78%</td>
   <td>23.18%</td>
   <td>2020</td>
   <td>3.69 × 10<sup>5</sup></td>
   <td>87.40%</td>
   <td>10.96%</td>
  </tr>
  <tr style="background-color: #e9ebf5">
   <th>iCaRL</th>
   <td>20</td>
   <td>8000</td>
   <td>2 × 10<sup>6</sup></td>
   <td>26.73%</td>
   <td>42.25%</td>
   <td>4000</td>
   <td>15.5 × 10<sup>6</sup></td>
   <td>43.33%</td>
   <td>21.57%</td>
   <td>2020</td>
   <td>3.69 × 10<sup>5</sup></td>
   <td>76.59%</td>
   <td>21.83%</td>
  </tr>
  <tr style="background-color: #cfd5ea">
   <th>BiC</th>
   <td>20</td>
   <td>8000</td>
   <td>2 × 10<sup>6</sup></td>
   <td>23.06%</td>
   <td>58.97%</td>
   <td>4000</td>
   <td>15.5 × 10<sup>6</sup></td>
   <td>46.53%</td>
   <td>15.95%</td>
   <td>2020</td>
   <td>3.69 × 10<sup>5</sup></td>
   <td>70.69%</td>
   <td>24.90%</td>
  </tr>
 </tbody>
</table>


