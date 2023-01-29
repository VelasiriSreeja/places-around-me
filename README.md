# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:
### Step 1:
Take screenshots of places around your house using Google Maps.

### Step 2:
Identify a minimum of five different locations and mark them using image maps.

### STEP3:
Develop a webpage(minimum of 50 words) for each location and link it to the image region.

## Code:
### map.html:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>THOOTHUKUDI MAP</title>
    </head>
    <body style="background-color: black;">
        <center><img src="/static/images/tuti.jpg" width="1898" height="827" alt="tuti" usemap="#tuti"></center>
    <MAP name ="tuti">
        <area shape="rect" coords="445,210,501,271" alt="velavan" title="velavanhypermarket" href="/velavanhypermarket/" >
        <area shape="rect" coords="1017,409,1110,555" alt="tharuvai" title="tharuvai" href="/tharuvai/" >
        <area shape="rect" coords="367,81,428,138" alt="sureshias" title="sureshias" href="/sureshias/">
        <area shape="rect" coords="955,93,1035,159" alt="theatre" title="theatre" href="/theatre/">
        <area shape="poly" coords="1564,196,1421,527,1491,733,1609,693,1621,802,1891,819,1896,202,1811,308"  alt="port" title="port" href="/port/" >
    </map>

    </body>
</html>

```

### velavanhypermarket.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title> VELAVAN HYPER MARKET </title>
</head>
<body style="background-color: rgb(159, 207, 207)">

<h1> VELAVAN HYPER MARKET</h1>
<h3>51 A, Gin Factory Rd, Shanmugapuram, Thoothukudi, Tamil Nadu 628002</h3>
<hr color="white"></hr>
<p> Velavan Hyper Market is the only place where people can purchase anything in a single place. Almost we have has all customer needed apparels. People can see an entirely different level of Hyper Market which consist of biggest Jewellery section, a multi-level Textile shop, biggest Supermarket, separate Vessels section, Books & Stationary shop, Electronic apparels, Medical shop and children’s Play Station. </p>
<h2>ALL ARE WELCOMED TO HAVE A FUN TIME</h2>
</body>
</html>


```
### tharuvai.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title> THARUVAI </title>
</head>
<body style="background-color: rgb(159, 207, 207)">

<h1> THARUVAI</h1>
<h3>George Road 628001 Thoothukudi, India</h3>
<hr color="white"></hr>
<hr2>Thoothukudi's biggest playground and physical activity feild for the youngsters and the old</hr2>
<h3>Parks and refreshment areas included</h3>
<h4>Athletic Field,Indoor games , Badminton Complex, Soccer Field and many more</h4>
<h2> TO LEARN MORE CONTACT: XXXXXXXXX </h2>
<h2>OR VISIT IT BY YOURSELF</h2>
</body>
</html>


### port.html:

<!DOCTYPE html>
<html lang="en">
<head>
  <title> V.O. CHIDAMBARANAR PORT </title>
</head>
<body style="background-color: rgb(188, 188, 248)">

<h1> V.O. CHIDAMBARANAR PORT </h1>
<h2>The largest port in Thoothukudi, Tamil Nadu </h2>
<hr color="white"></hr>
<h2> FACTS</h2>
<ul>
    <li>is one of the 13 major ports in India.</li>
    <li>It was declared to be a major port on 11 July 1974.</li>
    <li>It is second largest port in Tamil Nadu </li>
    <li>third largest container terminal in India.</li>
</ul> 
<h4>V.O. Chidambaranar Port is an artificial port.This is the third international port in Tamil Nadu and it is second all-weather port. All V.O. Chidambaranar Port Authority's traffic handling has crossed 10 million tons from 1 April to 13 September 2008, registering a growth rate of 12.08 per cent, surpassing the corresponding previous year handling of 8.96 million tons.</h4>   
</body>
</html>

```

### theater.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title> SRI BALAKRISHNA TALKIES</title>
</head>
<body style="background-color: rgba(234, 170, 81, 0.696)">

<h1> SRI BALAKRISHNA TALKIES</h1>
<h3>Sivan Kovil Street, Thoothukudi, Tamil Nadu 628002, India</h3>
<hr color="white"></hr>
<p>Newly built theatre and maintained well. Sound effects ARE SOO GOOD .Well planned  Amble parking space for 4 as well as 2 wheelers. </p>
<H2>More Facts:</H2>
<ol>
<li> 4 Screens – Total 1754 Seats</li>
 <li>An average occupancy 60%</li>
<li> 6000 average footfalls in the complex on week days ( Monday Â– Thursday)</li>
<li>11000 average footfalls in the complex on weekends (Friday, Saturday & Sunday)</li>
<li> 600 Cars and 6000 two wheelers parked per week in the complex parking lot.</li>
</ol>
<h2>Highlights of our Renovated  Theatre</h2>
<ol>
    <li> Plush Interiors</li>
    <li> Broad Push Back Seats of 22' Inch with Cup holders</li>
    <li>Air-conditioned Lobbies</li>
    <li>Granite Flooring inside the theatre</li>
    <li> Harkness Hall Screen</li>
<H2>MOVIE TIME = FUN TIME</H2>


</ol>
</body>
</html>

```
### sureshias.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title> SURESH IAS ACADEMY</title>
</head>
<body style="background-color: rgb(199, 253, 199)">

<h1>SURESH IAS ACADEMY</h1>
<h3>162-A, Ettayapuram Road, Near Hotel Paulson, Tuticorin - 628002,
Tamilnadu, India.</h3>
<hr color="white"></hr>
<h2>Our Specialities</h2>
<ul>
    <li>Due to our 15 years experience in this training service, we have made 13,000+ students to get placed in various Government posts and in banking sector.</li>
    <li>All coaching classes are handled only by persons who have successfully completed their competitive exams.</li>
    <li>We also offer free competitive exam books that covers all syllabus.</li>
    <li>We conduct daily model exams to enrich your skills.</li>
    <li>Weekly once our students will be given motivational training.</li>
    <li>You can pay one time and continue the course until you get placed.</li>
    <li>We train our students with the best possible short cut techniques, which you will not find in any other coaching classes.</li>
    <li>We also provide hostel and library facilities.</li>
</ul>

<h2>WE HELP YOU DEFINE YOUR OWN FUTURE AND MAKE IT HAPPEN!</h2>
</body>
</html>
```
## Output:
![Screenshot_20230128_055326](https://user-images.githubusercontent.com/118344328/215286868-f4c33557-0ec2-46a9-8950-577fd6cc742a.png)
![Screenshot (57)](https://user-images.githubusercontent.com/118344328/215305111-8d03d51a-3e19-41c3-8588-9d0cc03552bd.png)
![Screenshot (58)](https://user-images.githubusercontent.com/118344328/215305117-ea78b7c3-963d-4739-88f2-3b0b2c64f42a.png)
![Screenshot (59)](https://user-images.githubusercontent.com/118344328/215305120-de9e6878-1ca3-48f9-83b7-1cdf93324734.png)
![Screenshot (60)](https://user-images.githubusercontent.com/118344328/215305123-70ecafba-f225-43ce-b405-133715692bd3.png)
![Screenshot (61)](https://user-images.githubusercontent.com/118344328/215305125-c8e9c0f9-d1d2-467e-8100-9d9a768a269d.png)
![Screenshot (62)](https://user-images.githubusercontent.com/118344328/215305128-9aba3b41-489a-46e0-8cd1-fedcbfa29f20.png)



## Result:
And thus we  developed a website to display details about the places around my house .
