<template>  
  <AppLayout>
    <template #left>
      <router-link to="/">
        <img
          style="width: 50px; margin: 15px;"
          class="logo"
          src="@/assets/logo.png"
        >
      </router-link>
    </template>

    <template #center>
      <AppNav />
    </template>

    <template #right>
      <div>
        <AppButton
          accent
          style="margin: 5px;"
        >
          Заявка на инвестиции
        </AppButton>

        <AppButton style="margin: 5px;">
          Вход
        </AppButton>
      </div>
    </template>
  </AppLayout>
</template>

<script>
import AppButton from '@/components/AppButton';
import AppLayout from '@/components/AppLayout';
import AppNav from '@/components/AppNav';

export default {
  components: {
    AppButton,
    AppLayout,
    AppNav,
  }  
}
</script>
