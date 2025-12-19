# Ex03 Time Table
## Date:19/12/25

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Time Table</title>
  <style>
    table {
      border-collapse: collapse;
      width: 100%;
      text-align: center;
    }
    th, td {
      border: 1px solid black;
      padding: 8px;
    }
    th {
      background-color: #f2f2f2;
    }
    .header-img {
      display: block;
      margin: 0 auto 20px auto;
      max-width: 200px; /* adjust size as you like */
    }
  </style>
</head>
<body>
  <!-- Sample Image (replace "sample.jpg" with your image path) -->
  <img src="/static/logo.png" alt="Header Image" class="header-img">

  <h2 style="text-align:center;">Weekly Time Table</h2>

  <table>
    <tr>
      <th>Time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
      <th>Saturday</th>
    </tr>
    <tr>
      <td>8:00–9:00</td>
      <td>PYTHON</td>
      <td>-fwd</td>
      <td></td>
      <td>-</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>9:00–10:00</td>
      <td>PYTHON</td>
      <td>fwd</td>
      <td></td>
      <td>-</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>10:00–11:00</td>
      <td>-fwd</td>
      <td>P</td>
      <td></td>
      <td></td>
      <td>python</td>
      <td>-</td>
    </tr>
    <tr>
      <td>11:00–12:00</td>
      <td>fwd</td>
      <td></td>
      <td></td>
      <td>-</td>
      <td></td>
      <td>-</td>
    </tr>
    <tr>
      <td>1:00–2:00</td>
      <td>Web </td>
      <td></td>
      <td>mentor meet</td>
      <td>wed</td>
      <td>Communicative English<</td>
      <td></td>
    </tr>
    <tr>
      <td>2:00–3:00</td>
      <td>Web </td>
      <td> </td>
      <td>mentor meet</td>
      <td>wed</td>
      <td><Communicative English</td>
      <td></td>
    </tr>
    <tr>
      <td>3:00–4:00</td>
      <td>Communicative English</td>
      <td>-PYTHON</td>
      <td>Web App Dev</td>
      <td>Communicative English</td>
      <td>Communicative English</td>
      <td>wed</td>
    </tr>
    <tr>
      <td>4:00–5:00</td>
      <td>Communicative English</td>
      <td>-PYTHON</td>
      <td>Web App Dev</td>
      <td><Communicative English/td>
      <td>Communicative English</td>
      <td>wed</td>
    </tr>
  </table>
</body>
</html>
````

## OUTPUT
<img width="1287" height="565" alt="Screenshot 2025-12-19 223804" src="https://github.com/user-attachments/assets/787eff46-4e2e-42ee-96fc-426180c0eb1e" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
