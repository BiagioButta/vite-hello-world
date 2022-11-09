<template>
<!-- qui uso l'html  -->
<div>

  <AppTitle/>

</div>
<div>

<AppHero/>

</div>
</template>

<script>
// qui uso il js 

import AppTitle from './components/AppTitle.vue'; //lo devo usare dopo importato
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppTitle,
    AppHero
  }
}

</script>

<style>
/* qui uso il css  */

</style>