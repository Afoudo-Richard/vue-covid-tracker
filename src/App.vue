<template>
<Header></Header>
<div class="container">
  <router-view/>

</div>

</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'

export default {
  name: 'HomeView',
  components: {
    Header
  }
}

</script>


