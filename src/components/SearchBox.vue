<template>
  <v-form class="mt-5">
    <v-text-field
      v-model="ip"
      label="Search for any IP address or domain"
      type="text"
      single-line
      rounded
      solo
      :append-icon="'mdi-chevron-right'"
      @click:append="searchIP"
      class="text-subtitle-1"
    ></v-text-field>
  </v-form>
</template>

<script>
import Button from './Button'
export default {
  name: 'SearchBox',
  props: {
    ip: String,
  },
  components: {
    Button,
  },
  methods: {
    searchIP() {
      console.log('click')
    },
  },
}
</script>
