# Ex.07 Software Product Company Website
## Date:

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
Home.html

<html>
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width-device-widht' initial-cale-1.0" />
        <title> Web World  </title>
        <style>
            *{
                margin: 0;
                padding: 10;
                font: Arial, Helvetica, sans-serif;
               
             }
            nav
             {
                display: flex;
                color: rgb(255, 255, 255);
                justify-content: space-between;
                align-items: center;
                padding: 0 20px;
                font-weight: bolder;
                font-size: xx-large;
                font: comic small-caps;
             }  
             body{
                background-image:url("outrun-neon-dark-background-purple-3840x2160-4523.jpg");  
                background-size: cover;
             }  
            nav ul
            {
                display: flex;
            }
            nav ul {
                list-style-type: none;
            }
            nav ul li{
                margin: 0 10px;
                padding: 10px 20px
            } 
            nav ul li a{
                text-decoration: none;
                color: darkgreen;
                font-size:larges;
                cursor: pointer;
                
            }
            nav ul li ::before,
             nav ul li ::after

            {
                position: absolute;
                content: '';
                width: 0%;
                height: 2px;
                background-color: #fff;
                transition: 0.3s all ease-in-out;

            }
            ul li ::before{
                top:0;
                left:0;
            }
            ul li ::after{
                bottom:0;
                right: 0;
            }
            nav ul li a:hover ::before {
                right: 0;
                width: 100%;
                left: auto;
                background-color:  #5607f4a7;

            }
            nav ul li a:hover ::after {
            right:auto;
            left: 0;
            width: 100%;
            background-color: #5607f4a7;
            }
            nav ul li a:hover {
              background-color:   #5607f4a7;   
            }


            button {
                padding: 5px 10px;
                border-radius: 0px;
               color: blue;
               font-weight: bolder;
            }
            nav ul li a:hover {
                color:yellow;
                transition: 1s all;
                cursor: pointer;
                border-radius: 30px;

            }
            span{
                color:blueviolet;
            }
            .span {
                color: Aqua;
            }
            .content
            {
            top: 150px;
             right: 75px;
             text-align: left;
             font-size: xx-large;
             font: Arial;
             color: white;

            }
            nav .subtitle  {
                top: 0px;
                right: 5px;
                color: red;
                font-size: small;

            }
                .text p {
                color: white;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: -30px;
                word-spacing: 2px;
                letter-spacing: 1px;

            }   
            .login {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
        
            }
            .footer {
                background-color: #6fa1f8;
                margin-top: auto;
align-items: bottom;

            }
        </style>
    </head>
    <body>
            <nav>
                <h2>WEB <span>WORLD</span></h2>
            
                <ul> 
                    <li><a href="Home.html">HOME</a></li>
                    <li><a href="people.html">ABOUT</a></li>
                    <li><a href="product.html">SERVICE</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                    

                </ul>

                <div class="search">
                <form>
                    <input type="text" size="15"  placeholder="Search...">
                    <button type="Submit">Search</button>
                </form>
                </div>
            </nav>
            <br>
            <br>
            <div class="content">
                <div class="text">
                    
                  
                  <div class="title">  <p><h1>WEB DEVELOPMENT
                    <br> COMPANY </h1>
                    </p>
                    </div>
                    <div>
                      <h5> We develop innovative WEB Site and Apps</h5>
                    
                    </div>
                </div>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
                <br>
               
            
            
            </div>
</body>
</html>


