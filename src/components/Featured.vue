<template>
    <section>
        <div class="main">
            <p class="feat">FEATURED PROJECTS</p>
            <div class="view"></div>
            <div class="project">
                <div class="one">
                    <div class="image"></div>
                    <p class="house">STRANFIELD</p>
                    <p class="location">LONDON</p>
                    <p class="year">2022</p>
                </div>
                <div class="two">
                    <div class="image"></div>
                    <p class="house">TERRACE HOUSE</p>
                    <p class="location">NEW YORK</p>
                    <p class="year">2021</p>
                </div>
                <div class="four">
                    <div class="image"></div>
                    <p class="house">BONSAI AVE</p>
                    <p class="location">LAGOS</p>
                    <p class="year">2023</p>
                </div>
                <div class="three ">
                    <div class="image"></div>
                    <p class="house">MODERN VILLA</p>
                    <p class="location">VANCOUVER</p>
                    <p class="year">2022</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Featured",
    data() {
        return{}
    }
}
</script>

<style scoped>
.main {
    border: 2px solid teal;
    width: 93%;
    height: auto;
    margin: 3.125rem auto;
    padding: 5rem 0rem;
    text-align: left;
}
.main .feat {
    color: lightcoral;
    font-size: 40px;
    display: inline-block;
}
.main .view {
    border: 2px solid fuchsia;
    height: 3.125rem;
    width: 9.375rem;
    /* display: inline-block; */
    float: right;
    margin-top: 2.5rem;
}
.main .project {
    border: 2px solid violet;
    margin-top: 1.25rem;
    width: 100%;
    height: auto;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
}
.main .project .one  {
    border: 4px solid blue;
    width: 47%;
    height: 50rem;
}
.main .project .one .image {
    border: 1px solid yellowgreen;
    width: 100%;
    height: 46.875rem;
}

.main .project .two  {
    border: 4px solid red;
    width: 47%;
    height: 43.75rem;
}

.main .project .two .image {
    border: 1px solid yellowgreen;
    width: 100%;
    height: 40.625rem;
}
.main .project .three  {
    border: 4px solid blue;
    width: 47%;
    height: 50rem;
    position: relative;
    bottom: 3.125rem;
}

.main .project .three .image {
    border: 1px solid yellowgreen;
    width: 100%;
    height: 46.875rem;
}
.main .project .four  {
    border: 4px solid red;
    width: 47%;
    height: 43.75rem;
    position: relative;
    top: 3.125rem;
}

.main .project .four .image {
    border: 1px solid yellowgreen;
    width: 100%;
    height: 40.625rem;
}
.house {
    display: inline-block;
    font-size: 17px;
}
.location {
    display: inline-block;
    font-size: 11px;
    margin-left: 1.25rem;
    vertical-align: super;
}
.year {
    float: right;
    font-weight: bold;
    font-size: 17px;
}

@media screen and (max-width: 800px) {
  .main .feat {
    font-size: 35px;
  }
  .main .view {
    margin-top: 2rem;
  }
  .main .project .one {
    width: 49%;
    height: 35rem;
  }
  .main .project .one .image {
    width: 100%;
    height: 32rem;
  }
  .main .project .two {
    width: 49%;
    height: 30rem;
  }
  .main .project .two .image {
    width: 100%;
    height: 27rem;
  }
  .main .project .three {
    width: 49%;
    height: 35rem;
  }
  .main .project .three .image {
    width: 100%;
    height: 32rem;
  }
  .main .project .four {
    width: 49%;
    height: 30rem;
    top: 1.9rem;
  }
  .main .project .four .image {
    width: 100%;
    height: 27rem;
  }






}



@media screen and (max-width: 480px) {
  .main p {
    font-size: 30px;
  }
  .main .view {
    display: none;
  }
  .main .project {
    flex-direction: column;
  }
  .main .project .one {
    width: 100%;
    height: 33rem;
    margin: 25px auto;
  }
  .main .project .one .image {
    width: 100%;
    height: 29rem;
  }
  .main .project .two {
    width: 100%;
    height: 33rem;
    margin: 25px auto;
  }
  .main .project .two .image {
    width: 100%;
    height: 29rem;
  }
  .main .project .three {
    width: 100%;
    height: 33rem;
    margin: 25px auto;
    bottom: 0px;
  }
  .main .project .three .image {
    width: 100%;
    height: 29rem;
  }
  .main .project .four {
    width: 100%;
    height: 33rem;
    margin: 25px auto;
    top: 0px;
  }
  .main .project .four .image {
    width: 100%;
    height: 29rem;
  }
  /* .house {}
  .location {}
  .year {} */
}
</style>