# Ex.07 Software Product Company Website
## Date:15.12.2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
index.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <style>
        h1 {
            color: blue;
            font-size: 45px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            position: absolute;
            top: 35%;
        }

        body {
            background-color: silver;
            margin: 0;
        }

        .navbar ul {
            list-style-type: none;
            background-color: darkblue;

        }

        .navbar a {
            color: white;
            text-decoration: none;
            padding: 25px;
            display: flex;
            text-align: left;
            position: relative;
            font-size: 20px;
            top: -95px;

        }

        .navbar a:hover {
            background-color: lightblue;
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: white;
            font-family: monospace;
            font-size: 60px;
            background-color: darkblue;
        }

        footer {

            background-color: black;
            height: 30px;
            bottom: 0;
            width: 100%;
            color: white;
            position: absolute;
            text-align: center;

        }

        header {
            background-color: darkblue;
            height: 10vh;
            width: 100%;
            color: white;
        }

        header h2 {
            position: absolute;
            color: white;
            margin-top: 10px;
            margin-left: 10px;
        }

        .first,
        .second,
        .third {
            font-size: 50px;
            margin-left: 2px;
        }

        .second {
            color: rgb(43, 144, 226);
            text-align: center;
        }

        .third {
            text-align: center;
        }
        .first{
            margin-left:5px;
        }
        .search input,
        button {
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color: silver;
        }

        .d {
            position: absolute;
            top: 65%;
            font-size: 20px;
        }

        .search input {
            width: 18%;
            height: 30px;

        }

        .search button,
        .d button {
            color: white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }

        .d button {

            margin-right: 500px;
            padding: 20px 30px 20px 30px;
            border-radius: 30px;
            border-color: none;
        }

        #joinus:hover {
            cursor: pointer;
            color: rgb(5, 20, 15);
            background-color: rgb(215, 249, 250);
        }

        .login form {
            position: absolute;
            right: 100px;
            top: 30%;
            margin: 20px;
            box-sizing: border-box;
            border-color: rgb(105, 62, 7);
            background-color: rgba(25, 23, 20, 0.6);
            padding: 80px 80px 200px 80px;
        }

        .login form button {
            background-color: rgb(22, 165, 222);
            margin-right: 50px;
            color: white;
            padding: 10px 35px 10px 35px;
            font-size: 15px;
            border-radius: 15%;
            width: 60%;
        }

        .login form h3 {
            color: rgb(13, 12, 12);
            position: absolute;
            top: 0%;
            padding: 5px 30px 5px 30px;
            background-color: rgb(248, 250, 250);
            text-align: center;
            margin-left: 18px;


        }

        .login form input {
            height: 35px;
            border: none;
            border-bottom: 2px solid lightblue;
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            font-size: 15px;
            background: transparent;
        }

        .login ::placeholder {
            color: white;
            opacity: 1;
        }

        .login form h4 {
            position: absolute;
            top: 55%;
            color: white;
            margin-left: 25px;
        }

        .login form .Signup {
            position: absolute;
            top: 70%;
            color: white;
            margin-left: 35px;
        }

        .login form .Signup b a {
            text-decoration: none;
            color: lightblue;
            margin-left: 20px;
        }

        .login form h5 {
            position: absolute;
            top: 73%;
            color: white;
            margin-left: 65px;
        }

        .login form .image {
            position: absolute;
            top: 85%;
            margin-left: 40px;
            

        }
        .login form .image i{
            position:relative;
            padding-right: 5px;
        }

        .d p {
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
    </style>
</head>

<body>
    <header>
        <h2>NexTech Innovations</h2>
    </header>
    <nav class="navbar">

        <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="index.html">Home</a></li>
        </ul>
    </nav>
    <div class="search"><input type="text" placeholder="Enter to Search">
        <button>Search</button>
    </div>
    <h1>
        <div class="first">A Software Journey To</div>
        <div class="second"> Empower<br> </div>
        <div class="third">The World</div>
    </h1>
    <div class="d">
        <p> &nbsp;"Software is the wizard behind the screen,
            turning ideas into actions with its magical code spells."</p>
        <button id="joinus">Join Us</button>
    </div>
    <div class="login">
        <form>
            <h3>Login Here</h3>
            <input type="text" placeholder="Username or Email"><br><br>
            <input type="password" placeholder="Password"><br><br><br>
            <button>Login</button>
            <h4>Don't have an account</h4><br>
            <div class="Signup"><b><a href="">Sign up</a></b> here</div>
            <h5>Login with</h5>
            <div class="image">
                <i class="fa fa-instagram" style="color:white;font-size: 25px;"></i>
                <i class="fa fa-facebook" style="color:white;font-size: 25px;"></i>
                <i class="fa fa-twitter" style="color:white;font-size: 25px;"></i>
                <i class="fa fa-google" style="color:white;font-size: 25px;"></i>
            </div>
        </form>
    </div>
    <footer>
        Designed and Developed by Rahul V&nbsp;&copy; 2023
    </footer>

</body>

</html>

people.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: blue;
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:silver;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:darkblue;
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:darkblue;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        text-align: center;
        
        }
        header
        {
        background-color:darkblue;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:white;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .small
        {
           width:200px;
           height:200px;
           margin:10px;
        }
        .border{
        border-width:5px;
        border-color:lightblue;
        border-style:solid;
        border-radius:50%;
        }
        .cirpic{
            position:absolute;
            top:35%;
            margin-left: 40px;
        }
        .text{
            position:absolute;
            top:55%;
            margin-left: 40px;
            font-size: 20px;
        }
        .text2{
            position:absolute;
            top:60%;
            margin-left:58px;
        }
    
    </style>
</head>
<body>
    <header>
        <h2>NexTech Innovations</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="index.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
        <div class="cirpic">
            <img class="small border" src="r.jpg" width="500px">
            <img class="small border" src="arjun.jpg" width="500px" >
            <img class="small border" src="vikram.jpg" width="500px">
            <img class="small border" src="karthi.jpg" width="500px" >
            <img class="small border" src="amar.jpg" width="500px">
            <img class="small border" src="Vijay-Sethupathi.jpg" width="500px" >
        </div>
        <div class ="text">
            <table cellpadding="87">
                <tr div class="head">
                    <th>Rahul</th>
                    <th>Arjun</th>
                    <th>Vikram</th>
                    <th>Karthi</th>
                    <th>Amar</th>
                    <th>Vijay S</th>
                </tr>
            </table>
        </div>
        <div class="text2">
            <table cellpadding="83">
                <tr>
                    <td>CEO</td>
                    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CEO<br>Co-Founder</td>
                    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CTO<br>Co-Founder</td>
                    <td>Director</td>
                    <td>Asst.Director</td>
                    <td>Dy.Director</td>
                </tr>
            </table>
        </div>
      
            <footer>
                Designed and Developed by  Rahul V&nbsp;&copy; 2023
                </footer>
               
</body>
</html>

products.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: blue;
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:silver;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:darkblue;
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:darkblue;
        }
        footer{
        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        text-align: center;
        
        }
        header
        {
        background-color:darkblue;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:white;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 8px;
            font-size: 18px;
            border-color:silver;
        }
        .contain {
                position: absolute;
                top:11%;
                width:1180px;
                height:710px;
                margin-left: 5px;
                background-color:lightblue;
                }
                .contain p b{
                    font-size: 30px;
                    padding-left: 45px;
                }
                .contain p{
                    font-size: 20px;
                    padding-left: 15px;
                    padding:5px 20px 0px 15px ;
                }
                .contain img{
                   margin-top: 10px;
                   padding-left: 10px;
                   padding:10px 20px 0px 10px;
                }
        </style>
