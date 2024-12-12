# Ex04 Places Around Me
## Date: 07-12-2024

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

```
<!DOCTYPE html>
<html>
    <head>
        <title>
            My City
        </title>
    </head>
    <body>
        <h1 align = 'center' >
            <b>Tiruchirappalli</b>
        </h1>
        <h3 align = 'center'>
            Eswar(24006349)
        </h3>
        <center>
        <img src="bg.png" usemap="#Trichy">
        <map name="Trichy">
            <area target="_blank" alt="" title="" href="sr.html" coords="769,10,930,105" shape="rect">
            <area target="_blank" alt="" title="" href="t.html" coords="64,47,137,140" shape="rect">
            <area target="_blank" alt="" title="" href="tn.html" coords="494,161,94" shape="circle">
            <area target="_blank" alt="" title="" href="kk.html" coords="810,853,103" shape="circle">
            <area target="_blank" alt="" title="" href="ap.html" coords="950,765,928,697,1008,663,1064,755,1006,809" shape="poly">
        </map>
        </center>
    </body>
</html>
```

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Srirangam</title>
</head>
<body bgcolor="blue">
    <h1 align="center">Srirangam</h1>
    <p>Bordered by the Kaveri River, Srirangam is a city island known for being home to the vast Sri Ranganatha Swamy Temple, one of the largest in India with 81 shrines spanning 63 hectares. Pilgrims flock to the island for its many Hindu temples and wedding venues, ranging from casual to elaborate halls holding up to 1,000 guests. The area also has bridal boutiques and salons, as well as cafes and vegetarian restaurants.</p>
    
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TASMAC</title>
</head>
<body bgcolor="purple">
    <h1 align="center">TASMAC</h1>
    <p>The Tamil Nadu State Marketing Corporation Limited (TASMAC) is a company incorporated under the Companies Act, 1956 on 23.05.1983 with Registered Office at Chennai...</p>
    
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thillai Nagar</title>
</head>
<body bgcolor="cyan">
    <h1 align="center">Thillai Nagar</h1>
    <p>Thillai Nagar is the poshest locality in Tiruchirappalli in the Indian state of Tamil Nadu. It is a prominent commercial and residential locality in Trichy. Being the most busiest area in Trichy city, it has a daily floating population of 5 lakhs.</p>
    
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KK Nagar</title>
</head>
<body bgcolor="green">
    <h1 align="center">KK Nagar</h1>
    <p>K. K. Nagar or Kalaignar Karunanidhi Nagar is a residential part of Tiruchirappalli City in Tamil Nadu, India. The K. K. Nagar neighbourhood is near the Tiruchirappalli International Airport, and is the most densely populated ward in the city and also the most populous ward in the city of Tiruchirapalli.</p>
    
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Airport</title>
</head>
<body bgcolor="red">
    <h1 align="center">Airport</h1>
    <p>Tiruchirappalli International Airport is an international airport serving Tiruchirappalli in the Indian state of Tamil Nadu. The airport, spread over an area of 702.02 acres, is located on National Highway 336, about 5 km south of the city centre.</p>
    
</body>
</html>
```

## OUTPUT

![Screenshot (48)](https://github.com/user-attachments/assets/e43c1aed-a29c-479f-9990-738cd61944c9)

![Screenshot (44)](https://github.com/user-attachments/assets/97b5abe8-e0dd-464d-86ca-ec7abffeac6c)

![Screenshot (45)](https://github.com/user-attachments/assets/7ca053f5-7ce6-4484-88f5-0fca529c5456)

![Screenshot (43)](https://github.com/user-attachments/assets/a70548a4-4f62-41c0-8f96-79c9467581d1)

![Screenshot (47)](https://github.com/user-attachments/assets/6fb1fba9-aa09-4c94-88a5-709a406c39b2)

![Screenshot (46)](https://github.com/user-attachments/assets/8ec0fabc-a09e-4b9c-8c4e-2ef72505e6b7)



## RESULT
The program for implementing image maps using HTML is executed successfully.
