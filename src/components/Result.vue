<template>
  <v-card class="mx-auto text-center rounded-xl child" min-width="320" outlined>
    <v-card-text>
      <div class="text-uppercase caption">
        IP Address
      </div>
      <p class="text-h6 font-weight-black">192.212.174.101</p>
      <div class="text-uppercase caption">
        Location
      </div>
      <p class="text-h6 font-weight-black">Brooklyn, NY 10001</p>
      <div class="text-uppercase caption">
        Timezone
      </div>
      <p class="text-h6 font-weight-black">UTC-05:00</p>
      <div class="text-uppercase caption">
        ISP
      </div>
      <p class="text-h6 font-weight-black">SpaceX Starlink</p>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  name: 'Result',
}
</script>

<style scoped>
.child {
  position: absolute;
  top: 25%;
  left: 50%;
  transform: translate(-50%, 0);
}
</style>
