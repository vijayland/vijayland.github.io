<template>
  <div>
    <div class="info">
      <!-- <img src="@/assets/profile.png" alt="profile-pic" /> -->
      <h1>Vijay Ethuraj</h1>
      <ul>
        <li><span class="bx bxs-briefcase"></span>Software Engineer</li>
        <li><span class="bx bxs-location-plus"></span>TamilNadu, In.</li>
      </ul>
    </div>
    <div class="paragraph">
      <p>Hi, I am enthusiastic computer programmer.</p>
    </div>
    <hr />
    <div class="social-media">
      <a href="http://github.com/vijayland"
        ><h3><span class="bx bxl-github"></span>Github</h3></a
      >
      <a href="https://gitlab.com/evj"
        ><h3><span class="bx bxl-gitlab"></span>Gitlab</h3></a
      >

      <a href="https://www.linkedin.com/in/vijayethuraj/"
        ><h3><span class="bx bxl-linkedin-square"></span>Linkedin</h3></a
      >
    </div>
  </div>
</template>
<style>
body {
  display: flex;
  padding: auto;
  margin-right: 50%;
  font-family: "Overpass Mono", monospace;
  background-color: #ecf0f1;
}
li {
  display: flex;
  text-decoration: none;
}
li span {
  padding-right: 2px;
}
img {
  width: 250px;
  border-radius: 25px;
}
a {
  text-decoration: none;
  color: black;
}
.social-media {
  display: flex;
}
.social-media a {
  padding-right: 20px;
}
</style>