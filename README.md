# Ex04 Places Around Me
## Date: 31-10-25

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
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>KOLATHUR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vinolia Alaina. R (24003757)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="680" width="1280">
<map name="MyCity">
<area shape="rect" coords="600,280,500,300" href="mall.html" title="Sri Ganga Cinemas">
<area shape="rect" coords="640,40,780,140" href="hospital.html" title="Meridian Hospital">
<area shape="rect" coords="700,300,550,360" href="market.html" title="Kolathur Fish Market">
<area shape="rect" coords="400,400,550,500" href="park.html" title="Haridoss Lotus Pond Park">
</map>
</center>
</body>
</html>

park.html

<html>
<head>
<title>Haridoss Lotus Pond Park</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="red"><b>Haridoss Lotus Pond Park</b></font>
</h1>
<h3 align="center">
<font color="black"><b>Haridoss Lotus Pond Park - M.K.STALIN POND PARK</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Chennai" size="5">
Haridoss Lotus Pond Park, also known as M.K. Stalin Pond Park, is a serene urban oasis located in Kolathur, Chennai. This beautifully landscaped park features a large lotus pond, walking paths, and lush greenery, providing a peaceful retreat for residents and visitors alike. The park is designed to promote relaxation and outdoor activities, with benches and shaded areas for picnics and leisurely strolls. It serves as a community hub where people can connect with nature, enjoy the scenic beauty of the lotus flowers, and participate in recreational activities. Haridoss Lotus Pond Park is a testament to Chennai's commitment to creating green spaces that enhance the quality of life for its citizens.
</p>
<center>
    <img src="park.png" alt="park" width="900" height="548.5">
    </center>
</body>
</html>

hospital.html

<html>
<head>
<title>Meridian Hospital</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>MERIDIAN HOSPITAL</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Meridian Hospital, Retteri- Modern Healthcare Excellence</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Chennai" size="5">
Meridian Hospital in Retteri, Chennai, is a multi-super specialty healthcare center offering advanced medical facilities and expert care. It features modern infrastructure, including modular operation theaters, MRI and CT scan units, and 24/7 emergency services. The hospital provides treatment in various specialties such as cardiology, neurology, orthopedics, and pediatrics. With a dedicated team of doctors, nurses, and support staff, Meridian Hospital ensures quality care and patient comfort. Known for its cleanliness, technology, and compassionate service, it has become one of North Chennai's leading healthcare institutions, reflecting excellence and trust in modern medicine.



</p>
<center>
    <img src="hospital.png" alt="N4 Beach" width="900" height="545">
</center>

</body>
</html>



market.html

<html>
<head>
<title>Kolathur Fish Market</title>
</head>
<body bgcolor="lavender">
<h1 align="center">
<font color="red"><b>KOLATHUR FISH MARKET</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Kolathur Fish Market- Chennai's Aquatic Paradise</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Chennai" size="5">
    Kolathur Fish Market, located in North Chennai, is a haven for aquarium lovers and fish enthusiasts. It is one of the largest ornamental fish markets in South India, offering a wide range of colorful tropical and freshwater fish at affordable prices. From guppies and goldfish to exotic arowanas and cichlids, the market attracts both local buyers and traders. The shops also sell aquariums, fish food, plants, and accessories, making it a one-stop destination for aquarium setups. The lively atmosphere and diversity of aquatic life make Kolathur a must-visit for fish hobbyists.
</p>
<center>
    <img src="market.png"  width="900" height="548.5">
    </center>
</body>
</html>

mall.html

<html>
<head>
<title>SRI GANGA CINEMAS</title>
</head>
<body bgcolor="peachpuff">
<h1 align="center">
<font color="red"><b>SRI GANGA CINEMAS</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sri Ganga Cinemas-3 screen multiplex in Kolathur, Chennai, known for its modern facilities and reasonable prices</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Chennai" size="5">
Sri Ganga Cinemas is a popular multiplex located in Kolathur, Chennai. It features three screens equipped with modern projection and sound systems, providing an immersive movie-watching experience. The cinema offers a variety of films, from the latest Tamil blockbusters to international releases. Known for its comfortable seating, clean environment, and affordable ticket prices, Sri Ganga Cinemas attracts a diverse audience, including families, students, and movie enthusiasts. The multiplex also has a snack bar offering a range of refreshments, making it a favorite entertainment destination in the Kolathur area.
</p>
<center>
    <img src="mall.png" alt="Ganga Cinemas" width="900" height="548.5">
    </center>
</body>
</html>
```


## OUTPUT
CITY:-
<img width="1113" height="630" alt="image" src="https://github.com/user-attachments/assets/16ca6557-7904-4af9-9183-11dda8c2824d" />

PARK
<img width="1029" height="600" alt="image" src="https://github.com/user-attachments/assets/1aee7867-0f8d-4ebd-8295-52be45e67211" />

HOSPITAL
<img width="1031" height="600" alt="image" src="https://github.com/user-attachments/assets/307d1dd8-8278-44bd-a319-c7065773b2c2" />

MARKET
<img width="1033" height="585" alt="image" src="https://github.com/user-attachments/assets/13a7d5f5-7580-4637-8bed-f9c85c81b668" />

MALL
<img width="1032" height="609" alt="image" src="https://github.com/user-attachments/assets/e5406631-8b9a-4a5c-ae28-9d649386714a" />






## RESULT
The program for implementing image maps using HTML is executed successfully.
