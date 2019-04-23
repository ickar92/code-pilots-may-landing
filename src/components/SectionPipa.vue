<template>
  <section class="SectionPipa">
    <div class="title-block">
      <p class="title">
        МАИ
      </p>
      <p class="subtitle">
        Международная<br> ассоциация<br> <span>инвесторов</span>
      </p>
    </div>

    <div class="picture">
      <img
        src="@/assets/pic.png"
        style="width: 300px;"
      >
    </div>
  </section>
</template>

<style lang="scss" scoped>
.logo {
  width: 100px;
  height: 100px;
}

.pipa {
  display: flex;
  align-items: center;
}

.title-block {
  z-index: 2;
}

.title {
  color: #0c81fd;
  font-family: "Cocogoose Compressed Trial - Regula";
  font-size: 35px;
  font-weight: 400;
  text-transform: uppercase;
  letter-spacing: -3.5px;
  margin: 0;
}

.subtitle {
  color: #222222;
  font-family: "Cocogoose Compressed Trial - Regula";
  font-size: 80px;
  font-weight: 400;
  line-height: 90px;
  text-transform: uppercase;
  letter-spacing: -0.8px;
}

.subtitle span {
  color: #0c81fd;
  letter-spacing: -0.8px;
}

</style>
