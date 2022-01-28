<template>
  <BoardView />
</template>

<script>
import { defineComponent } from 'vue'

import BoardView from '../components/BoardView.vue'

export default defineComponent({
  name: 'Board',

  components: {
    BoardView,
  },

})
</script>
