# Ex-06-Book-Cover-Design
### Name: Anbuselvan.S
### Reference No: 23005959

## AIM:
To design a static web site for a book cover page.

## DESIGN STEPS:
### Step 1:
Create a new Django project and app.

### Step 2:
Create a static file directory and mention the changes in settings.

### Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

### Step 4:
Write down the code for book cover using HTML and CSS.

### Step 5:
Add images and other contents using CSS record a screenshot of it.

## CODE:
```
<!DOCTYPE html>
<html>
<head>
    <style>
       .image{
        margin-left: 450px;
        margin-top: 25px;
       }
       .img2{
        filter: brightness(50%);opacity: 95%;
       }
       .h1{
        position: absolute;
        top: 45px;
        left: 470px;
        font-style: italic;
        font-size: large;
        color: azure;
       }
       .line1{
        position: absolute;
        top: 65px;
        left: 460px;
       }
       .para{
        position: absolute;
        top: 100px;
        left: 500px;
        font-size: larger;
        font-style: bold;
        color: cornsilk;
        line-height: 20px;
       }
       .para2{
        position: absolute;
        top: 220px;
        left: 500px;
        font-size: large;
        font-style: italic;
        color: bisque;
        line-height: 15px;
       }
       .line3{
        position: absolute;
        bottom: 90px;
        left: 460px;
       }
       .edition{
        position: absolute;
        bottom: 100px;
        left: 480px;
        font-style: oblique;
        font-size: large;
        color: aqua;
        line-height: 10px;
       }
       .imgaut{
        position: absolute;
        bottom: 100px;
        left: 900px;
       } 
       .name{
        position: absolute;
        bottom: 41px;
        left: 475px;
        font-size: x-large;
        font-style: bold;
        color: aquamarine;
       }
    </style>
</head>
<body>
    <div class="image">
    <div class="img2"> 
    <img src="c:\Users\admin\Downloads\cloud-data-storage-rack-concept-glass-cube-cloudscape-digital-metaverse-server-global-network-business-web-database-backup-computer-private-infrastructure-technology.jpg" width="600px" height="700px">
    </div>
    <div class="h1">
        Expert Insight
    </div>
    <div class="line1">
        <hr width="120px" height="30px" color="red">
    </div>
    <div class="para">
        <h1>ARCHITECTING</h1> 
        <h1>THE CLOUD</h1>
        <hr width="500px" height="50px" color="dark red">
    </div>
    <div class="para2">
        <h2>Design Decisions for </h2>
        <h2>Cloud Computing</h2>
        <h2>Service Models</h2>
    </div>
    <div class="edition">
        <h3>First Edition</h3>
    </div>
    <div class="line3">
        <hr width="597px" height="100px" color="orange">
    </div>
    <div class="imgaut">
        <img src="c:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2023-12-15 114539.png" width="130px" height="130px">
    </div>
    <div class="name">
        <h4><strong>ANBUSELVAN.S</strong></h4>
    </div>
    </div>
    
</body>

</html>
```

## OUTPUT:
![image](https://github.com/anbuselvan1519/Ex-06-Book-Cover-Design/assets/139841744/b8d5ad2c-d4ad-4508-b45f-431f2779da53)

## Result:
Thus the program to develop a website to display the cover page design of a book is done.
