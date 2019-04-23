<template>
  <section class="SectionHeader">
    <div class="left-block">
      <div class="telephone">
        8 (800) 777-77-77
      </div>
      <ul>
        <li
          v-for="(menuItem, index) of menuItems"
          :key="index"
        >
          {{ menuItem.text }}
        </li>
      </ul>
    </div>
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
        style="width: 1200px;"
      >
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      menuItems: [
        { text: 'проекты'},
        { text: 'показатели'},
        { text: 'преимущества'},
        { text: 'новости'},
      ],
    }
  }
}
</script>


<style lang="scss" scoped>
section {
  display: flex;
}

.logo {
  width: 100px;
  height: 100px;
}

.title-block {
  z-index: 2;
  padding-top: 100px;
}

.title {
  color: #0c81fd;
  font-family: "Cocogoose Compressed Trial - Regula";
  font-size: 200px;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: -3.5px;
  margin: 0;
}

.subtitle {
  color: #222222;
  font-family: "Cocogoose Compressed Trial - Regula";
  font-size: 50px;
  font-weight: bold;
  // line-height: 90px;
  text-transform: uppercase;
  letter-spacing: -0.8px;
  margin: 0;
}

.subtitle span {
  color: #0c81fd;
  letter-spacing: -0.8px;
}

.picture {
  position: relative;
  bottom: 70px;
  z-index: -1;
}

.left-block {
  padding-top: 150px;
  margin-right: 50px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.telephone {
  background: #222;
  color: white;
  padding: 20px;
}

ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

li {
  color: #b3b3b3;
}

</style>
