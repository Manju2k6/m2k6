<!DOCTYPE html>
<html>
<head>
<style>

table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  border: 1px solid black;
  text-align: center;
  padding: 8px;
}

th {
  background-color: #333;
  color: white;
}

td:nth-child(odd of .period) {
  background-color: #DDEBF7;
}

td:nth-child(even of .period) {
  background-color: #FFF2CC;
}

.lab-hour {
  background-color: #F4CCCC;
}

.elective-hour {
  background-color: #B7E1CD;
}

/* Tea  */
.break {
  background-color: #FFD966;
  font-weight: bold;
  writing-mode: vertical-rl;
}

/* Day  */
.day {
  background-color: #D9EAD3;
  font-weight: bold;
}

</style>
</head>

<body>

<h2 style="text-align:center;">
BANGALORE INSTITUTE OF TECHNOLOGY
</h2>

<h3 style="text-align:center;">
DEPARTMENT OF CSE
</h3>

<h3 style="text-align:center;">
TIME TABLE - V SEM, B SECTION
</h3>

<table>

<tr>
  <th>DAYS</th>
  <th>8:00<br>to<br>9:00</th>
  <th>9:00<br>to<br>10:00</th>
  <th>10:00<br>to<br>10:30</th>
  <th>10:30<br>to<br>11:30</th>
  <th>11:30<br>to<br>12:30</th>
  <th>12:30<br>to<br>1:30</th>
  <th>1:30<br>to<br>2:30</th>
  <th>2:30<br>to<br>3:30</th>
  <th>3:30<br>to<br>4:30</th>
  <th>4:30<br>to<br>5:30</th>
</tr>


<!-- MONDAY -->

<tr>
  <td rowspan="3" class="day">MON</td>

  <td class="period">CNS</td>
  <td class="period">TOC</td>

  <td rowspan="18" class="break">TEA BREAK</td>

  <td class="period">AI</td>
  <td class="period">SE</td>
  <td class="period">RM</td>
  <td>  </td>
  <td></td>
  <td></td>
  <td></td>
</tr>

<tr>
  <td class="period">KNP</td>
  <td class="period">SHG</td>
  <td class="period">MJ</td>
  <td class="period">MH</td>
  <td class="period">PR</td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
</tr>

<tr>
  <td class="period">523</td>
  <td class="period">523</td>
  <td class="period">523</td>
  <td class="period">523</td>
  <td class="period">523</td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
</tr>


<!-- TUESDAY -->

<tr>
  <td rowspan="3" class="day">TUE</td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td class="period">AI</td>
  <td class="period">SE</td>
  <td class="period">TOC</td>
  <td class="period">CNS</td>
  <td></td>
</tr>

<tr>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td class="period">MJ</td>
  <td class="period">MH</td>
  <td class="period">SHG</td>
  <td class="period">KNP</td>
  <td></td>
</tr>

<tr>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td class="period">521</td>
  <td class="period">521</td>
  <td class="period">521</td>
  <td class="period">521</td>
  <td></td>
</tr>


<!-- WEDNESDAY -->

<tr>
  <td rowspan="3" class="day">WED</td>

  <td class="period">RM</td>
  <td class="period">SE</td>
  <td class="period">TOC</td>
  <td class="period">AI</td>
  <td></td>
  <td class="lab-hour" colspan="2">WT Lab / CNS Lab</td>
  <td></td>
  <td></td>
</tr>

<tr>
  <td class="period">PR</td>
  <td class="period">MH</td>
  <td class="period">SHG</td>
  <td class="period">MJ</td>
  <td></td>
  <td class="lab-hour" colspan="2">B1+B2 / B3+B4</td>
  <td></td>
  <td></td>
</tr>

<tr>
  <td class="period">523</td>
  <td class="period">523</td>
  <td class="period">523</td>
  <td class="period">523</td>
  <td></td>
  <td class="lab-hour" colspan="2">503 / 527A</td>
  <td></td>
  <td></td>
</tr>


<!-- THURSDAY -->

<tr>
  <td rowspan="3" class="day">THU</td>

  <td></td>
  <td></td>
  <td class="elective-hour">Online</td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
</tr>

<tr>
  <td></td>
  <td></td>
  <td class="elective-hour">EVS</td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
</tr>

<tr>
  <td></td>
  <td></td>
  <td class="elective-hour">KRS</td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
</tr>


<!-- FRIDAY -->

<tr>
  <td rowspan="3" class="day">FRI</td>

  <td class="lab-hour" colspan="2">WT Lab / CNS Lab</td>
  <td class="period">TOC</td>
  <td class="period">CNS</td>
  <td></td>
  <td class="period">RM</td>
  <td class="period">SE</td>
  <td></td>
  <td></td>
</tr>

<tr>
  <td class="lab-hour" colspan="2">B3+B4 / B1+B2</td>
  <td class="period">SHG</td>
  <td class="period">KNP</td>
  <td></td>
  <td class="period">PR</td>
  <td class="period">MH</td>
  <td></td>
  <td></td>
</tr>

<tr>
  <td class="lab-hour" colspan="2">503</td>
  <td class="period">527A</td>
  <td class="period">527C</td>
  <td></td>
  <td class="period">527C</td>
  <td class="period">527C</td>
  <td></td>
  <td></td>
</tr>


<!-- SATURDAY -->

<tr>
  <td rowspan="3" class="day">SAT</td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
</tr>

<tr>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
</tr>

<tr>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
  <td></td>
</tr>

</table>

</body>
</html>
