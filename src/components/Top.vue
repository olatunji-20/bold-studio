<template>
  <div>
    <div class="main">
      <div class="logo">
        <img src="../assets/bold-logo.png" class="logoo" />
      </div>
      <div class="options">
        <ul>
          <li>PROJECTS</li>
          <li>JOURNAL</li>
          <li>ABOUT</li>
          <li>CONTACT</li>
        </ul>
      </div>
      <div class="start">
        <p>START A PROJECT</p>
      </div>
    </div>
    <div class="design">
      <div class="first">
        <h3>WE DESIGN WITH THE FUTURE IN MIND.</h3>
        <div class="project">
          <h4>VIEW LATEST PROJECTS</h4>
          <div class="arrow">
            <img src="../assets/arrow.png" class="logoo" />
          </div>
        </div>
      </div>
      <div class="sec">
        <div class="approach">
          <p>
            The design approach of BOLD is a carefully considered combination of
            materials, detailing and precision combined with practical problem
            solving unique to each project.
          </p>
        </div>
      </div>
    </div>
    <div class="large-image">
      <img src="../assets/chair.png" class="pictures" />
    </div>
    <div class="creating">
      <div class="create">
        <p class="inter">
          AN INTERNATIONAL DESIGN STUDIO CREATING FOR THE FUTURE.
        </p>
      </div>
      <div class="create2">
        <p>
          We're a small team of curious humans who create work we are proud of
          for people and brands we belive in. With collaboration at the heart of
          every project, we identify what skills are required and then bring the
          best people together to create something truly extraordinary.
        </p>
        <br />
        <p>
          Combining strategy, branding, web design and development, we build
          digital experiences that transform the way people connect and interact
          with brands.
        </p>
      </div>
    </div>
  </div>
</template>
  
<script>
export default {
  name: "Top",
  data() {
    return {};
  },
};
</script>
  
<style scoped>
.main {
  width: 100%;
  height: 7.5rem;
  padding: 1.875rem;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.logo {
  width: 180px;
  height: 30px;
  position: relative;
  top: 12px;
  right: 3.125rem;
}
.logoo {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.options {
  width: auto;
  height: 3.125rem;
}
.options ul li {
  list-style-type: none;
  display: inline-block;
  font-size: 14px;
  margin: 0px 15px 0px 0px;
  transition: 0.5s ease;
}

.options ul li:hover {
  text-decoration: underline;
  cursor: pointer;
}
.start {
  width: 12.75rem;
  height: 2.8125rem;
  border: 1px solid black;
  position: relative;
  left: 2rem;
  font-size: 14px;
  transition: 0.5s;
}
.start:hover {
  border: 1px solid green;
  cursor: pointer;
}
.design {
  width: 96%;
  height: auto;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  padding-top: 6.25rem;
  justify-content: space-between;
  margin: 0px auto;
}
.first {
  width: 60%;
  height: 15.625rem;
  padding: 0.3125rem 1.25rem;
  text-align: left;
}
.first h3 {
  font-size: 45px;
}
.first .project {
  height: auto;
  width: 15.625rem;
}
.first .project h4 {
  line-height: 0px;
  position: relative;
  text-decoration: underline;
  display: inline-block;
}

@keyframes blinkd {
  0% {
    margin-left: 0px;
  }
  50% {
    margin-left: 7px;
  }
  100% {
    margin-left: 0px;
  }
}
.first .project .arrow {
  width: 12px;
  height: 12px;
  margin-left: 7px;
  display: inline-block;
  animation-name: blinkd;
  animation-duration: 1.5s;
  animation-timing-function: ease;
  animation-iteration-count: infinite;
}
.sec {
  width: 35%;
  height: 15.625rem;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
}
.sec .approach {
  height: auto;
  width: 100%;
  text-align: left;
  padding-right: 5px;
  font-size: 14px;
  line-height: 20px;
}
.large-image {
  width: 94%;
  height: 43.75rem;
  margin: 3.125rem auto 6.25rem;
}
.pictures {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.creating {
  border-bottom: 2px solid black;
  width: 94%;
  height: auto;
  padding: 0.62rem;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  margin: 0.625rem auto;
  justify-content: space-between;
}
.creating .create {
  width: 48%;
  height: 18.75rem;
  text-align: left;
}
.creating .create2 {
  width: 43%;
  height: 18.75rem;
  text-align: left;
  padding-top: 1rem;
  font-size: 14px;
  line-height: 20px;
}
.create .inter {
  font-size: 30px;
}
@media screen and (max-width: 800px) {
  .logo {
    right: 0px;
  }
  .start {
    display: none;
  }
  .large-image {
    height: 28rem;
  }
}

@media screen and (max-width: 480px) {
  .main {
    justify-content: flex-start;
  }
  .options {
    display: none;
  }
  .design {
    margin: 0px auto;
    width: 94%;
  }
  .first {
    width: 100%;
  }
  .first h3 {
    font-size: 40px;
  }
  .sec {
    width: 100%;
  }
  .large-image {
    height: 20rem;
  }
  .creating .create {
    width: 100%;
    height: 14rem;
  }
  .creating .create2 {
    width: 100%;
  }
}
</style>