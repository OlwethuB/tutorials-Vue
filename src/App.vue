<template>
  <NavBarComp/>
  <router-view/>
  <FooterComp/>
</template>

<script>
import NavBarComp from './components/NavBar.vue';
import FooterComp from './components/Footer.vue';


export default {

  components: {NavBarComp,FooterComp}

}
</script>
