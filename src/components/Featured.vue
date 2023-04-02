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
    margin: 50px auto;
    padding: 80px 0px;
    text-align: left;
}
.main .feat {
    color: lightcoral;
    font-size: 40px;
    display: inline-block;
}
.main .view {
    border: 2px solid fuchsia;
    height: 50px;
    width: 150px;
    /* display: inline-block; */
    float: right;
    margin-top: 40px;
}
.main .project {
    border: 2px solid violet;
    margin-top: 20px;
    width: 100%;
    height: auto;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
}
.main .project .one  {
    border: 1px solid blue;
    width: 47%;
    height: 800px;
}
.main .project .one .image {
    border: 1px solid yellowgreen;
    width: 100%;
    height: 750px;
}

.main .project .two  {
    border: 1px solid red;
    width: 47%;
    height: 700px;
}

.main .project .two .image {
    border: 1px solid yellowgreen;
    width: 100%;
    height: 650px;
}
.main .project .three  {
    border: 1px solid blue;
    width: 47%;
    height: 800px;
    position: relative;
    bottom: 50px;
}

.main .project .three .image {
    border: 1px solid yellowgreen;
    width: 100%;
    height: 750px;
}
.main .project .four  {
    border: 1px solid red;
    width: 47%;
    height: 700px;
    position: relative;
    top: 50px;
}

.main .project .four .image {
    border: 1px solid yellowgreen;
    width: 100%;
    height: 650px;
}
.house {
    display: inline-block;
    font-size: 17px;
}
.location {
    display: inline-block;
    font-size: 11px;
    margin-left: 20px;
    vertical-align: super;
}
.year {
    float: right;
    font-weight: bold;
    font-size: 17px;
}
</style>