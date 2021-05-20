<template>
  <div>
    <v-img src="../assets/pattern-bg.png" class="pa-4" min-height="300">
      <h2 class="white--text text-center font-weight-regular">
        IP Address Tracker
      </h2>
      <SearchBox />
    </v-img>
    <Result />
  </div>
</template>

<script>
import SearchBox from './SearchBox'
import Result from './Result'
export default {
  name: 'TheHeader',
  components: { SearchBox, Result },
}
</script>
