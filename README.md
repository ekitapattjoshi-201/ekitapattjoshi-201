<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="st.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    
    <div class="header">
        <nav> 
            <a href="#"><img src="ekita.jpg" alt="logo" class="logo" height="120px" width="150px"></a>
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">PROJECTS</a></li>
                <li><a href="#">SERVICES</a></li>
                <li><button type="button"class="button-cv">DOWNLOAD CV</button></li>
            </ul>
        </nav>

        <div class="body">
            <p class="demo1">ABOUT ME</p>
            <h1>Hello <br> I'm Ekita <span>Pattjoshi .</span></h1>
            <p class="demo2">A designer knows he/she has achived perfection not when
                <br> there is noting left to add, but when tere is nothing left to
                <br> take away.
            </p>

            <button type="button" class="button-lrn">LEARN MORE</button>
            <button type="button" class="button-hire">HIRE ME</button>
        </div>

        <div class="image">
            <img src="1697558774111.jpg">
        </div>
    </div>
    <section class="contact">

        <div class="contact-form" id="contact">
            <h1>Contact<span> Me</span></h1>
            <p>I am available for freelance work. Connect with me via phone:000261728 or email: ekita@gmail.com.</p>
            <form action="">
                <input type="" placeholder="Your Name" required>
                <input type="email" name="email" id="email" placeholder="E-mail" required>
                <input type="" placeholder="Write a subject" required>
                <textarea name="" id="" cols="30" rows="10" placeholder="Your Message" required>
    </textarea>
                <input type="Submit" name="" value="Submit" class="btn">
            </form>
        </div>

    </section>



    <footer>
        <p>Ekita Pattjoshi</p>
        <p>For more HTML,CSS and JAVASCRIPT Knowldege -Please click on the link below :</p>
        <div class="social-media">
            <a href="#"><i class="fa-brands fa-facebook"></i></a>
            <a href="#"><i class="fa-brands fa-instagram"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin"></i></a>
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
        </div>
        <p class="end">CopyRight By Ekita Pattjoshi</p>


    </footer>

</body>
</html>

st.css
*{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
}

.header{
    width: 100%;
    height: 100vh;
    background-color: seagreen;
}

nav{
    display: flex;
    margin: auto;
    width: 90%;
    padding: 20px;
    align-items: center;
    justify-content: space-between;
}

nav ul li{
    display: inline-block;
    list-style: none;
    margin: 10px;
}

nav ul li a{
    text-decoration: none;
    color: black;
    font-weight: bolder;
}

nav ul li a:hover{
    background-color: seagreen;
    border-radius: 2px;
    color: white;
}

.button-cv , .button-gfc{
    display: inline-block;
    margin-left: 0%;
    border-radius: 5px;
    transition: background-color 0.5s;
    background: black;
    padding: 10px;
    text-decoration: none;
    font-weight: bold;
    color: white;
    border: none;
    cursor: pointer;
}

.button-cv:hover{
    background-color: white;
    color: black;
}

.button-gfc{
    background: lightsalmon;
}

.button-gfc:hover{
    background-color: white;
    color: black;
}

.body{
    margin-left: 100px;
    margin-top: 100px;
}

.body h1{
    font-size: 30px;
    color: black;
    margin-bottom: 20px;
}

.demo1{
    color: orange;
    margin-bottom: 30px;
}

.demo2{
    color: black;
    line-height: 20px;
}

.button-lrn, .button-hire{
    background: lightsalmon;
    padding: 10px 12px;
    text-decoration: none;
    font-weight: bold;
    color: whitesmoke;
    display: inline-block;
    margin: 30px 8px;
    border-radius: 5px;
    transition: background-color 0.3s;
    border: none;
    letter-spacing: 1px;
    cursor: pointer;
}

.button-lrn:hover{
    background-color: whitesmoke;
    color: black;
}

.button-hire{
    background: black;
}

.button-hire:hover{
    background-color: seagreen;
}

span{
    color: seagreen;
}

.image{
    width: 80%;
    height: 80%;
    position: absolute;
    bottom: 0;
    right: 40px;
}

.image img{
    height: 80%;
    position: absolute;
    left: 80%;
    bottom: 20%;
    transform: translate(-60%);

}

section{
    padding: 40px 15%;
}
.contact{
   background: seagreen ;
   height: 100%;
   width: 100%;
   min-height:100vh;
   display: grid;
   grid-template-columns: repeat(2,2fr);
   align-items: center;
   grid-gap: 6rem;
}

.contact-form h1{
    font-size: 80px;
    color:#fff;
    margin-bottom: 20px;
}

span{
    color:#3e00f9;
}
.contact-form p{
    color: #c6c9d8bf;
    letter-spacing: 1px;
    line-height: 26px;
    font-size: 1.1rem;
    margin-bottom: 3.8rem;
}

.contact-form form{
    position: relative;


}
.contact-form form input,
form textarea{
    width:100%;
    padding: 17px;
    border: none;
    outline: #191919;
    color:black;
    font-size: 1.1rem;
    margin-bottom: 0.7rem;
    border-radius: 10px;
}

.contact-form textarea{
    resize: none;
    height: 200px;
}
.contact-form form .btn{ 
    display: inline-block;
    background: seagreen;
    font-size: 1.1rem;
    letter-spacing: 1px;
    text-transform: uppercase;
    font-family: 600;
    border: 2px solid transparent;
    border-radius: 10px;
    width: 220px;
    transition: ease .20s;
    cursor: pointer;

}
.contact-form form .btn:hover{
    border: 2px solid #0a04c4;
    background: transparent;
    transform: scale(1.1);

}

@media (max-width:1570px){
    section{
        padding:80px 3%;
        transition: .2s;
    }
    .contact-form h1{
        font-size: 60px;
    }
    .contact-form p{
        margin-bottom: 3rem;
    }
}

@media (max-width:1090px){
    .contact{
        grid-gap: 2rem;
        transition: .3s;
    }
}

@media (max-width:1000px){
    .contact{
        grid-template-columns: 1fr;
    }
    .contact-form{
        order: 2;
    }
}


footer {
    position: relative;
    width:100%;
    height:400px;
    display: flex;
    background: seagreen;
    display :flex;
    flex-direction:column;
    align-items: center;
    justify-content: center;
    
}


/*.social a {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 4rem;
    height: 4rem;
    background: transparent;
    border: .2rem solid var(--main-color);
    border-radius: 50%;
    font-size: 2rem;
    color: var(--main-color);
    margin: 3rem 1.5rem 3rem 0;
    transition: .5s ease;
}
.social a:hover {
    background: var(--main-color);
    color: var(--second-bg-color);
    box-shadow: 0 0 1rem var(--main-color);
}*/



footer p:nth-child(1) {
    font-size: 30px;
    color: white;
    margin-bottom: 20px;
    font-weight: bold;
}

footer p:nth-child(2){
    color: white;
    font-size: 17px;
    width: 500px;
    text-align: center;
    line-height: 26px;
}
.social-media{
    display:flex;
}
.social-media a{
    width: 45px;
    height: 45px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: blue;
    border-radius: 50%;
    margin: 22px 10px;
    color: white;
    text-decoration: none;
    font-size: 20px;

}
.social-media a:hover{
    transform: scale(1.3);
    transition: .3s ;

}
.end{

position: absolute;
color: #2500f9;
bottom: 35px;
font-size: 14px;
}







<!---
ekitapattjoshi-201/ekitapattjoshi-201 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
