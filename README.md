# Ex03 Places Around Me
## Date:28.11.25

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
~~~

gpsmap.html:

<html>
    <head>
        <title>Chennai Map</title>
    </head>
    <body>
        <h1 align="center" style="color: green;"><b>TamilNadu: Chennai</b></h1>
        <h2 align="center" style="color: chocolate;">Name: Siddharth CM</h2>
        <img src="Screenshot 2025-11-26 112947.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Koyamedu" title="Koyamedu" href="koyamedu.html" coords="642,152,941,253" shape="rect">
    <area target="" alt="West Mambalam" title="West Mambalam" href="westmambalam.html" coords="1147,634,80" shape="circle">
    <area target="" alt="Government Museum" title="Government Museum" href="museum.html" coords="1636,206,91" shape="circle">
    <area target="" alt="Mugalivakkam" title="Mugalivakkam" href="mugalivakkam.html" coords="226,823,463,909" shape="rect">
    <area target="" alt="Saidapet" title="Saidapet" href="saidapet.html" coords="1071,830,1288,897" shape="rect">
</map>
    </body>
</html>

koyamedu.html:

<html>
    <body bgcolor="red">
        <h1 align="center"><b><u>Chennai-Koyamedu</u></b></h1>
        <img src="koyamedu.jpg" width="700" height="300" style="padding-left: 350;">
        <p><h3><b><u>Description of Koyambedu:</u></b></h3><br>
Koyambedu is one of the busiest and most important localities in Chennai, known for its major transport and market hubs. It is home to the Koyambedu Bus Terminus (CMBT), one of Asia’s largest bus stations, connecting Chennai with towns and cities across Tamil Nadu and neighbouring states. The area is also famous for the Koyambedu Wholesale Market Complex (KWMC), one of India’s biggest wholesale markets for vegetables, fruits, and flowers.
Apart from transport and trade, Koyambedu has rapidly developed with shopping centres, residential apartments, restaurants, and metro connectivity. Because of its central location and continuous activity, Koyambedu is considered one of the liveliest and most well-connected parts of Chennai.</p>

    </body>
</html>

westmambalam.html:

<html>
    <body>
        <h1 align="center"><b><u>Chennai-West MamBalam</u>:-</b></h1>
        <img src="westmambalam.jpg" width="700" height="300" style="padding-left: 350;">
        <p><h3><b><u>Description of West MamBalam:</u></b></h3><br>
            West Mambalam is a well-known residential neighborhood in Chennai, famous for its peaceful atmosphere, traditional culture, and strong community life. Located close to T. Nagar and connected by the Mambalam Railway Station, it is one of the city’s most convenient and accessible areas. The locality is known for its temples, bustling markets, and classic Chennai lifestyle.
Ranganathan Street and Lake View Road bring daily crowds for shopping, while the quiet interior streets are lined with homes, schools, and small eateries. West Mambalam is also known for its religious heritage, with the Ayodhya Mandapam and several popular temples attracting devotees throughout the year. With its blend of tradition, connectivity, and comfort, West Mambalam remains one of Chennai’s most loved residential areas.</p>
    </body>
</html>

musemum.html:

<html>
    <body>
        <h1 align="center"><b><u>Chennai-Government Museum</u>:-</b></h1>
        <img src="museum.jpg" width="700" height="300" style="padding-left: 350;">
        <p><h3><b><u>Description of Chennai Government Museum,Egmore:</u></b></h3><br>
            A museum is a place where valuable objects from history, science, art, and culture are collected, preserved, and displayed for the public. It helps people learn about the past and understand how societies, traditions, and knowledge have developed over time. Museums often contain artefacts, paintings, sculptures, fossils, documents, and models that tell stories about different eras and civilizations.
Modern museums also use interactive displays, videos, and digital technology to make learning more engaging. They are important educational spaces that inspire curiosity, creativity, and respect for heritage. Whether it is an art museum, science museum, or history museum, each one plays a vital role in protecting knowledge and sharing it with future generations.</p>
    </body>
</html>

mugalivakkam.html:

<html>
    <body>
        <h1 align="center"><b><u>Chennai-Mugalivakkam</u>:-</b></h1>
        <img src="mugalivakkam.png" width="700" height="300" style="padding-left: 350;">
        <p><h3><b><u>Description of Mugalivakkam:</u></b></h3><br>Mugalivakkam is a fast-growing residential neighbourhood located in the western part of Chennai, near Porur. It has developed rapidly in recent years due to its convenient location, calm environment, and expanding infrastructure. The area is close to major IT hubs like DLF IT Park and Commerzone, making it a preferred place for working professionals.
Mugalivakkam offers a mix of apartments, independent houses, parks, supermarkets, and local shops, giving it a comfortable community feel. It also has good road connectivity to Porur, Guindy, and Chennai International Airport. With nearby schools, hospitals, and improving transportation facilities, Mugalivakkam has become one of the most promising and peaceful residential zones in the city.
            </p>
    </body>
</html>

saidapet.html:

<html>
    <body>
        <h1 align="center"><b><u>Chennai-Saidapet</u>:-</b></h1>
        <img src="saidapet.jpg" width="700" height="300" style="padding-left: 350;">
        <p><h3><b><u>Description of Saidapet:</u></b></h3><br>
            Saidapet is one of Chennai’s oldest and most important neighbourhoods, known for its mix of tradition, commerce, and strong connectivity. Located along Mount Road and close to Guindy, it serves as a major gateway between South and Central Chennai. The area is well-connected through the Saidapet Railway Station, Metro Station, and a busy bus terminus, making it a key transport hub.
Saidapet is also home to the historic Kaaraneeswarar Temple, bustling markets, government offices, and educational institutions. The neighbourhood has a lively atmosphere with small shops, eateries, and residential colonies spread across its streets. With both heritage landmarks and modern facilities, Saidapet remains a vibrant and centrally located part of Chennai.
        </p>
    </body>
</html>

~~~




## OUTPUT
![alt text](<Screenshot 2025-11-28 110911.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
