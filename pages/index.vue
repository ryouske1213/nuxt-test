<template>
<div>
  {{$store.state.store.count}}
  <p>========================</p>
  <div>
    {{$store.state.game.count}}
  </div>
</div>
</template>

<script>
import Vue from 'vue'
import {mapState} from 'vuex'

export default Vue.extend({

  computed: mapState(['count'])
})
</script>

q