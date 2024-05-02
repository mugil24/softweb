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
## home.html 
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Home </title>
        <style type="text/css"> 
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image:url(bg.jpg);
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
            .logo {
                color: #295db6;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(2, 0, 0);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(15, 18, 18, 0.434);
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
                color: rgb(167, 15, 15);
            } 
            ::placeholder {
                color: rgb(5, 0, 0);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(76, 46, 127);
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
                color: rgb(27, 138, 12);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(213, 233, 41);
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {  
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: rgb(3, 11, 1);
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: rgb(236, 14, 14);
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
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
                background-color: rgb(31, 128, 180);
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color: #ce181b;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">H<span>ack</span>B<span>ox</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2>  Networking Company </h2>
                <br>
                <p> Welcome to HackBox, HACKBOX is a startup based on IT,networking, Cloud Computing, Web Designing Digital Marketing & SEO training and Development.. </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by vaanmugil vs 212221040174 </center>
    </footer>
</body>
</html>



## person.html
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
                background-image:url(bg.jpg);
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
                color: rgb(47, 11, 43);
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo {
                color: #1b49d2;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(0, 5, 8);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(16, 4, 4, 0.348);
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
                color: rgb(0, 0, 0);
            } 
            ::placeholder {
                color: rgb(12, 13, 1);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgba(4, 6, 0, 0.358);
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
                color: rgb(22, 190, 19);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(214, 177, 14);
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
                color: rgb(27, 212, 122);
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid rgb(182, 15, 182);
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: #0b0105;
            }
            footer {
                background-color: #cf5656;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">H<span>ack</span>B<span>ox</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="person.html" class="bg-people"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="ceo.jpg"></td>
                    <td> <img src="founder.jpg "></td>
                    <td> <img src="dir.jpg "></td>
                    <td> <img src="ass.dir.jpg"></td>
                    <td> <img src="secr.jpg"></td>
                </tr>
                <tr align="center">
                    <th> Michael Green</th>
                    <th> Kizzy Charles-Guzman </th>
                    <th>  nithin kamath </th>
                    <th> LEWIS HAMILTON </th>
                    <th> Leena Nair </th>                    
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                    <td> Secretary </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by vaanmugil vs 212221040174</center>
    </footer>
</body>
</html>
## PRODUCT.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
<title> Product Page </title>
<style type="text/css">
    * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
    }
    .banner {
        width: 100%;
        height: 100vh;
        background-image:url(bg.jpg);
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
    .bg-product {
        border: 1px;
        padding: 10px;
        color: rgb(34, 114, 211);
        background-color: #6fa1f8;
        border-radius: 30px;
    }
    .logo {
        color: #1963cb;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
    }
    span {
        color: rgb(14, 10, 1);
    }
    form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(0, 2, 3, 0.332);
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
        color: rgb(40, 185, 27);
    } 
    ::placeholder {
        color: rgb(17, 11, 2);
    }
    form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: rgb(2, 15, 5);
        border-radius: 10px;
        background: #07a0dd;
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
        color: rgb(38, 2, 66);
        text-transform: uppercase;
    }
    .navbar li:hover {
        border: 1px;
        padding: 10px;
        color: rgb(213, 213, 5);
        background-color: #20cf43;
        transition: 0.5s; 
        cursor: pointer;
        border-radius: 30px;
    }
    .container {
        background: transparent;
        padding: 10px 5%;
        padding-bottom: 100px;
    }
    .container .box-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
        gap: 20px;
    }
    .container .box-container .box {
        color: rgb(33, 166, 51);
        box-shadow: 0 5px 10px rgba(0,0,0,.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid rgb(172, 185, 26);
        padding: 30px 20px;
    }
    .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
    }
    .container .box-container .box h2 {
        color: #6fa1f8;
        font-size: large;
        padding: 10px 0;
    }
    .container .box-container .box p {
        color: rgb(90, 201, 34);
        font-size: small;
        line-height: 1.5;
    }
    footer {
        background-color: #05979c;
        margin-top: auto;
    }
</style>
</head>
<body>
<div class="banner">
<br>
<div class="navbar">
    <h1 class="logo">H<span>ack</span>B<span>ox</span></h1>
    <ul>
        <li><a href=home.html"> Home </a></li>
        <li><a href="product.html" class="bg-product"> Products </a></li>
        <li><a href="person.html"> person </a></li>
        <li><a href="contact.html"> Contact </a></li>
    </ul>
    <form action="" method="get">
        <input type="text" placeholder="Enter to Search">
        <button type="submit"> Search </button>
    </form>
</div>
<center>
    <h1 > <font color = "black"> OUR PROJECTS </font> </h1>
<img src="prod.jpg" height="500" width="400">
</center>
</div>
<footer>
<center> Designed and Developed by VAANMUGIL VS 212221040174 </center>
</footer>
</body>
</html>
## contact.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Contact Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url(bg.jpg);
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
            .bg-contact {
                border: 1px;
                padding: 10px;
                color: rgb(20, 8, 83);
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
                color: rgb(13, 21, 4);
            }
            .navbar form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(5, 4, 4, 0.334);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            .navbar form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(0, 0, 0);
            } 
            ::placeholder {
                color: rgb(59, 52, 5);
            }
            .navbar form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(8, 1, 7);
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
                color: rgba(2, 246, 51, 0.911);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(35, 205, 16);
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid rgb(12, 164, 40);
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid #09be7e;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: rgb(2, 1, 19);
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid rgb(66, 205, 20);
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: rgb(20, 181, 68);
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: rgb(42, 235, 16);
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid rgb(36, 179, 96);
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: white;
                border-radius: 30px;
                background: #a28f85;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: rgb(10, 10, 10);
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: rgb(38, 7, 87);
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color: #010710;
                font-size: 20px;
            }
            footer {
                background-color: #e21010;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">H<span>ack</span>B<span>ox</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html" class="bg-contact"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="40" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Info </h2>
                <p> <span>Address</span> :124, vandluar, kelambakam, Chennai, Tamil Nadu-600086</p>
                <p> <span>Email</span> : vaanmugil24@gmail.com </p>
                <p> <span>Phone</span> : 7200867225</p>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by VAANMUGIL V S 212221040174</center>
    </footer>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2024-04-30 144532.png>)
![alt text](<Screenshot 2024-04-30 144548.png>)
![alt text](<Screenshot 2024-04-30 144607.png>)
![alt text](<Screenshot 2024-04-30 144621.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
