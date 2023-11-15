<style>
  /* Colors and fonts */
body {
  background: #282C33;
  color: #ffffff;
  font-size: 19px;
  font-family: 'Roboto', sans-serif;
  scroll-behavior: smooth;
}
.container{
  width: 90%;
  margin: 0 auto;
}
.section{
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 25px 0px;
}
h1, h2, h3 , a{
  font-family: 'Roboto', sans-serif;
}
header{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
}
header .item{
  padding-left: 30px;
}
.purple{
  color: #C778DD;
}
header .logo{
  width: 150px;
}
.intro-info h1{
  font-family: 'Roboto', sans-serif;
  font-weight: 700;
  color: #fff;
  font-size: 40px;
  line-height: 50px;
  letter-spacing: 5px;
}
.intro-info p{
  font-family: 'Roboto', sans-serif;
  font-weight: 300;
  color: #fff;
  font-size: 20px;
  line-height: 25px;
}
.btn {
  border: 1px solid #C778DD;
  padding: 8px 20px;
}
.intro-img> div{
  border: 1px solid #fff;
  padding: 8px 20px;
}

.project-card {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.blog-card{
  border: 1px solid purple;
  padding: 10px 15px;
  width: 330px;
}

.skills-section {
  margin: 50px 0px;
}
.list-skills{
  display: flex;
  padding-left: 0px;
  justify-content: space-between;
}
.list-skills li{
  border: 1px solid purple;

}
.list-skills li h4{
  border-bottom: 1px solid purple;
  padding: 10px 10px;
  margin: 5px 0px;
  font-size: 20px;
  line-height: 26px;
}

.list-skills li p{
  padding: 10px 10px;
  font-family: 'Roboto', sans-serif;
  font-weight: 300;
  font-size: 18px;
  line-height: 28px;

}

.about_me{
  margin:25px 0px
}
.inner-about{
  width: 100%;
}
.inner-about .about-info,
.inner-about .about-img{
  width: 50%;
}
.about-img{
  display: flex;
  justify-content: end;
}
.inner-about .about-info h3,
.inner-about .about-info p,
.contact-info p,
.contact-link{
  color: #ABB2BF;
  font-size: 20px;
  line-height: 32px;
  font-family: 'Roboto', sans-serif;
  font-weight: 300;
}
.contact-link,
.contact-info p{
  color: #ABB2BF;
  font-size: 16px;
  line-height: 22px;
  font-family: 'Roboto', sans-serif;
  font-weight: 300;
}

.inner-header.section{
  display: flex;
    justify-content: start;
    align-items: center;
    margin: 25px 0px;
}
.skills-section .inner-header::after,
.inner-header::after{
  content: "";
    border-top: 1px solid purple;
    height: 1px;
    width: 35%;
    margin-left: 10px;
}
.contact-link{
  border: 1px solid;
  padding: 10px;
  text-align: left;
}
.contact-link ul{

}
.inner-contact{
  display: flex;
  justify-content: space-between;
}
h1 {
  color: #C17767;
  font-size: 32px;
  font-weight: 900;
}
h2 {
  color: #629677;
  font-size: 20px;
  font-weight: 500;
}
a {
  text-decoration: none;
  color: #fff;
  font-weight: 600;
  font-size: 20px;
}
a:hover {
  color: #98B6B1;
}
ul{
  display: flex;
  padding-left: 0px;
  justify-content: center;
}
ul li{
  margin-right: 14px;
  list-style: none;
}
.responsive {
  width: 100%;
  height: auto;
}

@media (max-width: 960px) {
  /* For a screen < 960px, this CSS will be read */
  .container {
    width: 90% !important;
  }
  .menu_item{
    display: none
  }

  .blog-card {
    padding: 10px 15px;
    width: 290px;
    margin-bottom: 15px;
  }
  list-skills {
    display: flex;
    justify-content: normal;
    flex-wrap: wrap;
  }
  .list-skills li {
      margin-bottom: 20px;
  }
  .inner-about .about-info,
  .inner-about .about-img{
    width: 100%;
    margin-bottom: 15px;
  }
  .inner-contact {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
  }
  .list-skills {
      display: flex;
      padding-left: 0px;
      justify-content: normal;
      flex-wrap: wrap;
  }
}

@media (max-width: 720px) {
  /* For a screen < 720px, this CSS will be read */
  .container {
    width: 500px;
  }
  .menu_item{
    display: none
  }
  .section{
    flex-wrap: wrap;
  }
  .blog-card {
    padding: 10px 15px;
    width: 290px;
    margin-bottom: 15px;
  }
  list-skills {
    display: flex;
    justify-content: normal;
    flex-wrap: wrap;
  }
  .list-skills li {
      margin-bottom: 20px;
  }
  .inner-about .about-info,
  .inner-about .about-img{
    width: 100%;
    margin-bottom: 15px;
  }
  .inner-contact {
      display: flex;
      justify-content: flex-start;
      flex-wrap: wrap;
  }
  .list-skills {
      display: flex;
      padding-left: 0px;
      justify-content: normal;
      flex-wrap: wrap;
  }
}

@media (max-width: 540px) {
  /* For a screen < 540px, this CSS will be read */
  .container {
    width: 300px;
  }
}
</style>
<div class="container">
      <section class="intro section">
        <div class="intro-info">
          <h1>Hello, I'm a <span class="purple">web designer</span> and <br> <span class="purple">front-end developer<i class="fa-solid fa-laptop-code"></i></span></h1>
          <p> He crafts responsive websites where technologies meet creativity </p>
          <a class="btn"> Contact me !!</a>
        </div>
        <div class="intro-img">
          <img src="./images/person.png" alt="Manoj Vasava">
          <div><span class="purple"><i class="fa-solid fa-square"></i></span> Currently working on Portfolio</div>
        </div>
      </section>
      <section class="skills-section">
        <div class="inner-header section">
          <h3><span class="purple">#</span>skills</h3>
        </div>
        <div class="skills">
          <ul class="list-skills">
            <li>
              <h4>Languages</h4>
              <p>TypeScript Python
                JavaScript</p>
            </li>
            <li>
              <h4>Languages</h4>
              <p>TypeScript Python
                JavaScript</p>
            </li>
            <li>
              <h4>Databases</h4>
              <p>SQLite
                PostgreSQL
                Mongo</p>
            </li>
            <li>
              <h4>Other</h4>
              <p>HTML CSS EJS SCSS REST Jinja</p>
            </li>
            <li>
              <h4>Tools</h4>
              <p>VSCode Neovim Linux Lua Figma XFCE Arch Git Font Awesome</p>
            </li>
          </ul>
        </div>
      </section>
      <section id="about" class="about_me">
        <div class="inner-header section">
          <h3><span class="purple">#</span>about-me</h3>
        </div>
        <div class="inner-about section">
          <div class="about-info">
            <h3>Hello, I'm Manoj <i class="fa-solid fa-laptop-code"></i></h3>
            <h3> I'm Front-End Developer 💻</h3>
            <div>
            <p>
              Creative Front-End Developer with 3+ years of experience providing high-impact web solutions
              for diverse industry organizations. Skilled in designing, developing, managing and testing
              multiple web-based applications incorporating a range of technologies. </p>
            <p>  Aspiring to combine broad background with strong technical skills to excel as a
              Front-End Developer and WordPress Developer.</p>
            </div>
          </div>
          <div class="about-img">
            <img src="./images/me_1.png" alt="Manoj Vasava">
          </div>
        </div>
      </section>
      <section id="contact" class="contact_me">
        <div class="inner-header section">
          <h3><span class="purple">#</span>contact</h3>
       </div>
        <div class="inner-contact">
          <div class="contact-info">
            <p>I’m interested in freelance opportunities. However, if you have other request <br>or question, don’t hesitate to contact me</p>
          </div>
          <div class="contact-link">
            <p>Message Me here</p>
            <ul>
              <li>
                <a href="https://github.com/monster20288" target="_blank">
                  <i class="fab fa-github-square"></i>
                </a>
              </li>
              <li>
                <a href="https://www.facebook.com/djmonstermanoj/" target="_blank">
                  <i class="fa-brands fa-facebook"></i>
                </a>
              </li>
              <li>
                <a href="https://www.linkedin.com/in/manoj-vasava-65a4452b/" target="_blank">
                  <i class="fa-brands fa-linkedin-in"></i>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </section>
    </div>
<!--
**vasavamanoj/vasavamanoj** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
