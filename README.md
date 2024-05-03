# portfolio
<!DOCTYPE html>
<html>
  <head>
    <title>my portfolio</title>
    <link rel="stylesheet" href="styles.css">
 <style>
  div{
       border: 1px;
        width: 65%;
        height: fit-content;
        padding-left:20px;
        padding-right:20px;
  }
 h3 {
  color: $orange;
  margin: 10px 0;
  text-transform: lowercase;
  font-size: 1.25em;
}
.resume {
  width: 960px;
  background: $darkest-blue;
  color: $white;
  margin: 20px auto;
  box-shadow: 10px 10px $black;
  position: relative;
  display: flex;
}
.resume .base {
  width: 30%;
  padding: 30px 15px;
  background: $darker-blue;
  color: $white;
}
.resume .base .profile .info {
  text-align: center;
  color: $white;
}
</style>

  </head>

  <body style="background-color: aqua;" >
    <hr>
    <div class="resume">
      <div class="base">
        <div class="profile">
          <div class="photo">
            <img src="data:image/png;base64,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">
            <i class="fas fa-rocket"></i>
          </div>
          <div class="info">
            <h1 class="name" style="color: darkblue;">BhanuPutsala</h1>
              <h2 class="job" style="color: darkblue;">Student</h2>
          </div>
        </div>
      </hr>
        <div class="about">
          <h3 style="color: darkblue;">About Me</h3>I am flexible,reliable and possess excellent time keeping skills, i am an self motivated ,responsible & hard working person.
        </div>
        <div class="contact">
          <h3 style="color: darkblue;">Contact Me</h3>
          <div class="call"><span>1.9182122104</span></div>
          <div class="address"><span>2.Angara</span></div>
          <div class="email"><span>3.bhanusiri6129@gmail.com</span></div>
          <div class="link"><span>4.www.linkedin.com/in/bhanu-putsala-8261032b0</span></div>
        </div>
        <div class="">
          <h3 style="color: darkblue;">Languages</h3>
          <div class="box">
              <li>english</li>
              <li>telugu</li>
              <li>french</li>
          </div>
        </div>
        </div>
      <div class="">
        <div class="edu">
          <h3 style="color: darkblue;"><i class=""></i>Education</h3>
          <ol>
            <li><span>Bachelor of Technology<br>Artifical intelligence and machine learning</span><br><small>ISTS College</small><br><small>2021-2025</small><br> <small>8.30</small>
            </li>
            <li><span>Board of Intermediate<br>M.p.c </span><br><small>Sree Siddharath Junior College</small><br><small>2019-2021</small><br><small>861</small></li>
              <li><span>SSC </span><br><small>Z.p.p. High School</small><br><small>2018-2019</small><br><small>9.3</small></li>
          </ol>
        </div>
        <div class="skills-prog">
          <h3 style="color: darkblue;"><i class=""></i>Programming Skills</h3>
          <div>
            <ol>
           <li> <span>Html</span></li><br>
            <li><span>css</span></li><br>
            <li><span>java</span></li><br>
            <li><span>python</span></li><br>
            <li><span>c programming</span></li>
            </ol>
          </div>

        <div class="interests">
          <h3 style="color: darkblue;"><i class=""></i>Interests</h3>
          <div class="">
            <ol>
              <li><span>Art</span></li><br>
              <li><span>Books</span></li><br>
              <li><span>Music</span></li>
            </ol>
            
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
