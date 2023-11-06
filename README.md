# Ex04 Places Around Me
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
<title> Image Map </title>
</head>
<body>
<h1 align="center">
<font color="red"><b>kanchipuram</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Places Around Me</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="706" width="1804">
<map name="MyCity">
<area shape="rectangle" coords="1040,581,828,510"  href="silk.html" title="PS silk sarees">
<area shape="rectangle" coords="734,601,522,530"  href="ground.html" title="collector ground">
<area shape="rectangle" coords="747,145,535,74" href="theatre.html" title="babu theatre">
<area shape="rectangle" coords="1043,130,814,57"  href="temple.html" title="vazhakaratheeswarar temple">
<area shape="rectangle" coords="359,534,130,461" href="school.html" title="bharathi school">
</map>
</center>
</body>
</html>

<html>
<head>
<title>Kanchipuram</title>
</head>
<body bgcolor="brown">
<h3 align="center">Babu theatre</h3>
<hr size="3" color="red">
<p align="justify">
 babu theatre in kanchipuram
</p>
<p>
   Movie in babu theatre is super. The screen display while projecting the cinemas is excellent.
   The audio quality of the movie is fully atomos audio.
</p>
</body>
</html>

<html>
<head>
<title>Kanchipuram</title>
</head>
<body bgcolor="green">
<h3 align="center">bharathi school</h3>
<hr size="3" color="red">
<p align="justify">
 bharathi school in kanchipuram
</p>
<p>
amil Nadu (/ˌtæmɪl ˈnɑːduː/; Tamil: [ˈtamiɻ ˈnaːɽɯ] ⓘ, abbr. TN) is the southernmost state of India. The tenth largest Indian state by area and the sixth largest by population, Tamil Nadu is the home of the Tamil people, whose Tamil language—one of the longest surviving classical languages in the world—is widely spoken in the state and serves as its official language. The capital and largest city is Chennai.
</p>
</body>
</html>

<html>
<head>
<title>Kanchipuram</title>
</head>
<body bgcolor="purpel">
<h3 align="center">Temple</h3>
<hr size="3" color="red">
<p align="justify">
 vazakuratheeswarar temple in kanchipuram
</p>
<p>
    This is one of the famous Shiva temples of Kanchipuram. The temple is quite known for devotees having problems with respect to law and court. Devotees throng to this temple to get rid of any issues related to Law and believe in it for the results. Timing : 7:00 AM to 12:00 PM; 5:00 PM to 8:00 PM.
</p>
</body>
</html>

<html>
<head>
<title>Kanchipuram</title>
</head>
<body bgcolor="yellow">
<h3 align="center">collector office</h3>
<hr size="3" color="red">
<p align="justify">
collector ground at kanchipuram
</p>
<p>
    Collector office Police Ground is a cricket ground located in Kanchipuram, Tamil Nadu. The average rating of this place is 4.00 out of 5 stars based on 1 reviews. The street address of this place is RMFW+W45, Unnamed Road, Thaiyar Kullam, Kanchipuram, Tamil Nadu 631501, India. It is about 0.86 kilometers away from the Kanchipuram railway station.
</p>
</body>
</html>

<html>
<head>
<title>kanchipuram</title>
</head>
<body bgcolor="pink">
<h3 align="center">silk sarees</h3>
<hr size="3" color="red">
<p align="justify">
 ps Silk Sarees in kanchipuram
</p>
<p>
    PS Silk Sarees offers you the latest traditional Kanchipuram Silk Sarees. We offfer silk sarees with high quality soft & fine silk threads. We offer the latest trends and fashion.
    We ensure that the same quality and design of each item will reach you as you have seen on our website. We never reduce the quality of the product to make it cheaper.
    We pride ourselves on delivering the best possible shopping experience to all our customers which means that from the moment you place an order to the moment your order is delivered to your door, we are dedicated to your satisfaction.
</p>
</body>
</html>



```


## OUTPUT
![Alt text](<Screenshot (11).png>)
![Alt text](<Screenshot (12).png>)
![Alt text](<Screenshot (15).png>)
![Alt text](<Screenshot (16).png>)
![Alt text](<Screenshot (17).png>)
![Alt text](<Screenshot (18).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
