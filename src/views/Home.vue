<template>
  <div class="home">
    <son :msg="haha"></son>
  </div>
</template>

<script >
import Son from '@/components/Son.vue'
export default {
  name:'home',
  components:{
    Son
  },
  data(){
    return{
      haha:'string'
    }
  }
  
}
</script>
