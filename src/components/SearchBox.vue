<template>
  <v-form class="mt-5">
    <v-text-field
      v-model="ip"
      label="Search for any IP address or domain"
      type="text"
      single-line
      solo
      :append-icon="'mdi-chevron-right'"
      @click:append="searchIP"
      class="text-subtitle-1 rounded-lg cursor_pointer"
    ></v-text-field>
  </v-form>
</template>

<script>
export default {
  name: 'SearchBox',
  props: {
    ip: String,
  },
  methods: {
    searchIP() {
      console.log('click')
    },
  },
}
</script>

<style>
.cursor_pointer input{ 
  cursor:pointer;
}
</style>
