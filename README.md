# Ex04 Places Around Me
# Date:24/11/2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body align="center">
    <h1>SATHYA PRIYAN S(25017409)</h1>
    
<img src="imagemap.jpg" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Golden Temple" title="Golden Temple" href="temple.html" coords="578,308,347,216" shape="rect">
    <area target="" alt="Palamathi hills" title="Palamathi hills" href="hills.html" coords="838,235,627,177,662,297" shape="poly">
    <area target="" alt="Pulimedu waterfalls" title="Pulimedu waterfalls" href="Waterfalls.html" coords="295,373,83" shape="circle">
</map>
</body>
</html>

temple.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body align="center" bgcolor="lightgreen">
    <img src = "golden temple.jpg" height="500">
    <h1><p align="center"><font color="purple">The Sripuram Golden Temple was founded by Sri Sakthi Amma and built by the Sri Narayani Peedam trust, with construction starting in 2001 and completion in 2007. The temple, located in Thirumalaikodi, near Vellore, Tamil Nadu, is dedicated to the deity Sri Lakshmi Narayani (Maha Lakshmi) and its exterior is covered with approximately 1,500 kg of pure gold.</font> </p></h1>
</body>
</html>

hills.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body align="center" bgcolor="lightgreen">
    <img src="palamathi hills.jpg" height="500" width="900">
    <h1><p align="center"><font color="purple">Palamathi Hills, also known as Balamathi Hills, is a scenic extension of the Eastern Ghats near Vellore, Tamil Nadu, known for its lush greenery, winding roads, and panoramic views of the city. It features a reserve forest, a Lord Murugan temple atop the hill accessible by steep steps, and a historical Otteri lake. Visitors can enjoy trekking, bird-watching, and picnicking amidst the region's diverse flora and fauna. </font></p></h1>
</body>
</html>

waterfalls.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body align="center" bgcolor="lightgreen">
    <img src="pulimedu waterfalls.png" height="500" width="900">
    <h1><p align="center"><font color="purple">Diamond Waterfalls is a natural attraction located in Pulimedu, Vellore, known for its calm waters and best visited during the monsoon season. While open 24 hours, it lacks public transport and accessibility for families. Nearby attractions include the Golden Temple and other natural sites and forts in the Vellore district.</font>  </p></h1>
</body>
</html>

```
# OUTPUT
![imagemap (1)](https://github.com/user-attachments/assets/cc115be1-3176-48a7-a249-28ea9d5f91a7)
<img width="1920" height="1080" alt="Screenshot 2025-10-02 002411 (1)" src="https://github.com/user-attachments/assets/d278e049-9c28-48a7-83ab-578ba30cb625" />
<img width="1920" height="1080" alt="Screenshot 2025-10-02 002426 (1)" src="https://github.com/user-attachments/assets/1da2fb98-425b-4f59-a74b-ecba1f8fcdc0" />
<img width="1920" height="1080" alt="Screenshot 2025-10-02 002439 (1)" src="https://github.com/user-attachments/assets/bbe730fe-eb11-4027-bc56-cd5d3744bde7" />

# RESULT
The program for implementing image maps using HTML is executed successfully.
