<template>
  <section>
    <div class="main">
      <p class="ser">SERVICES WE PROVIDE</p>
      <div class="interior">
        <div class="int">
          <p>01</p>
          <hr />
          <p>INTERIOR DESIGN</p>
          <P class="com"
            >Combining strategy, branding web design and development, we build
            digital experiences that transform the way people connect and
            interact with brands.</P
          >
        </div>
        <div class="int">
          <p>02</p>
          <hr />
          <p>INTERIOR DESIGN</p>
          <P class="com"
            >Combining strategy, branding web design and development, we build
            digital experiences that transform the way people connect and
            interact with brands.</P
          >
        </div>
        <div class="int">
          <p>03</p>
          <hr />
          <p>INTERIOR DESIGN</p>
          <P class="com"
            >Combining strategy, branding web design and development, we build
            digital experiences that transform the way people connect and
            interact with brands.</P
          >
        </div>
      </div>
      <div class="project">
        <div class="one">
          <img
            src="../assets/window.png"
            class="service-image"
            loading="lazy"
          />
        </div>
        <div class="two">
          <img
            src="../assets/pillow.png"
            class="service-image"
            loading="lazy"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Services",
  data() {
    return {};
  },
};
</script>

<style scoped>
.main {
  border-top: 2px solid black;
  width: 93%;
  height: auto;
  margin: 3.25rem auto;
  padding: 5rem 0rem;
  text-align: left;
}
.main .ser {
  font-size: 40px;
  display: inline-block;
}
.main .interior {
  height: auto;
  width: 100%;
  padding: 1.25rem 0rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin-bottom: 5rem;
}
.main .interior .int {
  width: 21.875rem;
  height: 15.625rem;
  position: relative;
  cursor: pointer;
  top: 0px;
  transition: 0.4s;
}
.main .interior .int:hover {
  top: 10px;
}
.main .interior .int .com {
  font-size: 14px;
  line-height: 18px;
}
.main .project {
  margin-top: 1.25rem;
  width: 100%;
  height: auto;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.main .project .one {
  width: 48%;
  height: 40.625rem;
}
.main .project .two {
  width: 43%;
  height: 34.375rem;
  margin-top: 21.875rem;
}
.service-image {
  width: 100%;
  height: 100%;
  object-fit: fill;
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