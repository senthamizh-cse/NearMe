# Ex04 Places Around Me
## Date: 26/03/2024

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
## mapp.html
<html>
    <head>
        <h2><center>Jayamkondam</center></h2>
        <h3><center>Senthamizh-212221040150</center></h3>
    <hr>
    </head>
    <body bgcolor="brown">
    <img src="Screenshot 2024-03-21 142121.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="JKS Deluxe" title="JKS Deluxe" href="lodge.html" coords="1028,361,1215,432" shape="rect">
    <area target="" alt="kannarapalayam" title="kannarapalayam" href="palayam.html" coords="589,532,767,493,813,587,696,632,576,592" shape="poly">
    <area target="" alt="sengunthapuram" title="sengunthapuram" href="puram.html" coords="445,183,106" shape="circle">
    <area target="" alt="karadikulam" title="karadikulam" href="kulam.html" coords="771,734,922,805" shape="rect">
    <area target="" alt="gangani farm house" title="gangani farm house" href="farm.html" coords="1466,123,123"  shape="circle">
</map>
</body>
</html>

## palayam.html

<html>
    <head>
        <h2><center>Jayamkondam</center></h2>
        <h3><center>kannarapalayam</center></h3>
    <hr>
    </head>
    <body bgcolor="red">
        <p>
            palayam is the village which consists majority pepole of MBC community.
            It is famous for the ponds in this village
            And then the pepole of the village
        </p>

</body>
</html>


## puram.html

<html>
    <head>
        <h2><center>Jayamkondam</center></h2>
        <h3><center>sengunthapuram</center></h3>
    <hr>
    </head>
    <body bgcolor="white">
        <p>
            sengunthapuram is the village which consists majority pepole of BC community.
            It is famous for the temple in this village
            And then the pepole of the village

        </p>
   
</body>
</html>

## lodge.html

<html>
    <head>
        <h2><center>Jayamkondam</center></h2>
        <h3><center>Senthamizh-212221040150</center></h3>
    <hr>
    </head>
    <body bgcolor="brown">
        <p>
            JSK lodge is famous for its better service
            And then for their hospitality.

        </p>
    
</body>
</html>

## farm.html

<html>
    <head>
        <h2><center>Jayamkondam</center></h2>
        <h3><center>gangani farm house</center></h3>
    <hr>
    </head>
    <body bgcolor="green">
    <p>
       Gangani farm is the huge house in the village of elaiyur.
       And it is special for its architecture
    </p>
</body>
</html>

## kulam.html

<html>
    <head>
        <h2><center>Jayamkondam</center></h2>
        <h3><center>karadikulam</center></h3>
    <hr>
    </head>
    <body bgcolor="light blue">
        <p>
            kulam is the village which consists majority pepole of BC/OC community.
            It is famous for the windmill in this village
            And then the pepole of the village
        </p>
    
</body>
</html>

```


## OUTPUT
![alt text](<Screenshot 2024-03-26 142817.png>)
![alt text](<Screenshot 2024-03-26 142919.png>)
![alt text](<Screenshot 2024-03-26 142936.png>)
![alt text](<Screenshot 2024-03-26 142951.png>)
![alt text](<Screenshot 2024-03-26 143001.png>)
![alt text](<Screenshot 2024-03-26 144118.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
