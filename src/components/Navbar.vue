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
            <div class="start"></div>
        </div>
        <div class="design">
            <div class="first"></div>
            <div class="sec"></div>
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
    height: 50px;
    border: 1px solid red;
    position: relative;
    left: 20px;
  }
  .design {
    border: 2px solid blue;
    width: 100%;
    height: 450px;
    padding-top: 145px;
  }
  .first {
    width: 60%;
    height: 300px;
    border: 1px solid red;
    display: inline-block;
  }
  .sec {
    width: 39%;
    height: 300px;
    border: 1px solid red;
    display: inline-block;
  }

</style>
  