<template>
    <section>
        <div class="main">
            <p>CLIENTS</p>
            <div class="view">              
              <h4>VIEW ALL WORK</h4>
                <div class="arrow">
                  <img src="../assets/arrow.png" class="logoo" />
                </div>
            </div>
            <div class="clients">
                <div class="roller">
                    <div class="spons">
                      <img src="../assets/ad.png" class="sponsor"/>
                    </div>
                    <div class="spons">
                      <img src="../assets/copysmith.png" class="sponsor"/>
                    </div>
                    <div class="spons">
                      <img src="../assets/algorand.png" class="sponsor"/>
                    </div>
                    <div class="spons">
                      <img src="../assets/google.png" class="sponsor"/>
                    </div>
                    <div class="spons">
                      <img src="../assets/copysmith.png" class="sponsor"/>
                    </div>
                    <div class="spons">
                      <img src="../assets/algorand.png" class="sponsor"/>
                    </div>
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
    /* border: 2px solid peru; */
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
    /* border: 2px solid fuchsia; */
    height: 3.125rem;
    width: 12.5rem;
    /* display: inline-block; */
    float: right;
    margin-top: 2.5rem;
}
.main .view h4 {
    line-height: 0px;
    position: relative;
    /* top: 0.3125rem; */
    display: inline-block;
  }
  .logoo {
    width: 100%;
    height: 100%;
    object-fit: contain;
  }
  .main .view .arrow {
    /* border: 1px solid red; */
    width: 12px;
    height: 12px;
    margin-left: 7px;
    display: inline-block;
  }
.clients {
    /* border: 1px solid blueviolet; */
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
    /* border: 2px solid red; */
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
.clients .roller .spons {
    border: 1px solid black;
    height: 15.625rem;
    width: 15.625rem;
}
.clients .roller .spons .sponsor {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
@media screen and (max-width: 800px) {
  .main p {
    font-size: 35px;
  }
  .main .view {
    margin-top: 2rem;
  }
}



@media screen and (max-width: 480px) {
  .main p {
    font-size: 30px;
  }
  .main .view {
    height: 2rem;
    width: 10rem;
    margin-top: 1.8rem;
  }
}
</style>