<template>
  <v-btn @click="onClick()" class="ma-2" dark>
    <v-icon>
      mdi-chevron-right
    </v-icon>
  </v-btn>
</template>

<script>
export default {
  name: 'Button',
  methods: {
    onClick() {
      console.log('click')
    },
  },
}
</script>
