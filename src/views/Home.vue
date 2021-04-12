<template>
  <div>
    <Hello />
    <BuyTrade />
  </div>
</template>

<script>
// @ is an alias to /src
import Hello from '@/components/Home/Hello.vue'
import BuyTrade from '@/components/Home/BuyTrade.vue'

export default {
  name: 'Home',
  components: {
    Hello,
    BuyTrade,
  }
}
</script>
