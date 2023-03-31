<template>
    <section>
        <div class="main">
            <p>CLIENTS</p>
            <div class="view"></div>
            <div class="clients"></div>
        </div>
    </section>
</template>

<script>
    export default {
        name: "Clients",
        data() {
            return {

            }
        }
    }
</script>

<style scoped>
.main {
    border: 2px solid peru;
    width: 100%;
    height: 500px;
    text-align: left;
    padding: 0px 40px;
}
.main p {
    color: red;
    font-size: 45px;
    display: inline-block;
}
.main .view {
    border: 2px solid fuchsia;
    height: 50px;
    width: 250px;
    /* display: inline-block; */
    float: right;
    margin-top: 40px;
}
.clients {
    border: 1px solid blueviolet;
    width: 100%;
    height: 250px;
    margin: 20px auto;
}
</style>