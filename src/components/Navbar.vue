<template>
    <div>
        <div class="main">
            <div class="logo"></div>
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
              <h3>WE DESIGN THE FUTURE IN MIND.</h3>
              <div class="project">
                <h4>VIEW LATEST PROJECTS</h4>
              </div>
            </div>
            <div class="sec">
              <div class="approach">
                <p>The design approach of BOLD is a carefully considered combination of materials, detailing and precision combined with practical problem solving unique to each project.</p>
              </div>
            </div>
        </div>
        <div class="large-image">

        </div>
        <div class="creating">
          <div class="create">
            <p class="inter">AN INTERNATIONAL DESIGN STUDIO CREATING FOR THE FUTURE.</p>
          </div>
          <div class="create2">
            <p>We're a small team of curious humans who create work we are proud of for people and brands we belive in. With collaboration at the heart of every project, we identify what
              skills are required and then bring the best people together to create something truly extraordinary.
            </p>
            <br />
            <p>Combining strategy, branding, web design and development, we build digital experiences that transform the way people connect and interact with brands.</p>
          </div>

        </div>
    </div>
    
</template>
  
<script>
  export default {
    name: "Navbar",
    data() {
      return {};
    },
  };
</script>
  
<style scoped>
  .main {
    width: 100%;
    height: 120px;
    background: pink;
    border: 3px solid red;
    padding: 30px;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
  }
  .logo {
    width: 200px;
    height: 50px;
    border: 1px solid green;
    position: relative;
    right: 50px;
  }
  .options {
    width: 450px;
    height: 50px;
    border: 1px solid blue;
  }
  .options ul li {
    list-style-type: none;
    display: inline-block;
    font-size: 14px;
    margin: 0px 15px;
  }
  .start {
    width: 220px;
    height: 45px;
    border: 1px solid red;
    position: relative;
    left: 20px;
    font-size: 14px;
  }
  .design {
    border: 2px solid blue;
    width: 100%;
    height: 410px;
    display: flex;
    flex-direction: row;
    padding-top: 100px;
    justify-content: space-between;
  }
  .first {
    width: 60%;
    height: 250px;
    border: 1px solid red;
    /* display: inline-block; */
    padding: 5px 20px;
    text-align: left;
  }
  .first h3 {
    font-size: 45px;
  }
  .first .project {
    border: 2px solid green;
    height: auto;
    width: 250px;
    /* padding: 5px; */
  }
  .first .project h4 {
    line-height: 0px;
    position: relative;
    top: 5px;
  }
  .sec {
    width: 35%;
    height: 250px;
    border: 1px solid red;
    /* display: inline-block; */
  }
  .sec .approach {
    border: 1px solid firebrick;
    height: 80px;
    width: 90%;
    text-align: left;
    margin-top: 170px;
    font-size: 14px;
    line-height: 20px;
  }
  .large-image {
    width: 94%;
    height: 700px;
    border: 1px solid darkblue;
    margin: 50px auto 100px;
  }
  .creating {
    border-bottom: 2px solid goldenrod;
    width: 94%;
    height: auto;
    padding: 10px;
    display: flex;
    flex-direction: row;
    margin: 10px auto;
    justify-content: space-between;
  }
  .creating .create {
    width: 48%;
    height: 300px;
    border: 1px solid chartreuse;
    text-align: left;
  }
   .creating .create2 {
    width: 43%;
    height: 300px;
    border: 1px solid chartreuse;
    text-align: left;
    padding-top: 16px;
    font-size: 14px;
    line-height: 20px;
  }
  .create .inter {
    font-size: 30px;
  }

</style>
  