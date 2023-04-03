<template>
    <section>
        <div class="main">
            <p>CLIENTS</p>
            <div class="view"></div>
            <div class="clients">
                <div class="roller">
                    <div class="spons">A</div>
                    <div class="spons">B</div>
                    <div class="spons">C</div>
                    <div class="spons">D</div>
                    <div class="spons">E</div>
                    <div class="spons">F</div>
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
    height: 31.25rem;
    text-align: left;
    padding-bottom: 3.125rem;
    margin: 3.125rem auto 0rem;
}
.main p {
    color: red;
    font-size: 40px;
    display: inline-block;
}
.main .view {
    border: 2px solid fuchsia;
    height: 3.125rem;
    width: 12.5rem;
    /* display: inline-block; */
    float: right;
    margin-top: 2.5rem;
}
.clients {
    border: 1px solid blueviolet;
    width: 100%;
    height: auto;
    margin: 1.25rem auto;
    padding: 1.25rem;
    overflow: hidden;
}
@keyframes scrollee {
  0% {
    right: 0rem;
  }
  13% {
    right: 0rem;
  }
  26% {
    right: 18.75rem;
  }
  39% {
    right: 18.75rem;
  }
  52% {
    right: 37.5rem;
  }
  65% {
    right: 37.5rem;
  }
  78% {
    right: 56.25rem;
  }
  90% {
    right: 56.25rem;
  }
  100% {
    right: 0rem;
  }
}

.clients .roller {
    border: 2px solid red;
    height: auto;
    width: 125rem;
    position: relative;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    animation-name: scrollee;
    animation-duration: 8s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
}
.clients .spons {
    border: 1px solid black;
    height: 15.625rem;
    width: 15.625rem;
}
</style>