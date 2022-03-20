---
---

Congratulations to Richard Hendricks for winning first place in the Wowchemy Prize.
The standard commonmark does not support tables and does not refer to or recommend any specific table extensions (latest revision permalink as of 2018-03). Your question doesn't specifically ask about Github-flavored Markdown (GFM), but GFM is based on commonmark with a table extension which doesn't support this.

<table style="border-collapse: separate; text-align: center; vertical-align: middle;font-size:10px; ">
 <thead style="background-color: #333;color: white;">
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
  <tr>
   <th style="background-color: #36c;color: #fff">EWC</th>
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
  <tr>
   <th style="background-color: #36c;color: #fff">MAS</th>
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
  <tr>
   <th style="background-color: #36c;color: #fff">EWC</th>
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
  <tr style="border-bottom: 1pt solid black;">
   <th style="background-color: #36c;color: #fff">MAS</th>
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
  <tr>
   <th style="background-color: #36c;color: #fff">Naive</th>
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
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL</th>
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
  <tr>
   <th style="background-color: #36c;color: #fff">BiC</th>
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
  <tr>
   <th style="background-color: #36c;color: #fff">Naive</th>
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
  <tr>
   <th style="background-color: #36c;color: #fff">iCaRL</th>
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
  <tr>
   <th style="background-color: #36c;color: #fff">BiC</th>
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


<table style="border-collapse: separate; text-align: center; vertical-align: middle;font-size:10px; ">
 <thead style="background-color: #333;color: white;">
  <tr>
   <th rowspan="2">Model</th>
   <th rowspan="2">Frames per video</th>
   <th colspan="4">Kinetics</th>
   <th colspan="4">ActivityNet-Trim</th>
   <th colspan="4">UCF101</th>
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
 </tbody>
</table>

<!--more-->

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.

Sed eu dui nec ligula bibendum dapibus. Nullam imperdiet auctor tortor, vel cursus mauris malesuada non. Quisque ultrices euismod dapibus. Aenean sed gravida risus. Sed nisi tortor, vulputate nec quam non, placerat porta nisl. Nunc varius lobortis urna, condimentum facilisis ipsum molestie eu. Ut molestie eleifend ligula sed dignissim. Duis ut tellus turpis. Praesent tincidunt, nunc sed congue malesuada, mauris enim maximus massa, eget interdum turpis urna et ante. Morbi sem nisl, cursus quis mollis et, interdum luctus augue. Aliquam laoreet, leo et accumsan tincidunt, libero neque aliquet lectus, a ultricies lorem mi a orci.

Mauris dapibus sem vel magna convallis laoreet. Donec in venenatis urna, vitae sodales odio. Praesent tortor diam, varius non luctus nec, bibendum vel est. Quisque id sem enim. Maecenas at est leo. Vestibulum tristique pellentesque ex, blandit placerat nunc eleifend sit amet. Fusce eget lectus bibendum, accumsan mi quis, luctus sem. Etiam vitae nulla scelerisque, eleifend odio in, euismod quam. Etiam porta ullamcorper massa, vitae gravida turpis euismod quis. Mauris sodales sem ac ultrices viverra. In placerat ultrices sapien. Suspendisse eu arcu hendrerit, luctus tortor cursus, maximus dolor. Proin et velit et quam gravida dapibus. Donec blandit justo ut consequat tristique.
