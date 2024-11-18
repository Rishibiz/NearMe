## Date: 

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
</head>
<script>
    function coord(event) {
        let x=event.clientX;
        let y=event.clientY;
        document.getElementById("txt1").value=x;
        document.getElementById("txt2").value=y;
    }
</script>
<body>
    <img src="map.png" width="1000px" usemap="#MapNew" onmousemove="coord(event)">
    <MAP name="MapNew">
        <AREA shape="RECT" coords="334,209,414,200" href="https://stannsmhss.com/" Title="ST.Anne's High School" >
        <AREA shape="RECT" coords="476,148,509,149" href="https://snvmhss.org/" Title="Shri Nehru Vidyalaya School" >
        <AREA shape="RECT" coords="621,152,683,155" href="https://www.hivemontessori.com/" Title="Hive Montessori School" >
    </MAP> <br>
    X coord:<input type="text" name="" id="txt1"> <br>
    Y coord:<input type="text" name="" id="txt2"> 

</body>
</html>
```

## OUTPUT
![map](https://github.com/user-attachments/assets/facfd9c6-9292-4db2-8ea1-2007a749c447)
![output 1](https://github.com/user-attachments/assets/a91c55a6-1c2c-46b8-a897-4a09026a0b37)
![output 2](https://github.com/user-attachments/assets/c54c5050-a39d-4a20-b163-7a33a3ad7a84)
![output 3](https://github.com/user-attachments/assets/74ec67c9-967f-43aa-ae4e-f529dd0f68d9)




## RESULT
The program for implementing image maps using HTML is executed successfully.
