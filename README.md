# Ex04 Places Around Me
## Date: 12/04/2024

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
    <title>Image Map</title>
</head>
<body>
    <IMG src="map.png" width="1000" height="430" usemap="#MapNew" onmousemove="coordinate(event)"></IMG>
    <MAP name="MapNew">

        <AREA shape="RECT" coords="371,310,499,356" href="https://www.sriramachandra.edu.in/medical/" Title="Ramachandra Medical Center">
        <AREA shape="RECT" coords="32,195,176,239" href="https://pmchri.ac.in/" Title="Panimalar Medical Institute">
        <AREA shape="RECT" coords="267,197,402,252" href="https://saveethadental.com/" Title="Saveetha Dental College   ">
        <AREA shape="RECT" coords="553,9,712,67" href="https://madrasmedicalmission.org.in/contact.php" Title="Madras Medical Hospital">
        <AREA shape="RECT" coords="553,9,712,67" href="https://madrasmedicalmission.org.in/contact.php" Title="Madras Medical Hospital">

    </MAP><br>
    X-coordinate <input type="text" id="X"><br>
    Y-coordinate <input type="text" id="Y">

    <script>
        function coordinate (event) {
        let x = event.clientX;
        let y = event.clientY;
        document.getElementById("X").value = x
        document.getElementById("Y").value = y
        } 
    </script>

</body>
</html>
```

## OUTPUT
![Screenshot (158)](https://github.com/Jayalakshm1/NearMe/assets/130430542/6cabbce9-3036-41de-a6dc-42e820e61efc)
![Screenshot (163)](https://github.com/Jayalakshm1/NearMe/assets/130430542/194a4982-d293-4416-bc05-0440f15322e6)
![Screenshot (166)](https://github.com/Jayalakshm1/NearMe/assets/130430542/636b3db9-dd81-4c1a-a6cd-c7f0a244e8e1)
![Screenshot (165)](https://github.com/Jayalakshm1/NearMe/assets/130430542/cb2f54ad-d273-4ede-8f51-fe142798d8d3)
![Screenshot (164)](https://github.com/Jayalakshm1/NearMe/assets/130430542/23345055-5f3a-4f27-be01-b70c9457b8e3)










## RESULT
The program for implementing image maps using HTML is executed successfully.
