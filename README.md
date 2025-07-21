# table
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>first task table</title>
  <style>
    {

      th,
      td {
        border: 2px solid black;
      }
    }
  </style>
</head>

<body>
  <img src="./Screenshot 2025-07-06 020035.png" alt="">
  <table border="1" style="font-size: xx-large; border: 1px solid black; border-collapse: separate; width: 100%;">
    <tr>
      <th rowspan="3">Day</th>
      <th colspan="4">seminar</th>
    </tr>
    <tr>
      <th colspan="2"> Schedule</th>
      <th colspan="2" rowspan="2">Topic</th>
    </tr>
    <tr>
      <th>Begin</th>
      <th>End</th>
    </tr>
    <tr>
      <td rowspan="2">Monday</td>
      <td rowspan="2">8:00a.m.</td>
      <td rowspan="2">5:00p.m</td>
      <td colspan="2">Intriduction to XML</td>
    </tr>
    <tr>
      <td colspan="2">validity:DTD and Relax NG</td>
    </tr>
    <tr>
      <td rowspan="3">Tuseday</td>
      <td>8:00a.m.</td>
      <td>11:00a.m.</td>
      <td rowspan="2">Xpath</td>
    </tr>
    <tr>
      <td>11:00a.m.</td>
      <td>2:00p.m.</td>
    </tr>
    <tr>
      <td>2:00p.m.</td>
      <td>5:00p.m.</td>
      <td rowspan="1.5">XSL Transformations</td>
    </tr>
    <tr>
      <td>Wednesday</td>
      <td>8:00a.m.</td>
      <td>12:00p.m.</td>
      <td>XSL Formating Objects</td>
    </tr>
  </table>
</body>

</html>
