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
    height: 7.5rem;
    background: pink;
    border: 1px solid red;
    padding: 1.875rem;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
  }
  .logo {
    width: 12.5rem;
    height: 3.125rem;
    border: 1px solid green;
    position: relative;
    right: 3.125rem;
  }
  .options {
    width: 28.125rem;
    height: 3.125rem;
    border: 1px solid blue;
  }
  .options ul li {
    list-style-type: none;
    display: inline-block;
    font-size: 14px;
    margin: 0px 15px;
  }
  .start {
    width: 13.75rem;
    height: 2.8125rem;
    border: 1px solid red;
    position: relative;
    left: 1.25rem;
    font-size: 14px;
  }
  .design {
    border: 2px solid blue;
    width: 100%;
    height: 25.625rem;
    display: flex;
    flex-direction: row;
    padding-top: 6.25rem;
    justify-content: space-between;
  }
  .first {
    width: 60%;
    height: 15.625rem;
    border: 1px solid red;
    /* display: inline-block; */
    padding: 0.3125rem 1.25rem;
    text-align: left;
  }
  .first h3 {
    font-size: 45px;
  }
  .first .project {
    border: 2px solid green;
    height: auto;
    width: 15.625rem;
    /* padding: 5px; */
  }
  .first .project h4 {
    line-height: 0px;
    position: relative;
    top: 0.3125rem;
  }
  .sec {
    width: 35%;
    height: 15.625rem;
    border: 1px solid red;
    /* display: inline-block; */
  }
  .sec .approach {
    border: 1px solid firebrick;
    height: 5rem;
    width: 90%;
    text-align: left;
    margin-top: 10.625rem;
    font-size: 14px;
    line-height: 20px;
  }
  .large-image {
    width: 94%;
    height: 43.75rem;
    border: 1px solid darkblue;
    margin: 3.125rem auto 6.25rem;
  }
  .creating {
    border-bottom: 2px solid goldenrod;
    width: 94%;
    height: auto;
    padding: 0.62rem;
    display: flex;
    flex-direction: row;
    margin: 0.625rem auto;
    justify-content: space-between;
  }
  .creating .create {
    width: 48%;
    height: 18.75rem;
    border: 1px solid chartreuse;
    text-align: left;
  }
   .creating .create2 {
    width: 43%;
    height: 18.75rem;
    border: 1px solid chartreuse;
    text-align: left;
    padding-top: 1rem;
    font-size: 14px;
    line-height: 20px;
  }
  .create .inter {
    font-size: 30px;
  }

</style>
  