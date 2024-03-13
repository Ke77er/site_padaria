<template>
  <section id="section-about" class="section-about">
    <!DOCtype html>
<html lang="eng">
  <head>
    <link href="https://fonts.googleapis.com/css2?family=PT+Serif:wght@700&family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=PT+Serif:wght@700&display=swap" rel="stylesheet">    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <body>
    <header id="header">
        <a href="https://www.freeiconspng.com/img/38215" title="Image from freeiconspng.com"><img id="header-img" src="https://www.freeiconspng.com/uploads/chef-cook-cooking-culinary-gourmet-head-toque-icon-15.png" width="55" alt="Chef, cook, cooking, culinary, gourmet, head, toque icon" /></a>
      <nav id="nav-bar">
        <ul>
          <li><a class="nav-link" href="#home"><strong>Home</strong></a></li>
          <li><a class="nav-link" href="#aboutus"><strong>About Us</strong></a></li>
          <li><a class="nav-link" href="#menu"><strong>Menu</strong></a></li>
          <li><a class="nav-link" href="#contact"><strong>Contact</strong></a></li>
        </ul>
      </nav>
        <h1 id="home"><u>Sweet Design</u></h1>
    </header>
    <main>      
        <div class="section-1 box"></div>
          
        <!--
This is the same image in css/section-1.
Using this image in HTML, the image will move also as you scrow down.

      <img class="main-image" src="https://i.pinimg.com/originals/94/15/64/941564e55aa70cbfeffd4929348f1eaf.jpg" alt="restaurant, bakery, menu">
 -->
      <section id="aboutus">
        <fieldset class="about-us"><br>
          <legend><strong>&ensp;About Us</strong>&ensp;</legend><br>
          <p>Sweet Design is a family owned full custom cake service. We specialize in desserts that impress not only the eye but your tummy. Our desserts are individually designed just for you to ensure your expectations are exceeded, with both aesthetics and flavor.<br><br>

Serving delicious hand crafted baked goods from scratch using high quality ingredients is our mission. You can always expect from us fresh and delicious treats, from a wedding, holiday to a birthday party or anything in between. We work with you individually to obtain the ultimate design so that your vision can come to life, and add that something special to your event.
</p><br>
        </fieldset>
      </section>
      <!-- Menu -->
     <div class="section-menu">
      <section id="menu">
        <a href="#"><img class="menu-img" src="https://www.lifeloveandsugar.com/wp-content/uploads/2018/01/Chocolate-Covered-Strawberry-Cupcakes4.jpg" width="250" alt="chocolate cupcakes with strawberry toping"></a><h2><span class="A">Cupcakes</span></h2>
        <a href="#"><img class="menu-img" src="https://images.squarespace-cdn.com/content/v1/5b663fdaf793924d129c4808/1565796308735-9EZV0OC3IJF3172L8O7Z/ke17ZwdGBToddI8pDm48kBYqM30z5AqL0F13YT7UOhp7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1UVVboVSxqMMDqP7sFwVe1j3G715-GJgIimxjHoB0qdGOFK4eMZgYA6RDahiKMr8qgw/IMG_0042.JPG" width="281" alt="cake covered with vanilla frosting and donut toping"></a><h2><span class="B">Cakes</span></h2>
        <a href="#"><img class="menu-img" src="https://www.biscotts.com/wp-content/uploads/2016/05/FRENCH-STYLE-MACAROONS.png" width="323" height="" alt="five macaroons with different color and flavor, green color, pink color, yellow color, red color and orange color"></a><h2><span class="C">Cookies</span></h2>
      </section>
     </div>
      <section id="section-2">        
        <iframe id="video" width="670" height="315" src="https://www.youtube.com/embed/demCt-E4-NM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br class="hr-br"><hr>     
      </section>
      <section id="contact">
        <aside id="form-text-position">
        <h3>GET IN TOUCH</h3><br>
          <p class="form-txt">Please take a moment to let us know how we can serve<br> you better or what other products you would like us to source for you.</p><br><br>
          <p class="form-txt">We would love to hear from you!</p>
        </aside>
        <aside>
        <form id="form" action="https://www.freecodecamp.com/email-submit">
         <label id="name-label" for="name">Name:</label><br><br>         
            <input type="text" name="name" id="name" placeholder="Enter name"></input><br><br>
          <label id="email-label" for="email">Email:</label><br><br>       
            <input type="email" name="email" id="email" placeholder="Enter email"></input><br><br>
        <label id="name-label" for="name">Message:</label><br><br>       
            <textarea id="comments" placeholder="Optional..." rows="6"></textarea><br><br>
        <input type="submit" id="submit" value="submit"><br><br>
        </form>
        </aside>
      </section>     
    </main>     
    <footer>          
    <span class="personal-info">Created by Danilo Velez</span>
    <span class="footer-txt">Copyright 2020</span>
    </footer>
  </body>
