<template>
  <div class="menu">
    <div class="newOne">
      <div>Livraison en cours :</div>
      <div>Restaurant : Chez Benoit </div>
      <div>Livraison : Pizza 4 fromages</div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HomeProp from '@/components/home/HomeProp.vue';

@Options({
  components: {
    HomeProp
  },
})

export default class HomeMenu extends Vue {
valides!: {
  Nom: string;
  Origine: string;
  Destination:string;
}
  AdresseRestau!: string;
  AdresseDestination!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.menu {
  display: inline-block;
}
.newOne {
  
}
</style>
