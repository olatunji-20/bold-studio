<template>
    <section>
        <div class="main">
            <p>FEATURED PROJECTS</p>
            <div class="view"></div>
            <div class="project"></div>
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
.main p {
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
    height: 1200px;
}
</style>