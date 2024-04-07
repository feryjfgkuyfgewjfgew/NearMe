# Ex04 Places Around Me
## Date: 07-04-2024

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<script>
    function coordinate(event)
    {
        let x=event.clientX;
        let y=event.clientY;
        document.getElementById("text1").value=x;
        document.getElementById("text2").value=y;
    }
</script>
<body align="center">
    <h1 style="color: chartreuse;"><b>SETHUKKARASI C(212223230201)<br>COLLEGES IN KELAMBAKKAM</b></h1>
    <img src="map.png" width="1800px" usemap="#MyMap" onmousemove="coordinate(event)"><br>
    <map name="MyMap">
        <area shape="rect" coords="1110,660,1170,730" href="https://care.edu.in/" title="Chettinad Academy Of Research And Education">
        <area shape="rect" coords="935,1320,980,1395" href="http://www.ssn.edu.in/" title="Sri Sivasubramaniya Nadar College of Engineering">
        <area shape="rect" coords="1310,315,1355,385" href="https://www.aiht.ac.in/" title="Anand Institute of Higher Technology">
        <area shape="rect" coords="1230,570,1290,640" href="https://hindustanuniv.ac.in/" title="Hindustan Institute of Technology & Science">
        <area shape="rect" coords="1180,155,1235,230" href="https://www.cmi.ac.in/" title="Chennai Mathematical Institute">
        <area shape="rect" coords="895,1110,945,1190" href="http://www.smkfomra.ac.in/" title="SMK Fomra Institute of Technology">        
    </map>
    X coordinate <input type="text" name="" id="text1">
    Y coordinate <input type="text" name="" id="text2">
</body>
</html>
```

## OUTPUT
![alt text](arasi/mapapp/static/1.png)
![alt text](arasi/mapapp/static/2.png)
![alt text](arasi/mapapp/static/3.png)
![alt text](arasi/mapapp/static/4.png)
![alt text](arasi/mapapp/static/5.png)
![alt text](arasi/mapapp/static/6.png)
![alt text](arasi/mapapp/static/7.png)
![alt text](arasi/mapapp/static/8.png)


## RESULT
The program for implementing image maps using HTML is executed successfully.
