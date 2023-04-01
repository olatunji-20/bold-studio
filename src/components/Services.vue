<template>
    <section>
        <div class="main">
            <p class="ser">SERVICES WE PROVIDE</p>
            <div class="interior">
                <div class="int">
                    <p>01</p>
                    <hr />
                    <p>INTERIOR DESIGN</p>
                    <P>Combining strategy, branding web design and development, we build digital experiences that transform the way people connect and interact with brands.</P>
                </div>
                <div class="int">
                    <p>02</p>
                    <hr />
                    <p>INTERIOR DESIGN</p>
                    <P>Combining strategy, branding web design and development, we build digital experiences that transform the way people connect and interact with brands.</P>
                </div>
                <div class="int">
                    <p>03</p>
                    <hr />
                    <p>INTERIOR DESIGN</p>
                    <P>Combining strategy, branding web design and development, we build digital experiences that transform the way people connect and interact with brands.</P>
                </div>
            </div>
            <div class="project"></div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Services",
    data() {
        return {}
        
    },
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
.main .ser {
    color: green;
    font-size: 40px;
    display: inline-block;
}
.main .interior {
    border: 1px solid orangered;
    height: auto;
    width: 100%;
    padding: 20px 0px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-bottom: 80px;
}
.main .interior .int {
    border: 1px solid brown;
    width: 350px;
    height: 250px;
}
.main .project {
    border: 2px solid violet;
    margin-top: 20px;
    width: 100%;
    height: 700px;
}
</style>