Product.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: blac;
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
                background-image:url("outrun-neon-dark-background-purple-3840x2160-4523.jpg");  
                background-size: cover;
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
        background-color:black;
        }
        footer{
        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:black;
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
        .contain{
                position: absolute;
                top:12%;
                width:1260px;
                height:770px;
                margin-left: 90px;
               
                background-color:lightgrey;
                font-size: larger;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                
                
                }
                .contain p b{
                    font-size: 30px;
                    padding-left: 45px;
                }
                .contain p{
                    font-size: 18px;
                    padding-left: 10px;
                    padding:5px 20px 0px 15px ;
                    
                }
                .contain img{
                   margin-top: 10px;
                   padding-left: 10px;
                   padding:20px 20px 0px 20px;
                }
                .m{
                    text-align: center;
                    font-size: large;
                }
                span{
                    color: blueviolet;
                }


    </style>
</head>
<body>
    <header>
        <h2>WEB <span>
            WORLD
        </span></h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="Contact.html">Contact</a></li>
        <li><a href="product.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="Home.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
            <div class="contain">
                <table >
                    <tr>
                        <td><img src="amazon-logo.png" height="200px" width="200px">
                            <p><b>web<br>&nbsp;&nbsp; Shoppping </b><br>
                                &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>
                               
                
                        </p></td>
                        <td><img src="att-logo.png" height="200px" width="200px"><br>
                            <p><b>&nbsp;&nbsp;Logo-maker&nbsp;</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
                                
                        </p></td>
                        <td><img src="louis-vuitton-logo.png" height="200px" width="200px"><br>
                            <p><b>louis-vuitton <br>&nbsp;&nbsp;</b><br>
                                &nbsp;&nbsp;&nbsp; 
                        
                        </p></td>
                        <td><img src="apple-logo.png" height="200px" width="200px"><br>
                            <p><b>electronics gadget</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>
                                
                        </p></td>
                        <td><img src="facebook-logo.png" height="200px" width="200px"><br>
                            <p><b>Social Media</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Learning<br>
                                
                        </p></td>  
                    </tr>
                    <tr>
                        <td><img src="google-logo.png" height="200px" width="200px">
                            <p><b>&nbsp;&nbsp;&nbsp;Google&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</b><br>
                                &nbsp;&nbsp;&nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Fitness<br>
                
                        </p></td>
                        <td><img src="mercedes-benz-logo.png" height="200px" width="200px"><br>
                            <p><b>&nbsp;&nbsp;Luxury car</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>
                               
                        </p></td>
                        <td><img src="mcdonalds-logo.png" height="200px" width="200px"><br>
                            <p><b>&nbsp;&nbsp;Mc Donalds</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
                        </p></td>
                        <td><img src="samsung-logo.png" height="200px" width="200px"><br>
                            <p><b>Home Application</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>
                        
                        </p></td>
                        <td><img src="starbucks-logo.png" height="200px" width="200px"><br>
                            <p><b>&nbsp;&nbsp;starbucks</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>
                                
                        </p></td>  

                    </tr>
                </table>
            </div>
            <footer class="m">
                Designed and Developed by RajaGopal V &copy; 2023
                </footer>
               
</body>
</html>


People.html

<html>
                    <head>
                        <meta name="viewport" content="width=device-width, initial-scale=1.0">
                        <title> people page </title>
                        <style type="text/css">
                            * {
                                margin: 0;
                                padding: 0;
                                font-family: Arial, Helvetica, sans-serif;
                            }
                            .banner {
                                width: 100%;
                                height: 100vh;
                                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(outrun-neon-dark-background-purple-3840x2160-4523.jpg);
                                background-size: cover;
                                background-position: center;
                            }
                            .navbar {
                                width: 85%;
                                margin: auto;
                                padding: 35px 0;
                                display: flex;
                                align-items: center;
                                justify-content: space-between;
                            }
                            .bg-people {
                                border: 1px;
                                padding: 10px;
                                color: white;
                                background-color: #6fa1f8;
                                border-radius: 30px;
                            }
                            .logo {
                                color: #6fa1f8;
                                font-size: 40px;
                                font-weight: 700;
                                letter-spacing: 3px;
                            }
                            span {
                                color: white;
                            }
                            form {
                                width: 300px;
                                height: 40px;
                                display: flex;
                                background: rgba(255, 255, 255, 0.2);
                                padding: 1px 1px;
                                font-size: 15px;
                                border-radius: 10px;
                                backdrop-filter: blur(4px) saturate(180%);
                            }
                            form input {
                                background: transparent;
                                flex: 1;
                                border: 0;
                                outline: none;
                                padding: 12px 20px;
                                font-size: 15px;
                                color: white;
                            } 
                            ::placeholder {
                                color: white;
                            }
                            form button {
                                border: 0;
                                outline: none;
                                padding: 5px 20px;
                                color: white;
                                border-radius: 10px;
                                background: #6fa1f8;
                                cursor: pointer;
                            }
                            .navbar li {
                                list-style: none;
                                display: inline-block;
                                margin: 0 20px;
                                position: relative;
                            }
                            .navbar li a {
                                text-decoration: none;
                                color: white;
                                text-transform: uppercase;
                            }
                            .navbar li:hover {
                                border: 1px;
                                padding: 10px;
                                color: white;
                                background-color: #6fa1f8;
                                transition: 0.5s; 
                                cursor: pointer;
                                border-radius: 30px;
                            }
                            .image {
                                position: relative;
                                border: 0;
                                top: 70px;
                                background: transparent;
                            }
                            .image table {
                                border: 0;
                                color: white;
                                position: relative;
                                left: 150px;
                            }
                            .image table img {
                                height: 140px;
                                width: 140px;
                                border: 2px solid white;
                                padding: 5px;
                                border-radius: 50%;
                            }
                            .image table td {
                                color: #6fa1f8;
                            }
                            footer {
                                background-color: #6fa1f8;
                                margin-top: auto;
                            }
                        </style>
                    </head>
                <body>
                    <div class="banner">
                        <br>
                        <div class="navbar">
                            <h1 class="logo"> <span>WEB</span> WORLD</h1>
                            <ul>
                                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                                <li><a href="product.html"> Products </a></li>
                                <li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People </a></li>
                                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
                            </ul>
                            <form action="" method="get">
                                <input type="text" placeholder="Enter to Search">
                                <button type="submit"> Search </button>
                            </form>
                        </div>
                        <div class="image">
                            <table cellspacing="20"> 
                                <tr align="center">
                                    <td> <img src="My photo.jpg"> </td>
                                    <td> <img src="Shichan.jpg"> </td>
                                    <td> <img src="Thalapathy Vijay.jpeg"> </td>
                                    <td> <img src="str.jpeg"> </td>
                                    <td> <img src="Suriya.jpeg"> </td>
                                    <td> <img src="na.jpeg"> </td>
                                </tr>
                                <tr align="center">
                                    <th> RAJA</th>
                                    <th> SURENDAR </th>
                                    <th>NIRANJAN</th>
                                    <th> ROHITH </th>
                                    <th> SHYAM </th>
                                    <th> Ramos </th>
                                </tr>
                                <tr align="center">
                                    <td> CEO </td>
                                    <td> CEO, Co-Founder </td>
                                    <td> CTO, Co-Founder </td>
                                    <td> Director </td>
                                    <td> Asst. Director </td>
                                    <td> Dy. Director </td>
                                </tr>
                            </table>
                        </div>
                    </div>
                    <footer>
                        <center> Designed and Developed by RajaGopal (23002920) </center>
                    </footer>
                </body>
                </html>
                
               
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
        color: black;
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
                background-image:url("outrun-neon-dark-background-purple-3840x2160-4523.jpg");  
                background-size: cover;
             }  
        .navbar ul{
        list-style-type:none;
        background-color:black;
        
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
        nav ul li ::before,
             nav ul li ::after

            {
                position: absolute;
                content: '';
                width: 0%;
                height: 2px;
                background-color: #fff;
                transition: 0.3s all ease-in-out;

            }
            ul li ::before{
                top:0;
                left:0;
            }
            ul li ::after{
                bottom:0;
                right: 0;
            }
            nav ul li a:hover ::before {
                right: 0;
                width: 100%;
                left: auto;
                background-color:  #5607f4a7;

            }
            nav ul li a:hover ::after {
            right:auto;
            left: 0;
            width: 100%;
            background-color: #5607f4a7;
            }
            nav ul li a:hover {
              background-color:   #5607f4a7;   
            }


        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:black;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:black;
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
        color:  black;
            width:100%;
            size:5px;
        }
        .coform {
            background-color: wheat;
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
            color:black;
            border-radius: 20%;
            margin-left: 10px;
        }
        
        #submit{
            left: 50px;
            width: fit-content;
        }
        .vl{
            position:absolute;
            border-left: 3px solid black;
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
            top:44.2%;
            font-size: 25px;
            background-color: black;
            padding:70px 250px 95px 147px ;
            margin-left: 840px;
            color: white;
            border: 4px;
            border-color: beige;
            border-style: solid;
        }
        .coform form{
            background-color: black;
            color: aliceblue;
            top:44.3%;
            margin-left: 20px;
            padding:0px 282px 50px 0px;
            border: 4px;
            border-color: aliceblue;
            border-style: solid;
        }
        .u{
            text-align: center;
            font-size: larger;
        }
        span 
        {
            color: blueviolet;
        }
    </style>
    </head>
    <body>
        <header>
            <h2>WEB <span>WORLD</span></h2>
            </header>
            <nav class="navbar">
            
            <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="Home.html">Home</a></li>
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
              <textarea rows="10" cols="50" >Your Message
              </textarea><br>
              <button id="submit">Submit</button>
            </form>
        </div>
        <div class="info">
            <h3 id="ci" >Contact Information</h3><br>
            <b>Address: </b>143, Nallathambi street,pammal,<ch-75></ch-75><br><br>
            <b>Email: </b>Webworld@gmail.com<br><br>
            <b>Phone: </b>044-123456879
        </div>
        <div class="vl"></div>
    </div>
                <footer class="u">
                    Designed and Developed by RajaGopal V &copy; 2023
                    </footer>
                   
    </body>
    </html>


```

## OUTPUT:

![Screenshot (55)](https://github.com/arhamshajahan/softweb/assets/127313881/f74d7b3a-1b3e-4de1-85b0-f977a70c1901)
![Screenshot (56)](https://github.com/arhamshajahan/softweb/assets/127313881/4604ee1b-34ed-452b-829d-75f5e57c841c)
![Screenshot (57)](https://github.com/arhamshajahan/softweb/assets/127313881/ab2f9470-ff8b-4a38-b678-3a756963820b)
![Screenshot (58)](https://github.com/arhamshajahan/softweb/assets/127313881/ae3143ea-04e3-4382-b653-d65b7e49f281)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
