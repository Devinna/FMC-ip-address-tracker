<template>
  <div>
    <v-img src="../assets/pattern-bg.png" class="pa-4">
      <h2 class="white--text text-center font-weight-regular">
        IP Address Tracker
      </h2>
      <SearchBox />
      <Result/>
    </v-img>
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
