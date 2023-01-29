# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create a new folder and clone the git repository.

### Step 2:
Create a new project using command "django-admin startproject myproj" and change directory to it.

### Step 3:
Change the necessary details in the settings.py.

### Step 4:
Create new folder static in myproj.In static,create new folder html.In html,create new file cover.html.

### Step 5:
Write the program in cover.html and run the server.

### Step 6:
Publish the website in the url santhosh.student.saveetha.in:8000.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color: goldenrod;
            margin-left: auto;
            margin-right: auto ;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('images/BookCover1.jpeg');
            background-size: cover;
        }
        .insight{
            color:goldenrod;
        }
        .hrstyle{
            width: 100px;
        }

        .author{
            color: white;
            display: inline;
            position: relative;
            color: goldenrod;
            top:190px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;

        }
        .id{
            width: 400px;
            position: relative;
            top:180px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;

        }
        .ed{
            color:green;
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top:85px;

        }
        .subtitle{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: large;
            position: relative;
            top: 40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover</title>
        </head>
        <body>
            <div class="bookpage">
                <div class="insight">
                    SEC INSIGHT
                </div>
                <div class="hrstyle">
                    <hr style="color: goldenrod;">
                </div>
                <div class="booktitle">
                    <h1> Responsive Web Design with HTML5 and CSS </h1></div>
                <div class="subtitle">
                    Develop future-proof responsive websites using the latest HTML5 and CSS techniques
                </div>
                <div class="mypic">
                    <img src="images/BookPhoto1.png" width="127" height="155" alt="">
                </div>
                <div class="id">
                    <hr style="color:gold;">
                </div>
                <div class="author">
                    <p><b>Santhosh U</b></p>
                </div>
                <div class="pub">
                    SEC
                </div>
                <div class="ed">
                    <b>Seventh Edition</b>
                </div>
            </div> 
        </body> 
</html>
```

## Output:
![CoverPageOutput](https://user-images.githubusercontent.com/119477975/215324916-57da3f3a-6a68-41f8-9c55-111f417521d2.png)

![CoverPageValidator](https://user-images.githubusercontent.com/119477975/215324922-157ac9d1-cd53-402b-a24f-68be71c29256.png)


## Result:
A website to display Book Cover Page design is executed successfully
