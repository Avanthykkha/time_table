# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM

```
<doctype HTML!>
    <html>

        <head bgcolor="lightgrey">
            <center><img src="c:\Users\admin\Desktop\saveetha name tag.png" alt="Saveetha" width="800px" height="100px" ></center>
            <br>
            <h1 style="text-align: center;">MY TIMETABLE</h1></head>
            
        <body>
            
            <hr>
            <br>
            
            <style>
                table,th,td{
                    text-align: center;
                    border:3px inset black;
                    border-collapse: collapse;
                    height:60px;
                    width:900px;
                    vertical-align: center;
                    scroll-behavior: smooth;
                
                }
            </style>
            <center>
            <table>
                <tr bgcolor="beige">
                    <th>DAY</th>
                    <th>8-10</th>
                    <th>10-12</th>
                    <th rowspan="7">LUNCH</th>
                    <th>1-3</th>
                    <th>3-5</th>
                
                </tr>
                <tr bgcolor="pink">
                    <th>MON</th>
                    <td></td>
                    <td>web</td>
                    <td></td>
                    <td></td>

                </tr>
                <tr bgcolor="pink">
                    <th>TUES</th>
                    <td></td>
                    <td>phy</td>
                    <td>pyn&LA</td>
                    <td></td>

                </tr>
                <tr bgcolor="pink">
                    <th>WED</th>
                    <td>pyn&LA</td>
                    <td></td>
                    <td></td>
                    <td></td>

                </tr>
                <tr bgcolor="pink">
                    <th>THURS</th>
                    <td></td>
                    <td>pyn&LA</td>
                    <td></td>
                    <td></td>

                </tr>
                <tr bgcolor="pink">
                    <th>FRI</th>
                    <td>phy</td>
                    <td>digi</td>
                    <td>career</td>
                    <td></td>
                
                </tr>
                <tr bgcolor="pink">
                    <th>Sat</th>
                    <td>digi</td>
                    <td>Pyn & LA</td>
                    <td></td>
                    <td>Web</td>

                </tr>
            </table> 
            <br>
            <p style="font-size: larger;">
                <table>
                <tr bgcolor="beige">
                <th>web</th> <br>
                <th>pyn & LA</th> <br>
                <th>career</th><br>
                <th>phy</th><br>
                <th>digi</th><br></tr>
            
                <tr bgcolor="pink">
                <td> Web Development</td>
                <td> Python and Linear Algebra</td>
                <td>Career Development</td>
                <td>Physics</td>
                <td>Digital Electronics</td>
                

                <tr bgcolor="pink">
                    <td> 19AI414</td>
                    <td> 19AI301C</td>
                    <td> 19EY708</td>
                    <td> SH3214</td>
                    <td> 19EE404</td></table></tr>
                 

            </p>
            </center>
        </body>
    </html>
```
# OUTPUT
![Screenshot 2024-12-02 115016](https://github.com/user-attachments/assets/f49bbf45-20a9-4cb2-a3b8-87a873101249)


![Screenshot 2024-12-02 115143](https://github.com/user-attachments/assets/a3dc5c02-8855-4480-b1c3-a2467d23c792)



# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
