![yash pic](https://github.com/Ruttala-Yaswanth/myportfolio/assets/150068079/fc1bb1ad-1090-4faa-8b80-c2f0907f7d26)
![LinkedIn-Logo](https://github.com/Ruttala-Yaswanth/myportfolio/assets/150068079/a9400d1c-f5dc-4b01-9032-89804ac25ef2)
![instagram-logo](https://github.com/Ruttala-Yaswanth/myportfolio/assets/150068079/0679e36e-4420-41a5-8e2b-8fd8a6c89418)
![github icon](https://github.com/Ruttala-Yaswanth/myportfolio/assets/150068079/34facac4-4d25-4979-b9d1-9413f7e8bb96)


<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio-Ruttala yaswanth</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" type="image/Portfolio-icon" href="./image/portfolio.ico">
</head>
<body>
    <div class="home main">
        <h1>Hey hi,<br>I am <strong class="name">RUTTALA YASWANTH,</strong><br>Full stack web developer</h1>
        <img src="./image/yash pic.jpg" alt="my image"/>
    </div>
     <div class="home lower">
        <a href="./about.html"><button class="button">click here to know about me</button></a>
        <div>
            <a href="https://www.linkedin.com/in/ruttala-yaswanth">
                <img src="./image/LinkedIn-Logo.jpg" alt="linkedin" class="social-icon-img"/>
            </a>
            <a href="https://github.com/Ruttala-Yaswanth">
                <img src="./image/github icon.png" alt="github" class="social-icon-img"/>
            </a>
            <a href="https://www.instagram.com/yaswanth___ruttala">
                <img src="./image/instagram-logo.png" alt="instagram" class="social-icon-img">
            </a>
        </div>
    </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>about</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" type="image/Portfolio-icon" href="./image/portfolio.ico">
</head>
<body>
    <div class="content">
        <p>
             I am <b>Ruttala Yaswanth</b>, currently pursuing my third year of B.Tech in the EEE branch at <strong><a href="https://www.raghuenggcollege.com"><u>Raghu Engineering College</u></a></strong>, located on the outskirts of Visakhapatnam. My programming skills include proficiency in <u><b>C, Python, and JavaScript</b></u>. I am enthusiastic about learning and am currently focusing on <b>full-stack web development</b>, with an ongoing winter internship at <a href="https://prepinsta.com/home">PrepInsta</a> to enhance my skills in this area.
         </p> 
    </div>
    <a href="./index.html">
      <button class="button">back</button>
    </a>
</body>
</html>

@import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@1&family=Poppins:wght@300&display=swap');
body{
    background-color: black;
    background-image: url(./image/background\ img-portfolio.webp);
    background-size: cover;
}
h1{
    color: aliceblue;
}
img{
    width: 300px;
    height: auto;
    border-radius: 50%;
    aspect-ratio: 1;
    object-fit: cover;

}

.main{
    height: 60vh;
    padding: 50px;
}

.lower{
    height: 100px;
    padding: 20px;
}
.home{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}

.name{
    color: rgba(0, 179, 255, 0.872);
    font-family: 'DM Serif Display', serif;
}

.button{
    background-color: darkseagreen;
    height: 40px;
    width: auto;
    border-width: 0px;
    border-radius: 12px;
}

h1{
    font-family: 'Poppins', sans-serif;

}

.social-icon-img {
    height: 50px;
    width: auto;
    padding: 10px;
}
.content{
    background-color: rgba(255, 255, 255, 0.322);
    color: white;
    margin: 100px;
    padding: 90px;
    border-radius: 60px;
}
