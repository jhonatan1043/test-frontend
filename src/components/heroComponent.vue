<template>
  <div class="containers">
    <div class="container__flex">
      <AsideComponent></AsideComponent>
      <CardsComponent></CardsComponent>
    </div>
  </div>
</template>

<script>
import AsideComponent from "@/components/asideComponent.vue";
import CardsComponent from "@/components/cardsComponent.vue";

export default {
  components: {
    AsideComponent,
    CardsComponent,
  },
};
</script>

<style scoped>
.container__flex {
  display: flex;
  /* align-items: center; */
  /* justify-content: space-between; */
}
</style>
