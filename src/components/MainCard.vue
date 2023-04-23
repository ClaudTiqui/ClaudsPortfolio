<template>
  <div class="main-container">
    <div class="container-one">
      <div class="profile">
        <img src="../assets/profilePicture.jpg" alt="" />
        <h3>Claud Tiqui</h3>
        <p>Software Developer</p>
      </div>
      <div class="social-links">
        <div class="link">
          <a href=""
            ><img src="../assets/github.png" alt="" />
            <h2>GitHub</h2>
          </a>
        </div>

        <div class="link">
          <a href=""
            ><img src="../assets/linkedIn.png" alt="" />
            <h2>LinkedIn</h2>
          </a>
        </div>
      </div>
    </div>
    <div class="container-two">
      <div class="about-me">
        <h1>About Me</h1>
        <p>
          Hi there! I'm a software developer who found my passion for technology
          through a non-linear career path. Originally, I dreamed of joining the
          Air Force, but as I got closer to the reality of that career, I
          realized it wasn't the right fit for me. Instead, I discovered my
          interest in software development and found that using my
          problem-solving skills to build applications that improve people's
          lives was my new life goal. With the guidance of my future
          father-in-law, who is a senior software developer, I dove headfirst
          into the tech industry. While I know it won't be an easy journey, I'm
          eager to learn and grow as a developer every day. I recently joined
          Tech Elevator to help launch my career and I'm excited about the
          opportunity to make an impact in the tech space. I have experience in
          Object-Oriented Programming using Java, Web Application Development
          using HTML, CSS, JavaScript, Spring Boot, and Vue.js, and Database
          Programming using JDBC, SQL, PostgreSQL, and E/R diagrams. I'm also
          familiar with Agile, Unit Testing (JUnit), Integration Testing, Unix
          Command Line navigation, Git, and IntelliJ development tools and
          techniques. If you're looking for someone with a passion for software
          development and a drive to learn and grow, please don't hesitate to
          reach out. I'd love to chat with you and see if I can help make an
          impact on your team.
        </p>
      </div>
      <div class="technology-section">
        <h1>Technologies Studied</h1>
        <div class="logos">
          <img src="" alt="" />
        </div>
      </div>
      <div class="button-container">
        <div class="projects-button">
          <a href="">My Projects</a>
        </div>
        <div class="projects-button">
          <a href="">My Resume</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
img {
  height: 20px;
}

.main-container {
  display: flex;
  flex-direction: row;
  background-color: rgb(210, 214, 218);
  border-radius: 25px;
}

.container-one {
  background-color: aqua;
  padding: 2.5%;
  border-radius: 25px;
  width: 30%;
}
.logos img{
    height: 2.5rem;
}
.profile img {
  height: 5rem;
  border-radius: 50%;
}

.link a {
  text-decoration: none;
  color: black;
  font-size: 10px;
}
.link img{
    height: 2rem;
}

.container-two {
  background-color: rgb(255, 255, 255);
  margin: 2.5%;
  width: 70%;

}

.about-me{
    text-align: left;
    margin: 2.5%;
    width: 70%;
}
.projects-button{
    background-color: rgb(6, 174, 180);
    margin: 5px;
    margin: 5px;
    border-radius: 15px;

}
.button-container{
    margin-top: 5%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
.projects-button a{
    text-decoration: none;
    color: white;
}
</style>