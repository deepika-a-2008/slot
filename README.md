# Ex03 Time Table
## Date:26/09/2025

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
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Weekly Timetable</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fdfdfd;
      padding: 20px;
    }
    h2 {
      text-align: center;
      color: #333;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    th, td {
      border: 1px solid #ccc;
      text-align: center;
      padding: 10px;
    }
    th {
      background-color: #f2f2f2;
    }
    td:nth-child(2) { background-color: #ffd6d6; } /* Monday */
    td:nth-child(3) { background-color: #d6f0ff; } /* Tuesday */
    td:nth-child(4) { background-color: #e6ffd6; } /* Wednesday */
    td:nth-child(5) { background-color: #fff0d6; } /* Thursday */
    td:nth-child(6) { background-color: #f0d6ff; } /* Friday */
  </style>
</head>
<body>
  <h2>Weekly Timetable</h2>
  <table>
    <tr>
      <th>TIME</th>
      <th>MONDAY</th>
      <th>TUESDAY</th>
      <th>WEDNESDAY</th>
      <th>THURSDAY</th>
      <th>FRIDAY</th>
    </tr>
    <tr>
      <td>08:00 - 09:00</td>
      <td>Math</td>
      <td>Science</td>
      <td>English</td>
      <td>Math</td>
      <td>History</td>
    </tr>
    <tr>
      <td>09:00 - 10:00</td>
      <td>Science</td>
      <td>Math</td>
      <td>Art</td>
      <td>English</td>
      <td>PE</td>
    </tr>
    <tr>
      <td>10:00 - 11:00</td>
      <td>English</td>
      <td>History</td>
      <td>Science</td>
      <td>PE</td>
      <td>Math</td>
    </tr>
    <tr>
      <td>11:00 - 12:00</td>
      <td>Art</td>
      <td>English</td>
      <td>Math</td>
      <td>Science</td>
      <td>English</td>
    </tr>
  </table>
</body>
</html>```


## OUTPUT

<img width="1819" height="592" alt="Screenshot 2025-09-25 162948" src="https://github.com/user-attachments/assets/480ad800-56ad-4213-8784-9ad61f00fad5" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
