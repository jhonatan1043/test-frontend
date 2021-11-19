<template>
<div>
   <HeaderComponent></HeaderComponent>
   <HeroComponent></HeroComponent>
</div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HeaderComponent from "@/components/headerComponent.vue"; // @ is an alias to /src
import AsideComponent from "@/components/asideComponent.vue";
import HeroComponent from "@/components/heroComponent.vue";

@Options({
  components: {
    HeaderComponent, 
    AsideComponent,
    HeroComponent
  },
})
export default class Home extends Vue {}
</script>
