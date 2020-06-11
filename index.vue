<template>
  <div>
    <v-alert :hidden="error" type="error">Yes</v-alert>
    <v-btn @click="error = !error">Yee</v-btn>
  </div>  
</template>

<script>
export default {
  data: () => ({
    error: false
  })
}
</script>
