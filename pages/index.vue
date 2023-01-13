<template>
  <div>
  <Tutorial />
  <Otro :msg="'Blue'" />
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
