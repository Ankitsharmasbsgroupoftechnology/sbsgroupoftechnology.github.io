<!DOCTYPE html>
<html>
<head>
    <title>SBS Group</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
    <script src="https://unpkg.com/react@17/umd/react.development.js" crossorigin></script>
    <script src="https://unpkg.com/react-dom@17/umd/react-dom.development.js" crossorigin></script>
    <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">
    <style>
 * {box-sizing: border-box;}
  body {
 margin: 0;
 font-family: Arial, Helvetica, sans-serif;
 }
  .header{
      overflow: hidden;
      background-color: pink;
      padding: 20px 10px;
  } 
  .header a{
      float: left;
      color: black;
      text-align: center;
      padding: 6px;
      text-decoration: none;
      font-size: 18px;
      line-height: 25px;
      border-radius: 4px;
  }
  .header a.logo {
      font-size: 20px;
      font-weight: bold;
  }
 .header a.active {
     background-color: dodgerblue;
     color: white;
 }
 .header-right {
     float: right;
 }
 @media screen and (max-width: 500px){
     .header a {
         float: none;
         display: block;
         text-align: left;
     }
     .header-right {
      float: none;
     }
 }
 .img-circle {
     border-radius: 50%;
 }
 body,html {
     height: 100%;
     margin: 0;
 }

 .technology {
     margin: 0px;
     padding: 0px;
     border: 1px solid #ddd;
  border-radius: 4px;
  padding: 5px;
  width: 250px;
  top: 30px;
 }
 .top-right {
     position: absolute;
     top: 70px;
     right: 10px;
 }
 strong{
     font-size: 230px;
     color:whitesmoke;
     text-shadow: 12px 12px black;
 }
 h1 {
     font-size: 50px;
     color: white;
     text-shadow: 5px 5px black;
     font-family: 'Orbitron', sans-serif;
 }
 
 .bg {
     background-image: url("https://cdn.pixabay.com/photo/2020/04/12/20/37/abstract-5035778_960_720.jpg");
     height: 85%;
     background-position: center;
     background-repeat: no-repeat;
     background-size: cover;
     border-radius: 4px;
     padding: 5px;
     background-color:blueviolet;
     background-attachment: fixed;
     width: 100%;
 }
 p {
     font-family: 'Dancing Script', cursive;
     font-size: 40px;
 }
 li {
    font-family: 'Dancing Script', cursive;
     font-size: 40px; 
 }
 #AboutUs {
  background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX3cYZ3O7sXo9qzlQrU0COqd1hqbvIKrzm0g&usqp=CAU");
 height: 100%;
 background-size: cover;
 background-repeat: no-repeat;
 background-attachment: scroll;
 }
 
 
 form{
     font-family: Arial, Helvetica, sans-serif;
 }
 *{
     box-sizing: border-box;
 }
 input[type=text], select, textarea {
     width: 100%;
     padding: 12px;
     border: 1px solid black;
     margin-top: 6px;
     margin-bottom: 16px;
     resize: vertical;
 }
 input[type=submit] {
     background-color: blue;
     color: whitesmoke;
     padding: 12px 20px;
     border: none;
     cursor: pointer;
 }
 input[type=submit]:hover {
  background-color: black;
 }
 .container{
     border-radius: 5px;
     padding: 0px;
     background-color: grey;
 }
 .column{
     float: left;
     width: 50%;
     margin-top: 6px;
     padding: 20px;
 }
 .row:after{
     content: "";
     display: table;
     clear: both;
 }
 
    </style>
</head>
<body>
     <div class="header">
    <a href="#default" class="logo"><img src="https://www.crushpixel.com/big-static13/preview4/creative-idea-concept-light-bulb-1194209.jpg" height="35px" width="35px" class="img-circle" > SBS Group of Technology</a>
<div class="header-right">
    <a class="active" href="#home"><span class="glyphicon glyphicon-home"></span>Home</a>
    <a href="#AboutUs"><span class="glyphicon glyphicon-user"></span>About Us</a>
    <a href="#contact"><span class="glyphicon glyphicon-envelope"></span>Contact Us</a>
    <a href="file:///C:/Users/Ankit%20Sharma/Documents/GitHub/sbsgroupoftechnology.github.io/SBS%20Technology%20Store.html"><span class="glyphicon glyphicon-shopping-cart" ></span>Technology Store</a>
    <a href="file:///C:/Users/Ankit%20Sharma/Documents/GitHub/sbsgroupoftechnology.github.io/Login.html"><span class="glyphicon glyphicon-log-in"></span>Login</a>
    <a href="file:///C:/Users/Ankit%20Sharma/Documents/GitHub/sbsgroupoftechnology.github.io/Sign%20Up.html"><span class="glyphicon glyphicon-list-alt"></span>Register</a>
</div>
</div>
<div class="bg">
     <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQtSV0SsZ4Ez3mWTylZ6riuLbwRUbJYAUdD4A&usqp=CAU"align="left" class="technology" height="200px" width="250px">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTmI5TEKIIMlBTVoQYZXPgeKQub2QkY39B2PQ&usqp=CAU"align = "left" class="technology" height="200px" width="250px"><br><br><br><br><br><br><br><br><br><br><br>
      <img src="https://www.jonesday.com/-/media/files/publications/2019/09/when-innovation-invents/when_innovation_invents_commentary_social.jpg" height="200px" width="250px" align="left" class="technology">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT5JcE1UNDc3ttMitkzH8iqS6KGMRAPxHBmcg&usqp=CAU" class="technology" height="200px" width="250px">
     <div class="top-right">
         
        <h1> <strong> SBS</strong><br> Group of Technology</h1>
     </div>
    </div>

    <div id="AboutUs">
<p>
    Hello Guys we are thankful to you all that you visit to our site. All you have eager to know about our company. 
    So, As per the name of our company SBS Group of Technology. It is the Site in which We do three works:
    <ol>
        <li><p>We tell about all the Information to the people about Technology and also the new updates comes in Today's Technology.</p></li>
        <li><p>We train the people that how to use latest technology by the help of our Youtube Channel Name "Technical Specialist".</p></li>
        <li><p>We try to make new technology which are advanced, eco-friendly and affordable. <br>We sell all the types of technology at reasonable price.</p></li> 
    </ol>

    </p>
  
</div>

<div id="contact">
    
<div class="container">
    <div style="text-align:center">
    <h2>Contact Us</h2>
    Leave a message for us.
    </div>
    <div class="row">
        <div class="column">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTaYVTFjGKPbqyFR0tCZEiIDsCfKlcZ8eOk1Q&usqp=CAU" style="width: 100%;">

        </div>
        <div class="column">
            <form action="c.js">
                <label for="fname">First Name</label>
                <input type="text" id="fname" name="first name" placeholder="Your name...">
                <label for="lname">Last Name</label>
                <input type="text" id="lname" name="last name" placeholder="Your last name...">
                <label for="Country">Country</label>
                <select id="country" name="country">
                    <option value="India">India</option>
                    <option value="India">America</option>
                    <option value="India">China</option>
                    <option value="India">England</option>
                    <option value="India">Australia</option>
                    <option value="India">Japan</option>
                    <option value="India">Hong Kong</option>
                    <option value="India">Bangladesh</option>
                    <option value="India">Nepal</option>


                </select>
                <label for="Subject">Your Message</label>
                <textarea id="subject" name="subject" placeholder="Write something.." style="height:170px"></textarea>
        <input type="submit" value="Submit">
            </form>
        </div>
    </div>
</div>
</div>

</body>
 
</html>
