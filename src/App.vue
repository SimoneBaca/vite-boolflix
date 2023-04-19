<script>
import { store } from './components/store'
import AppContent from './components/App.Content.vue';
export default {
  
  components:{
    AppContent,
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

<AppContent></AppContent>
</div>
</template>
<style lang="">

</style>