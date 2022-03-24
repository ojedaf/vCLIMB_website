---
---
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
