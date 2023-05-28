# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

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



## Code:
```
<!DOCTYPE html>
{% load static %}
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>coverpage</title>
    <link rel="stylesheet" href="static/css/cover.css">
    <style>
    main{
    background-color: rgb(58, 54, 54);
    background-image: url('static/images/book.png');
    height: 1000px;
    width:800px;
    margin-left: 500px;
}
    </style>
 </head>
<body>
    <main>
        <h4>EXPERT INSIGHT</h4>
        <hr id="start" color="orange">
        <h1>
            Responsive Web <br>
            Design with <br>
            HTML5 and CSS
        </h1>
        <p>Develop future-proof responsive websites <br>
        using the latest HTML5 and CSS techniques</p>

        
        <p id="edision">THIRD EDISION</p>
        <hr id="aj" color="orange">
        <img src="static/images/ben.png" alt="sdfgh">
        
           <p id="author">Ben Frain</p>
            <p id="packt"> <u> Packt> </u></p>
    
    
    </main>
   
</body>
</html>
```

## Output:
![Screenshot (6)](https://github.com/CHANDRUMANIKANDAN/cover-page-design/assets/118644502/f0f7168f-23bd-464b-be5e-cc8b8a5da06f)


## Result:
Thus the experiment was executed successfully.
