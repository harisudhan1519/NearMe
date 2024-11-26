# Ex04 Places Around Me
## Date: 22/11/2024

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
            <font color="red">KALLAKURICHI</font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>HARISUTHAN S [24004236]</b></font>
        </h3>
        <center>
            <img src="map.png.png" usemap="#My City" height="610" width="1450">
        <map name="My City">
            <area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town"
            <map name="image-map">
                <area target="" alt="kottaimedu" title="kottaimedu" href="kottaimedu.html" coords="839,452,1030,381" shape="rect">
                <area target="" alt="anna nagar" title="anna nagar" href="anna nagar.html" coords="830,643,994,692" shape="rect">
                <area target="" alt="siruvangur" title="siruvangur" href="siruvangur.html" coords="993,243,1172,306" shape="rect">
                <area target="" alt="MedPlus hospital" title="MedPlus hospital" href="MedPlus hospital.html" coords="570,421,759,492" shape="rect">
                <area target="" alt="Adyar Ananda Bhavan" title="Adyar Ananda Bhavan" href="Adyar Ananda Bhavan.html" coords="449,805,670,879" shape="rect">
            </map>
            </map>   
        </center>
    </body>
</html> 



Adyaranandabhavan.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="cyan">
    <h1 align="center">ADYAR ANANDA BHAVAN</h1>
    <p>Adyar Ananda Bhavan (A2B) in Kallakurichi is a popular destination for food lovers, offering a delightful mix of traditional South Indian cuisine and a variety of other dishes. Renowned for its quality and authentic taste, A2B has become a favorite spot for locals and travelers alike. The restaurant is especially famous for its freshly prepared dosas, idlis, vadas, and sweets like Mysore Pak and Badam Halwa, which are a testament to the rich culinary heritage of Tamil Nadu.

        Strategically located in Kallakurichi, A2B provides a comfortable and clean dining environment, making it ideal for family outings, quick snacks, or even festive celebrations. Its menu also includes North Indian and Chinese options, catering to diverse tastes. With consistent quality, excellent service, and a reputation for hygiene, Adyar Ananda Bhavan in Kallakurichi is more than just a restaurant—it's a culinary landmark in the region.</p>
</body>
</html




annanagar.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="pink">
    <h1 align="center">ANNA NAGAR</h1>
    <p>Anna Nagar in Kallakurichi is a vibrant and fast-developing residential area known for its modern infrastructure and convenient amenities. Situated in the growing town of Kallakurichi, Anna Nagar has become a sought-after locality due to its accessibility and proximity to schools, colleges, markets, and healthcare facilities. The area is a blend of urban lifestyle and community living, attracting people from various walks of life.

        Anna Nagar's streets are well-planned, with an emphasis on cleanliness and greenery, providing a peaceful environment for its residents. It serves as a hub for small businesses, shops, and eateries, adding to the convenience of daily living. The locality also celebrates various cultural and religious festivals, reflecting the diverse traditions of the people who live here. As Kallakurichi continues to grow, Anna Nagar is emerging as one of its prominent neighborhoods, offering a mix of modernity and tradition.</p>
</body>
</html




kottaimedu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="green">
    <h1 align="center">KOTTAIMETU</h1>
    <p>Kallakurichi's Kottaimedu is a notable locality in Tamil Nadu, renowned for its historical significance and cultural heritage. The name "Kottaimedu" translates to "Fort Hill," hinting at its past association with forts or fortified areas that played a role in the region's history. This area is known for its picturesque landscapes, blending natural beauty with a rustic charm that reflects the essence of rural Tamil Nadu.

        Kottaimedu serves as a hub for community gatherings, festivals, and traditional events that celebrate the rich culture of the region. The locality is surrounded by agricultural lands, showcasing the predominance of farming as a livelihood. The people of Kottaimedu are known for their warm hospitality and adherence to traditions, making it a significant part of Kallakurichi's identity. With increasing development, Kottaimedu retains its charm while slowly adapting to modern influences, creating a balance between the past and the present.</p>
</body>
</html>




medplus.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="grey">
    <h1 align="center">MEDPLUS HOSPITAL</h1>
    <p>MedPlus Hospital in Kallakurichi is a well-known healthcare facility that caters to the medical needs of the local community with professionalism and care. Equipped with modern medical equipment and staffed by experienced doctors, nurses, and support personnel, the hospital provides a wide range of services, including general medicine, emergency care, pediatrics, gynecology, and diagnostics.

        MedPlus Hospital is committed to delivering quality healthcare, ensuring timely treatment for patients in both outpatient and inpatient settings. Its clean and patient-friendly environment, coupled with its focus on affordability, has made it a trusted name in Kallakurichi. The hospital also plays a vital role in creating health awareness among the residents by conducting medical camps and health check-up drives. As a beacon of healthcare in the region, MedPlus Hospital continues to contribute significantly to the well-being of the community.</p>
</body>
</html




siruvangur.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="yellow">
    <h1 align="center">SIRUVANGUR</h1>
    <p>Siruvangur, a serene village in the Kallakurichi district of Tamil Nadu, is known for its tranquil environment and agricultural prominence. Nestled amidst lush green fields and scenic landscapes, Siruvangur embodies the rural charm and simplicity that Tamil Nadu’s countryside is celebrated for. The village thrives primarily on farming, with crops like paddy, sugarcane, and millets being cultivated, reflecting the agrarian lifestyle of its residents.

        The community in Siruvangur is close-knit, with people actively participating in cultural and religious events. Temples in and around the village serve as spiritual and social hubs, hosting festivals that draw visitors from neighboring areas. Despite its traditional roots, Siruvangur is gradually witnessing development, with better connectivity and access to essential services enhancing the quality of life for its residents. This blend of tradition and progress makes Siruvangur a noteworthy part of the Kallakurichi district.
        
        
        
        
        
        
        
        
        </p>
</body>
</html

```

## OUTPUT
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (46).png>)
![alt text](<Screenshot (47).png>)
![alt text](<Screenshot (48).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
