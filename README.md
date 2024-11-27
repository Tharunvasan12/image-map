# Ex04 Places Around Me
## Date: 27/11/2024
## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
map.html
```
<html>
    <head>
        <title>MY CITY</title>
        <style>
            body{
                background-color:black;
            }
            header{
                text-align: center;
                color:blue;
                background-color:cyan;
                font-size: 50px;
            }
        </style>
    </head>
    <body>
        <header>
            <font><b>Theni city</b></font></header>
        
        <center>
            <h1 leftalign="center">
                <font color="white"><b>Tharunish vasan.T(24001333)</b></font>
            </h1>
            <img src="Screenshot 2024-11-26 215126.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="THEATRE" title="THEATRE" href="THEATRE.html" coords="312,24,521,80" shape="rect">
    <area target="" alt="TRENDS" title="TRENDS" href="TRENDS.html" coords="446,165,633,198" shape="rect">
    <area target="" alt="HOTEL" title="HOTEL" href="HOTEL.html" coords="430,254,672,312" shape="rect">
    <area target="" alt="RAMYAS" title="RAMYAS" href="RAMYAS.html" coords="580,355,812,398" shape="rect">
    <area target="" alt="SALON" title="SALON" href="SALON.html" coords="182,363,345,414" shape="rect">
</map>
</html>

THEATRE.html
<html>
<style>
    body{
        background-color:black;
    }
    header{
        text-align: center;
        color:blue;
        background-color:cyan;
        font-size: 50px;
    }
    p{
        color: white;
        font-size: 30px;
    }
</style>
<header>
    <font><b>THEATRE</b></font></header><br><br><br>
    <center><img src="THEATRE.jpg" usemap="#image-map" height="350" width="400">
        <body>
            <p>athuma Theatre in Allinagaram Theni, Theni is a top player in the category Cinema Halls in the Theni. This well-known establishment acts as a one-stop .The operational hours at Fathuma Theatre are Monday:- 9:00 am - 9:00</p>
        </body>
</html>

TRENDS.html
<html>
<style>
    body{
        background-color:black;
    }
    header{
        text-align: center;
        color:blue;
        background-color:cyan;
        font-size: 50px;
    }
    p{
        color: white;
        font-size: 30px;
    }
</style>
<header>
    <font><b>TRENDS</b></font></header><br><br><br>
    <center><img src="trends.jpg" usemap="#image-map" height="350" width="400">
        <body>
            <p>India's largest fashion retail chain, TRENDS offers stylish, high-quality products across Women's wear, Men's wear, Kids' wear and Fashion accessories through a diversified portfolio of national and international brands.</p>
        </body>
        </html>
RAMYAS.html
<html>
<style>
    body{
        background-color:black;
    }
    header{
        text-align: center;
        color:blue;
        background-color:cyan;
        font-size: 50px;
    }
    p{
        color: white;
        font-size: 30px;
    }
</style>
<header>
    <font><b>RAMYAS</b></font></header><br><br><br>
    <center><img src="ramyas.jpg" usemap="#image-map" height="350" width="400">
        <body>
            <p>Ramyas Hotels is one among the most well-known hotels in THeni. Ramyas, the deluxe hotel in Theni was established during the year 2018.he most common type of accommodation in the hotel industry, a hotel is defined as an establishment that offers overnight accommodation, meals and other services. They are mainly aimed at travelers or tourists, although locals may also use them. Hotels provide private rooms and almost always have en-suite bathrooms.</p>
        </body>
        </html>

HOTEL.html
<html>
<style>
    body{
        background-color:black;
    }
    header{
        text-align: center;
        color:blue;
        background-color:cyan;
        font-size: 50px;
    }
    p{
        color: white;
        font-size: 30px;
    }
</style>
<header>
    <font><b>HOTEL</b></font></header><br><br><br>
    <center><img src="theni international.jpg" usemap="#image-map" height="350" width="400">
        <body>
            <p>The property is located in the heart of Theni, making it convenient for shopping and accessing the market. The rooms are spacious, but some guests have ...
            </p>
        </body>
        </html>

salon.html
<html>
<style>
    body{
        background-color:black;
    }
    header{
        text-align: center;
        color:blue;
        background-color:cyan;
        font-size: 50px;
    }
    p{
        color: white;
        font-size: 30px;
    }
</style>
<header>
    <font><b>SALON</b></font></header><br><br><br>
    <center><img src="naturals.jpg" usemap="#image-map"height="350" width="400" >
        <body>
            <p>Natural Ice Cream, d/b/a Naturals, is an Indian ice cream brand owned by Mumbai-based Kamaths Ourtimes Ice Creams Pvt. Ltd. It was founded by Raghunandan Srinivas Kamath who opened its first store at Juhu in Mumbai in 1984.One such remarkable story is that of Raghunandan Srinivas Kamath, the visionary behind Naturals Ice Cream, a company valued at approximately Rs 400 crore. His journey from a small village in Mangalore to becoming a renowned name in the ice cream industry is a testament to his determination, innovation, and resilience</p>
        </body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2024-11-27 091921.png>)
![alt text](<Screenshot 2024-11-27 091950.png>)
![alt text](<Screenshot 2024-11-27 092004.png>)
![alt text](<Screenshot 2024-11-27 092021.png>)
![alt text](<Screenshot 2024-11-27 092035.png>)
![alt text](<Screenshot 2024-11-27 092052.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully