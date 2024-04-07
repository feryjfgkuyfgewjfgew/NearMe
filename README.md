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
<body>
    <img src="new.png" width="1000px" usemap="#MyMap" onmousemove="coordinate(event)"><br>
    <map name="MyMap">
        <area shape="rect" coords="561,200,578,328" href="https://en.wikipedia.org/wiki/India" title="INDIA">
        <area shape="rect" coords="508,218,544,254" href="https://en.wikipedia.org/wiki/Pakistan" title="PAKISTAN">
        <area shape="rect" coords="598,134,668,268" href="https://en.wikipedia.org/wiki/China" title="CHINA">
        <area shape="rect" coords="288,77,324,110" href="https://en.wikipedia.org/wiki/Poland" title="POLAND">
        <area shape="rect" coords="665,293,688,307" href="https://en.wikipedia.org/wiki/Thailand" title="THAILAND">
        <area shape="rect" coords="332,216,386,258" href="https://en.wikipedia.org/wiki/Egypt" title="EGYPT">        
    </map>
    X coordinate <input type="text" name="" id="text1">
    Y coordinate <input type="text" name="" id="text2">
</body>
</html>```

## OUTPUT
![Screenshot 2024-04-07 181425](https://github.com/feryjfgkuyfgewjfgew/NearMe/assets/150319377/06f9e92d-0134-4f72-aa0c-44672c8a0a8e)
![new](https://github.com/feryjfgkuyfgewjfgew/NearMe/assets/150319377/0fbd300f-df96-47c6-9d83-5c14e3e826e6)


## RESULT
The program for implementing image maps using HTML is executed successfully.
