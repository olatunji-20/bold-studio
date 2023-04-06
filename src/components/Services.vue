<template>
    <section>
        <div class="main">
            <p class="ser">SERVICES WE PROVIDE</p>
            <div class="interior">
                <div class="int">
                    <p>01</p>
                    <hr />
                    <p>INTERIOR DESIGN</p>
                    <P class="com">Combining strategy, branding web design and development, we build digital experiences that transform the way people connect and interact with brands.</P>
                </div>
                <div class="int">
                    <p>02</p>
                    <hr />
                    <p>INTERIOR DESIGN</p>
                    <P class="com">Combining strategy, branding web design and development, we build digital experiences that transform the way people connect and interact with brands.</P>
                </div>
                <div class="int">
                    <p>03</p>
                    <hr />
                    <p>INTERIOR DESIGN</p>
                    <P class="com">Combining strategy, branding web design and development, we build digital experiences that transform the way people connect and interact with brands.</P>
                </div>
            </div>
            <div class="project">
                <div class="one"></div>
                <div class="two"></div>
            </div>
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
    margin: 3.25rem auto;
    padding: 5rem 0rem;
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
    padding: 1.25rem 0rem;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-bottom: 5rem;
}
.main .interior .int {
    border: 1px solid brown;
    width: 21.875rem;
    height: 15.625rem;
}
.main .interior .int .com {
    font-size: 14px;
    line-height: 18px;
}
.main .project {
    border: 2px solid violet;
    margin-top: 1.25rem;
    width: 100%;
    height: auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
.main .project .one {
    border: 1px solid blue;
    width: 48%;
    height: 40.625rem;
}
.main .project .two {
    border: 1px solid rebeccapurple;
    width: 43%;
    height: 34.375rem;
    margin-top: 21.875rem;
}

@media screen and (max-width: 800px) {
    .main .project .one {
        height: 33rem;
    }
    .main .project .two {
        height: 29rem;
    }
}


@media screen and (max-width: 480px) {
    .main .interior {
        flex-wrap: wrap;
    }
    .main .interior .int {
        width: 100%;
    }
    .main .project {
        flex-direction: column;
    }
    .main .project .one {
        width: 100%;
    }
    .main .project .two {
        width: 100%;
        margin-top: 40px;
    }
}



</style>