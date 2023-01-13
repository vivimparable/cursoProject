<template>
  <div>
  <Tutorial />
  <Otro :msg="'Blue'" />
  <h1>Hello</h1>
</div>
</template>

<script>
import Otro from '@/components/OtroComp..vue'
export default {
  name: 'IndexPage',
  components:{
    Otro
  }
}
</script>
