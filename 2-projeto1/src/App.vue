<template>

<div>
<PrimeiroComponente/>
<LyfeCycle/>
</div>

</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LyfeCycle from './components/LyfeCycle.vue'
export default{
  name:'App',
  components:{

    PrimeiroComponente,
    LyfeCycle

  }
}

</script>