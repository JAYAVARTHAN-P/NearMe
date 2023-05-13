# Ex04 Places Around Me
## AIM

To develop a website to display details about the places around my house.
## DESIGN STEPS
STEP 1

Create a Django admin interface.
STEP 2

Download your city map from Google.
STEP 3

Using <map> tag name the map.
STEP 4

Create clickable regions in the image using <area> tag.
STEP 5

Write HTML programs for all the regions identified.
STEP 6

Execute the programs and publish them.
## CODE

map.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Palacode</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>JAYAVARTHAN-P(22008689)</b></font>
</h3>
<center>
<img src="/static/images/map1.png" usemap="#MyCity" height="590" width="1490">
<map name="MyCity">
<area shape="rectangle" coords="850,311,950,365" href="/static/html/tm.html"
title="Tomato Market">
<area shape="rectangle" coords="712,41,872,126" href="/static/html/hmg.html"
title="Mayura Grand">
<area shape="rectangle" coords=990,315,1020,169" href="/static/html/pk.html"
title="Poovankottai">
<area shape="rectangle" coords="661,161,821,215" href="/static/html/po.html"
title="Post Office">
<area shape="rectangle" coords="1206,311,1266,365" href="/static/html/ll.html"
title="Lotus Lake">
</map>
</center>
</body>
</html>

hmg.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Mayura Grand</title>
    </head>
    <body bgcolor="lime">
    <h1 align="center">
    <font color="red"><b>Palacode</b></font>
    </h1>
    <h3 align="center">
    <font color="blue"><b>Mayura Grand</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="5">
    Conveniently situated in the Palacode pat of Dharmapuri, this property puts you close to attractions and interesting dining options</font>
    </p>
    </body>
</html>

ll.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Lotus Lake</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Palacode</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Lotus Lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
THAMAIRAI LAKE is in Palacode Dharmapuri District Tamil Nadu State in India. THAMARAI LAKE near by pincode areas are 636805(Mallupatti),636809 (Paupparapatti),635205(Periyanahalli),.Near by railway Stations are Palacode. It is in 22km distance to Dharmapuri City.</font>
</p>
</body>
</html>

pk.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>PoovanKottai</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Palacode</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>PoovanKottai</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
GitHub - 22008650/NearMe https://github.com/22008650/nearme
11 of 17 08/05/2023, 21:44
<b>
Poovankottai is a small Village/hamlet in Karimangalam Block in Dharmapuri District of Tamil Nadu State, India. It comes under Pulikal Panchayath.
</font>
</p>
</body>
</html>

po.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Post Office</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Palacode</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Post office
</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Palacode S.O post officce belongs to Palacode,Dharmapuri, Tamil Nadu. This Post Office belongs to Tamil Nadu circle, and further under Coimbatore Region and Dharmapuri division. The post office Palacode S.O type is a Sub Post Office. Usual business hours for Palacode Sub Post Office is from 8 am to 4 pm and working days are from Monday to Saturday. This doesn't include public holidays or extended business hours as declared by Indian post office.
 </p>
</body>
</html>

tm.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Tomato Market</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Palacode</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Tomato Market</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
GitHub - 22008689/NearMe https://github.com/22008650/nearme
12 of 17 08/05/2023, 22:12
Output:
Palacode Tomato Market in Dharmapuri is one of the leading bussiness in the Tomato Wholesalers. Also known for Tomato Wholesalers, Vegatable Vendors,Tomato Retailers and much more. Find Address, Contact Number, Reviews & Ratings, Photos, Maps of Palacode Tomato Market, Dharmapuri.
Palacode Tomato Market in Palacode, Dharmapuri is a top player in the category Tomato wholesalers in the Dharmapuri. This well=know establishment acts as a one-stop destination servicing customers both local and from other parts of Dharmapuri. Over the course of its joourney, this business has establishee a firm foothold in it's industry. The belief that customer satisfaction is as important as their products and services, have helped this establishment garner a vast base of customers, which continues to grow by the day. This business employs individuals that are dedicated towards their respective roles and put in a lot of effort to achieve the common vision and larger goals of the company. In the nea future, this business aims to expand its line of products and services and cater to a larger client base.In Dharmapuri, this establishment occupies a prominent location in Palacode. It is an effortless task in commuting to this establishment as there are various modes of transport readily available. It is known to provide top service in the following categories. Tomato Wholesalers, Vegatable Vendors,Tomato Retailers.</b>
</font>
</p>
</body>
</html> 

## OUTPUT



## HTML VALIDATOR


## RESULT
The program for implementing image maps using HTML is executed successfully.
