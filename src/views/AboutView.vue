<template>
  <div class="name">About Us!!</div>

  <div class="media">
    <div class="image-block">
      <img src="@/assets/bubble2.jpg" alt="" class="boba2" />
    </div>

    <div class="about">
      <p>
        Our mission is to create high quality and fresh drinks for everyone.
      </p>
      <p>
        We aren't just a bubble tea shop, were a place for everyone to come
        together and enjoy themselves.
      </p>
      <p>
        We constantly update our menu with new flavors and combinations, so that
        you get a chance to try something new every time you come in!
      </p>
      <p>
        Our tea is freshly brewed in house and we aim to make every cup perfect.
        If it is not to your liking we will always re-make it for you.
      </p>
    </div>
  </div>

  <div class="statement">
    <div class="message">
      <p>
        We care about environment. We take pride in using eco-friendly and
        recycled material. That's not all!! Part of our proceeds go towards
        non-profit organizations that help out the planet.
      </p>
    </div>
  </div>
</template>

<script>
</script>

<style lang="scss">
@import url(//fonts.googleapis.com/css?family=Lato:300:400);

.name {
  /* From https://css.glass */
  background: rgba(255, 255, 255, 0.25);
  border-radius: 15px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(8.5px);
  -webkit-backdrop-filter: blur(8.5px);
  font-family: "Lato", sans-serif;
  font-weight: 300;
  font-size: 48px;
  letter-spacing: 2px;
}

.boba2 {
  padding: 20px;
  margin: 100px;
  width: 350px;
  height: auto;
  @media (min-width: "1080px") {
    width: 500px;
  }
  @media (min-width: "600px") {
    width: 425px;
  }
}

.media {
  overflow: hidden;
  position: relative;
  top: -45px;
  display: flex;
  align-items: center;
  justify-content: center;
  p {
    font-size: 14px;
    max-width: 350px;
  }
  @media (min-width: "600px") {
    .about {
      p {
        font-size: 18px;
        max-width: 425px;
      }
    }
  }
  @media (min-width: "1080px") {
    .about {
      p {
        position: relative;
        left: -20px;
        font-size: 22px;
      }
    }
  }
}

.statement {
  overflow: hidden;
  position: relative;
  top: -60px;
  display: flex;
  align-items: center;
  justify-content: center;
  p {
    font-size: 14px;
    max-width: 350px;
  }
  @media (min-width: "600px") {
    .message {
      p {
        font-size: 18px;
        max-width: 425px;
      }
    }
  }
  @media (min-width: "1080px") {
    .message {
      p {
        position: relative;
        left: -20px;
        font-size: 22px;
        max-width: 750px;
      }
    }
  }
}

@media screen and (max-width: 1080px) {
  .media {
    flex-direction: column;
    align-content: center;
    justify-content: center;
  }
}
</style>