</head>
<body>
    <header>
        <h2>NexTech Innovations</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="index.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
            <div class="contain">
                <table >
                    <tr>
                        <td><img src="unity.jpg" height="200px" width="200px">
                            <p><b>Unity</b><br>
                                &nbsp;&nbsp;&nbsp;Game Development<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Platform
                        </p></td>
                        <td><img src="sale.png" height="200px" width="200px"><br>
                            <p><b>Salesforce</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cloud-based<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;CRM
                        </p></td>
                        <td><img src="wp.jpg" height="200px" width="200px"><br>
                            <p><b>WordPress</b><br>
                                &nbsp;&nbsp;&nbsp;Content Management <br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  System
                        </p></td>
                        <td><img src="trello.png" height="200px" width="200px"><br>
                            <p><b>Trello</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;Project Management<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Tool
                        </p></td>
                        <td><img src="dropbox.png" height="200px" width="200px"><br>
                            <p><b>Dropbox</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cloud Storage<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Device
                        </p></td>  
                    </tr>
                    <tr>
                        <td><img src="turbo.png" height="200px" width="200px">
                            <p><b>TurboTax</b><br>
                                &nbsp;&nbsp;&nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tax Preparation<br>
                                &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Software
                        </p></td>
                        <td><img src="eclipse.png" height="200px" width="200px"><br>
                            <p><b>Eclipse</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;IDE for Software<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;development
                        </p></td>
                        <td><img src="gra.png" height="200px" width="200px"><br>
                            <p><b>Grammarly</b><br>
                                &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;Writing Assistant<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; Tool
                        </p></td>
                        <td><img src="slack.png" height="200px" width="200px"><br>
                            <p><b>&nbsp;&nbsp;Slack</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;Team Collaboration<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;Tool
                        </p></td>
                        <td><img src="virtualbox-logo-1.jpg" height="200px" width="200px"><br>
                            <p><b>VirtualBox</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Virutualization<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Software
                        </p></td>  

                    </tr>
                </table>
               
            </div>
            <footer>
                Designed and Developed by Rahul V&nbsp;&copy; 2023
                </footer>
               
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: blue;
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:silver;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:darkblue;
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:darkblue;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        text-align: center;

        
        }
        header
        {
        background-color:darkblue;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:white;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .line{
            position: absolute;
            top:43%;
        color:  darkblue;
            width:100%;
            size:5px;
        }
        .coform {
            background-color: white;
            top:43%;
        }
        .coform form{
            position: absolute;
            top:45%;
        }
        .coform form h3{
            font-size:30px;
        }
        .coform form input{
            margin-left: 10px;
            width:500px;
            height:25px;
        }
        .coform form textarea{
            margin-left: 10px;
        }
        .coform form button{
            position: absolute;
            background-color:  rgb(22, 165, 222);
            color:white;
            border-radius: 20%;
            margin-left: 10px;
        }
        #submit{
            left:0px;
            width:20%;
        }
        .vl{
            position:absolute;
            border-left: 3px solid darkblue;
            height: 450px;
            margin-left: 800px;
            top:44%;
        }
        #ci{
            font-size: 30px;
            margin-left: 40px;
        }
        .info{
            position:absolute;
            top:44.3%;
            font-size: 25px;
            background-color: white;
            padding:70px 250px 35px 147px ;
            margin-left: 800px;
        }
        .coform form{
            background-color: white;
            top:44.3%;
            margin-left: 0px;
            padding:0px 282px 55px 0px;
        }
    </style>
    </head>
    <body>
        <header>
            <h2>NexTech Innovations</h2>
            </header>
            <nav class="navbar">
            
            <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="index.html">Home</a></li>
            </ul>
            </nav>
            <div class="search"><input type="text" placeholder="Enter to Search">
                <button>Search</button></div>
                <div class="line">
                    <hr color="darkblue">
            </div>
            <div class="coform">
            <form>
              <h3>&nbsp;Contact Us</h3>
              <input type="text" placeholder="Your Name"><br><br>
              <input type="text" placeholder="Your Email"><br><br>
              <textarea rows="12" cols="66" >Your Message
              </textarea><br>
              <button id="submit">Submit</button>
            </form>
        </div>
        <div class="info">
            <h3 id="ci" >Contact Information</h3><br>
            <b>Address: </b>2,Ayanavaram,Chennai<br><br>
            <b>Email: </b>nextech@gmail.com<br><br>
            <b>Phone: </b>044-0327
        </div>
        <div class="vl"></div>
    </div>
                <footer>
                   Designed and Developed by Rahul V&nbsp;&copy; 2023
                    </footer>
                   
    </body>
    </html>
```

## OUTPUT:
![Alt text](<Screenshot (47).png>)
![Alt text](<Screenshot (48).png>)
![Alt text](<Screenshot (49).png>)
![Alt text](<Screenshot (50).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
