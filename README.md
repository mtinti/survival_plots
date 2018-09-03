# Notebook to facilitate the visualisation of Kaplan-Meier plots
## Input data should be a txt file with 3 columns:

<ul>
  <li>T: the Time length of the observation</li>
  <li>E: binary, 1 if the Event is observed (death) or 0</li>
  <li>g: the Group to wich the data point belongs to</li>
</ul>

### Input format example

<table style="width:30%">
  <tr>
    <th>T</th>
    <th>E</th> 
    <th>g</th>
  </tr>
  <tr>
    <td>5</td>
    <td>1</td> 
    <td>control</td>
  </tr>
  <tr>
    <td>33</td>
    <td>0</td> 
    <td>melarsoprol</td>
  </tr>
</table>