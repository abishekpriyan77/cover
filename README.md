# Ex.06 Book Front Cover Page Design
## Date:6/12/2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
book.html
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FWAD Book Cover</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color:wheat;
        }

        .cover {
            width: 400px;
            height: 600px;
            background: linear-gradient(135deg, #e81a1d,firebrick, #f66478);
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            align-items: center;
            text-align: center;
            padding: 20px;
            color:black;
        }

        .cover-header {
            margin-top: 20px;
        }

        .title {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.2em;
            font-weight: 300;
            margin-bottom: 20px;
        }

        .graphic {
            width: 80%;
            max-width: 250px;
            margin: 30px 0;
        }

        .cover-footer {
            margin-bottom: 20px;
        }

        .author {
            font-size: 1.2em;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .tagline {
            font-size: 1em;
            font-style: italic;
            color: firebrick;
        }

        .line {
            width: 80%;
            height: 2px;
            background: #e0f7fa;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="cover">
        <div class="cover-header">
            <div class="title">A History of Violence </div>
            <div class="subtitle">A History of Violence is a 2005 action thriller film directed by David Cronenberg and written by Abishek priyan. It is an adaptation of the 1997 DC graphic novel</div>
            
        </div>

        <div class="graphic">
            <img src="IMG_20241206_235926.jpg" alt="Code Illustration" style="width: 80%; border-radius: 5px;">
        </div>
        <div class="line"></div>
        <div class="cover-footer">
            <div class="author">Abishek priyan</div>
            <div class="tagline">"Nan Than Da LEO ♌ "</div>
        </div>
    </div>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (189).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
