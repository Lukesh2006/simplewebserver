# EX01 Developing a Simple Webserver
## Date: 25/11/24

## AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <head><title>SEC timetable</title></head>
  
    
        <body>
            <center><img src="saveetha logo.jpg" height="150" width="700"></center>
            <center><h3>LUKESH (24901128)</h3></center>
            <style>
               
                table{
                    border-collapse:collapse;
                }
            </style>
            <center><table border="10"width="800"height="300">
                <tr>
                    <th bgcolor="purple">day/time</th>
                    <th bgcolor="purple">Monday</th>
                    <th bgcolor="purple">Tuesday</th>
                    <th bgcolor="purple">Wednesday</th>
                    <th bgcolor="purple">Thursday</th>
                    <th bgcolor="purple">Friday</th>
                    <th bgcolor="purple">Saturday</th>
                </tr>
                <tr>
                    <th bgcolor="purple">8-10</th>
                    <th colspan="1" align="center"bgcolor="cyan">FREE SLOT</th>
                    <th bgcolor="cyan">Environmental science</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    </tr>
                <tr>
                    <th bgcolor="purple">10-12</th>
                    <th bgcolor="cyan">Web development</th>
                    <th bgcolor="cyan">Physics</th>
                    <th bgcolor="cyan">C programming</th>
                    <th bgcolor="cyan">Communicative english</th>
                    <th bgcolor="cyan">C programming</th>
                    <th bgcolor="cyan">Probality and queueing models</th>
                </tr>
                <tr>
                    <th bgcolor="purple">12-01</th>
                    <th bgcolor="purple">Lunch</th>
                    <th bgcolor="purple">Lunch</th>  
                    <th bgcolor="purple">Lunch</th>  
                    <th bgcolor="purple">Lunch</th>  
                    <th bgcolor="purple">Lunch</th>  
                    <th bgcolor="purple">Lunch</th>                  
                </tr>
                <tr>
                    <th bgcolor="purple">01-03</th>
                    <th bgcolor="cyan">B.eee</th>
                    <th bgcolor="cyan">Communicative english</th>
                    <th bgcolor="cyan">Mentor meet</th>
                    <th bgcolor="cyan">Web development</th>
                    <th bgcolor="cyan">Probability and queueing models</th>
                    <th bgcolor="cyan">Physics</th>
                </tr>
                <tr>
                    <th bgcolor="purple">03-05</th>
                    <th colspan="0"align="center"bgcolor="cyan">FREE SLOT</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    <th bgcolor="cyan">B.eee</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    <th bgcolor="cyan">Career developmemt</th>
                    <th bgcolor="cyan">Web developmemt</th>
                </tr>
            </table>
            <br>
            <table border="3" width="600">
                <tr>
                    <td>S.no</td>
                    <td>Subject code</td>
                    <td>Subject name</td>
                </tr>
                <tr>
                    <td>01</td>
                    <td>19AI304</td>
                    <td>C programming</td>
                </tr>
                <tr>
                    <td>02</td>
                    <td>19AI414</td>
                    <td>Web development</td>
                </tr>
                <tr>
                    <td>03</td>
                    <td>19EE305</td>
                    <td>B.eee</td>
                </tr>
                <tr>
                    <td>04</td>
                    <td>19EN101</td>
                    <td>Communicative english</td>
                </tr>
                <tr>
                    <td>05</td>
                    <td>19EY708</td>
                    <td>Career developmemt</td>
                </tr>
                <tr>
                    <td>06</td>
                    <td>19MA222</td>
                    <td>Probability and queueing models</td>
                </tr>
                <tr>
                    <td>07</td>
                    <td>SH3214</td>
                    <td>Physics</td>
                </tr>
                <tr>
                    <td>08</td>
                    <td>SH3214</td>
                    <td>Environmrntal science</td>
                </tr>
            </table>
        </body>
</html>
```

## OUTPUT:
![alt text](output.png)

![simple1 ](https://github.com/user-attachments/assets/a8b62066-6bd1-4351-af8f-229792d1bdb4)




## RESULT:
The program for implementing simple webserver is executed successfully.
