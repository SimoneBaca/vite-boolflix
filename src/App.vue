<script>
import { store } from './store'
import AppContent from './components/App.Content.vue';
import AppHeader from './components/AppHeader.vue';
export default {
  
  components:{
    AppContent,
    AppHeader
  },
  data(){
    return{
      store,
    }
  }
}
</script>
<template lang="">
<div>
  <AppHeader></AppHeader>
<AppContent></AppContent>
</div>
</template>
<style lang="">

</style>