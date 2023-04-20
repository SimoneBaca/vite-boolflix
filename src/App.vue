<script>
import { store } from './store'
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