<template>
  <nav class="AppNav">
    <ul>
      <router-link
        v-for="(navItem, index) of navItems"
        :key="index"
        tag="li"
        :to="navItem.to"
      >
        <span class="text">
          {{ navItem.text }}
        </span>
      </router-link>
    </ul>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      navItems: [
        { text: 'Главная', to: '/' },
        { text: 'О нас', to: '/about' },
        { text: 'Как получить инвестиции', to: '/how' },
        { text: 'Инвесторам', to: '/investors' },
        { text: 'Статус проектов', to: '/project-status' },
        { text: 'Контакты', to: '/contacts' },
      ],
    }
  }
}
</script>

<style lang="scss" scoped>
nav {
  flex: 1;
  display: flex;
  align-items: flex-start;
  
}

ul {
  flex: 1;
  list-style: none;
  display: flex;
  padding: 0;
  margin: 0;
}

li {
  flex: 1;
  color: #222;
  font-family: 'Roboto Condensed', sans-serif;
  font-size: 22px;
  padding: 30px 10px;
  font-weight: 400;
  text-transform: uppercase;
  border-top: 10px solid transparent;
  cursor: pointer;

  &.router-link-exact-active {
    border-top-color: #222;
  }
}
</style>
