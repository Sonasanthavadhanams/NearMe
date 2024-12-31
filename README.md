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
```
<html>
    <head>
        <title>MY CITY</title>
    </head>
    <body>
        
        <h1 align="center">
        <font color="blue"><b>VILLIVAKKAM</b></font>
    </h1>
    <h1 align="center"<b>SONA .S (24900459)</h1>
        <p>Villivakkam is a neighbourhood of Chennai, Tamil Nadu, India. It is served by the Villivakkam railway station on the Chennai Central–Arakkonam suburban section. Villivakkam is the largest state assembly constituency in Tamil Nadu in terms of number of voters.The real name of Villivakkam is Vilvaaranyam. An old Shiva temple here is built by Sage Agasthiyar and there are many vilvam (bael) trees here, hence it earned the name Vilva Aaranyam, which means the "jungle of bael trees". As time passed, the name changed into Villivakkam.</p>
        
        <img src="map.png" usemap="#test" height="550" width="1200">
        <map name="test">
            <area shape="rect" alt="Dummy" coords="50,0,300,250" href="1.html" target="_blank">
            <area shape="rect" alt="Dummy" coords="644,400,733,430" href="2.html" target="_blank">
            <area shape="rect" alt="Dummy" coords="634,430,700,536" href="3.html" target="_blank">
            <area shape="rect" alt="Dummy" coords="741,300,850,380" href="4.html" target="_blank">
            <area shape="rect" alt="Dummy" coords="620,200,720,250" href="5.html" target="_blank">
        </map>
    </body>
</html>

1.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport">
    <title>1</title>
    <style>
        body {
            margin: 0;
            padding: 0;
        }


        h2 {
            text-align: center;
            background-color: bisque;
            margin: 0;
            padding: 2rem;
        }
        .d-flex {
            display: flex;
            justify-content: center;
        }
    </style>
</head>

<body>
    <h2> This is korattur lake</h2>
    <p>A lake in Chennai, India that is part of the North Chennai Development Scheme. The lake is being developed to include a walking track, children's play area, natural viewing area, parking, drinking water, artificial waterfall, garden, and illuminated fish tanks. 
        Korattur Lake in Chennai, India
        Also known as Vembu Pasumai Thittu, this lake is located in Korattur, Chennai, India. It is one of the largest lakes in the western part of the city. </p>
    
</body>

</html>


2.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<>, initial-scale=1.0">
    <title>2</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h2> This is Chennai Rail Museum</h2>
    <p>The Chennai Rail Museum is a railway museum in Chennai, Tamil Nadu, India. The museum opened on 16 April 2002 in the Furnishing Division of the Integral Coach Factory (ICF) near Perambur. The 6.25-acre (2.53 ha) museum has technical and heritage exhibits, with a sizable collection of steam engines from the British Raj. It also has vintage coaches (such as Ooty trains), which were endemic on Indian railways. Most of the older models were manufactured by the North British Locomotive Company,[1] with some trains in the collection dating back more than a century.[</p>
    </body>
</html>

3.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<>, initial-scale=1.0">
    <title>3</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h2> This is Integral Coach Factory</h2>
    <p>Integral Coach Factory is an Indian manufacturer of rail coaches. Established in 1955, it is located in Perambur in Chennai and is the largest rail coach manufacturer in the world. It is owned and operated by the Indian Railways and is the oldest amongst the five rake production units of the Indian Railways. While the facility initially manufactured ICF coaches, it currently manufactures LHB coaches and electric multiple units including the semi-high speed Vande Bharat train-sets.</p>
    
    </body>
</html>

4.html

!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<>, initial-scale=1.0">
    <title>4</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h2> This is ICF Lake 1</h2>
    <p>The lake had been used as a source of drinking water in the region since the 1930s, when the reservoir was constructed.[2] Till the 1950s, the reservoir was treated through a filtration unit and supplied as drinking water. From the 1950s, the reservoir began to get polluted due to mixing with oil waste and later by linking stormwater drain from the Villivakkam area, and drinking water supply was discontinued.[2] In 2017, the ICF conducted surveys and renovated the lake at a cost of ₹ 10 million[3] by removing sludge using dredgers, introducing new fish varieties, and building walking track around the lake.</p>
    
    </body>
</html>

5.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<>, initial-scale=1.0">
    <title>5</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h2> This is ECI HOPE </h2>
    <p> HISTORICAL STATEMENT The Evangelical Church of India was founded by the Oriental Missionary Society, newly called One Mission Society, whose founders Mrs. & Mr. Charles E. Cowman and Mr. E. Kilbourne commenced OMS ministry in the year 1901 in Japan.</p>
    
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (46).png>)
![alt text](<Screenshot (47).png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.


