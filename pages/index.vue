<template>
  <div class="container-fluid">
    <div class="row">
      <div class="cols">
        <v-card>
          <v-card-title>Dashboard</v-card-title>
        </v-card>
      </div>
    </div>
  </div>
</template>
<script>
// import localforage from 'localforage'
export default {
  layout: 'dashboard'
  // middleware: 'auth'
  // async created () {
  //   const { status, data } = (await this.$axios.get('/initial_fetch')).data
  //   if (status === 1) {
  //     console.log(data)
  //     localforage.setItem('stored:regions', data.regions)
  //     localforage.setItem('stored:cities', data.cities)
  //     localforage.setItem('stored:townships', data.townships)
  //   }
  // }
}
</script>
