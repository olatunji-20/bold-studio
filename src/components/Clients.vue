<template>
    <section>
        <div class="main">
            <p>CLIENTS</p>
            <div class="view"></div>
            <div class="clients">
                <div class="roller">
                    <div class="spons"></div>
                    <div class="spons"></div>
                    <div class="spons"></div>
                    <div class="spons"></div>
                    <div class="spons"></div>
                </div>
            </div>
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
    width: 93%;
    height: 500px;
    text-align: left;
    padding-bottom: 50px;
    margin: 50px auto 0px;
}
.main p {
    color: red;
    font-size: 45px;
    display: inline-block;
}
.main .view {
    border: 2px solid fuchsia;
    height: 50px;
    width: 200px;
    /* display: inline-block; */
    float: right;
    margin-top: 40px;
}
.clients {
    border: 1px solid blueviolet;
    width: 100%;
    height: auto;
    margin: 20px auto;
    padding: 20px;
    overflow: auto;
}
.clients .roller {
    border: 2px solid red;
    height: auto;
    width: 1500px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    overflow: hidden;
}
.clients .spons {
    border: 1px solid black;
    height: 250px;
    width: 250px;
}
</style>