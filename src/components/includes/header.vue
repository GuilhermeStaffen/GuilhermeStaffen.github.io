<template>
  <section class="section">
    <div class="container-fliud">
      <img
        alt="Guilherme Staffen"
        class="rounded-circle"
        id="imgCircle"
        src="../../assets/guilherme.jpeg"
      />
      <h1>Guilherme Staffen</h1>
      <p class="occupation">
        Senior Test Automation Developer at
        <a href="https://compass.uol/pt/home/" target="_blank"
          >Compass.uol</a
        >
      </p>
      <div class="test-case">
        <a href="https://github.com/GuilhermeStaffen/" target="_blank" ><img src="../../assets/github.svg" /></a>
        <a href="https://www.linkedin.com/in/guilhermestaffen/" target="_blank" ><img src="../../assets/linkedin-in.svg" /></a>
      </div>
      <div class="test-case">
        <p><strong>Given</strong> there is a Guilherme's website</p>
        <p><strong>When</strong> I access the website</p>
        <p><strong>Then</strong> the home page is visible</p>
      </div>
    </div>
  </section>
</template>

<style lang="css" scoped>
.section {
  padding-top: 10%;
  min-height: 100vh;
  background-color: #181818;
}

#imgCircle {
  max-width: 300px;
  max-height: 300px;
}

.occupation {
  font-size: 26px;
}

.test-case {
  margin-top: 3%;
}

.test-case > p {
  left: 0%;
  font-size: 18px;
}

.test-case img {
  left: 0%;
  max-height: 80px;
  max-width: 80px;
  padding: 10px;
}
</style>
