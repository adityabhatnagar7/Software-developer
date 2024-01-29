<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="my web.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
     crossorigin="anonymous" referrerpolicy="no-referrer" />

</head>
<script type="text/javascript">
    function displayhome(){
        var divhome=document.getElementById("home");
        var divabout=document.getElementById("about");
        var divcontact=document.getElementById("contact");
        var divEducation=document.getElementById("Education");
        divhome.style.display="block";
        divabout.style.display="none";
        divcontact.style.display="none";
        divEducation.style.display="none";
    
    }
    function displayabout(){
        var divhome=document.getElementById("home");
        var divabout=document.getElementById("about");
        var divcontact=document.getElementById("contact");
        var divEducation=document.getElementById("Education");
        divhome.style.display="none";
        divabout.style.display="block";
        divcontact.style.display="none";
        divEducation.style.display="none";

    
    }
    function displaycontact(){
        var divhome=document.getElementById("home");
        var divabout=document.getElementById("about");
        var divcontact=document.getElementById("contact");
        var divEducation=document.getElementById("Education");
        divhome.style.display="none";
        divabout.style.display="none";
        divcontact.style.display="block";
        divEducation.style.display="none";

    
    }
    function displayEducation(){
        var divhome=document.getElementById("home");
        var divabout=document.getElementById("about");
        var divcontact=document.getElementById("contact");
        var divEducation=document.getElementById("Education");
        divhome.style.display="none";
        divabout.style.display="none";
        divcontact.style.display="none";
        divEducation.style.display="block";

        
    
    }
</script>
<body>

    <div id="home">
      <h1 class="hometext"><br><br>Hii'<br> I am Aditya Bhatnagar </h1>
      <h2 class="hometextone">a Devloper</h2>
     
      <img src="C:\Users\Aditya Bhatnagar\OneDrive\Pictures\Screenshots\logo125.png" class="div3">

    </div>
    <div id="about">
     <p>I am a creative and resourceful developer who brings a wealth of knowleadge and Experience to every project with a strong sense of leadership and a 
        a natural ability to work well with others, I am able to take on complex challenge and come up with innovative solutions that make a real diffrence.....
        <br>
        <br>
        Whether working independently or as part of a team i am always ready to roll up my sleeves and get to work using my keen eye for detail and 
        my passion for problem-solving to drive suscces my unqique blend of skills and expertise make me stand out in my field....
     </p>

     
        <h1 class="abo">About</h1>
        
    
     <img src="C:\Users\Aditya Bhatnagar\OneDrive\Pictures\Screenshots\logo125.png" class="div">
      <img src="C:\Users\Aditya Bhatnagar\Downloads\react1.png" class="logo">
      <div class="raound"></div>
      <div class="raound1"></div>
      <div class="raound2"></div>
    </div>
    <div id="contact">
        <img src="C:\Users\Aditya Bhatnagar\Downloads\light.png2.jpeg" class="light">

     <h1 class="div4">Write Me a Message</h1>
     <form>
        Enter Name: <input type="text">
        <br>
        <br>
        Enter Contact Number: <input type="number">
        <br>
        <br>
        Enter Remarks: <textarea name="Remarks" id="" cols="30" rows="10"></textarea>
        <br>
        <br>
      
      
     </form>
     
     <div class="div6">
       <h5>Contact</h5>
        </div><hr class="row">
        <div class="div7">
            <h4>Contact Me</h4>
        </div>
        <div class="div8">
            <i class="fa-solid fa-phone"></i>
            <br><br>
            +91-9755494831
            
        </div>

        <div class="div9">
        <i  class="fa-solid fa-envelope"></i>
        </div>
        <h2 class="div10">abhatnagar677@gmail.com</h2>

    </div>
    <div id="Education">
      <h2 class="div11">Academics</h2>
      <h2 class="div12">B.A Agra University 2022-2024</h2>
      <h3 class="div13">Pali inter Colleage (XII), Art year of completion:2021 Percentage: 68% </h3>
      <h4 class="div14">(X) P.R.T Inter Colleage Year of Completion:2019 Percentage:65%</h4>
      <hr><hr class="div20">
      <h1 class="div15">Skills</h1>
      <h1 class="div16">Python</h1>
      <h1 class="div17">HTML</h1>
      <h1 class="div18">CSS</h1>
      <h1 class="div19">javascript</h1>
    </div>

   

    <div  id="div1">
      <a button="btn" onclick="displayhome()">Home</a>
      <a button="btn" onclick="displayabout()">About</a>
      <a button="btn" onclick="displaycontact()">Contact</a>
      <a button="btn" onclick="displayEducation()">Education</a>

     

    </div>
    
</body>
</html>