</html>

<!--
<img src="https://miro.medium.com/max/1170/1*joqxCrOjt2ev_sROeVMP5Q.png"
>
-->
  </section>
</template>

<script>
export default {
  name: "SectionBakery",
  data() {
    return {
    };
  },
  computed: {
  },
  mounted() {
  },
  methods: {
  },
};
</script>
<style>
@import url('../src/assets/styles.css');
</style>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#header {
  position: fixed;
  z-index: 1;
  width: 100%;
  height: 55px;
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  flex-wrap: wrap;
  background-color: #f0e8d3;
}

#header-img {
  position: absolute;
  height: 50px;
  width: 50px;
  bottom: 5px;
  left: 40px;
}
.box {
  width: 100%;
}
.section-1 {
  height: 100vh;
  background-image: url(https://i.pinimg.com/originals/94/15/64/941564e55aa70cbfeffd4929348f1eaf.jpg);
  background-attachment: fixed;
  background-size: cover;
}
h1 {
  position: absolute;
  top: 0px;
  left: 90px;
  font-size: 30px;
  font-family: 'Pacifico', cursive;
 }
.A {
  position: absolute;
  top: 380px;
  left: 70px;   
}
.B {
  position: absolute;
  top: 380px;
  left: 430px;
  
}
.C {
  position: absolute;
  top: 380px;
  left: 790px;
}
.nav-link  {
  color: black;  
  text-decoration: none;
  padding: 1em;
  margin: 0px 10px;
  font-family: 'PT Serif', serif;
  
}
li {
  position: relative;
  list-style: none;
  display: flex;
  float: left;
  bottom: 2px;
}
#menu {
  top: 50px;
  margin-left: 55px;
  margin-right: 35px;
  display: flex;
  position: relative;
  grid-gap: 30px;
  justify-content: space-between;
 }
.menu-img{
  border-radius: 10px;
}
iframe {
  margin-top: 100px;
  margin-left: 220px; 
}
fieldset {
  margin-top: 100px;
  margin-right: 200px;
  margin-left: 200px;
 }
.about-us {
  text-align: center;
  font-family: 'PT Serif', serif;
}

.section-menu {
  background-color: #f0e8d3;
  width: 100%;
  height: 500px;
  margin-top: 100px;
}
#contact {
  margin-top: 100px;
}
#form {
  display: block;
  float: right;
  width: 40%; 
  font-family: 'PT Serif', serif;
  margin-bottom: 50px;
}
textarea{
  width: 80%;
  text-indent: 5px;
  border-radius: 3px;
  border: 1px solid
}
input{
  width: 80%;
  height: 30px;
  text-indent: 5px;
  border-radius: 3px;
  border: 1px solid
}
#form-text-position {
  float: left;
  position: absolute;
  margin-left: 5%;
}
h3 {
  margin-left: 25%;
  font-size: 40px;
}
.form-txt {
  font-size: 18px;
}
hr {
  margin-top: 100px;
}
#submit {
  width: 30%;
  height: 30px;
  background-color: black;
  color: white;
  border-radius: 3px;
  font-size: 17px;
}
footer {
  bottom: 0;
  width: 100%;
  z-index: -1;
  display: flex;
  justify-content: space-between;  
  background-color: black;
  color: white;
  height: 70px;
  align-items: center;
}
.footer-txt {
  margin-right: 500px;
  font-size: 17px;
}
.personal-info {
  margin-left: 20px;
  font-size: 17px;
}
@media (max-height: 800px) {
  .personal-info {
    font-size: 17px;
  }
}

  



</style>