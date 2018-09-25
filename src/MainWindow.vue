<template>
  <Window title="google_task_client" width="400" height="100" margined v-on:close="exit">
    <Box>
      <Text>Welcome to your Vuido application!</Text>
    </Box>
  </Window>
</template>

<script>
export default {
  methods: {
    exit() {
      this.$exit();
    }
  }
}
</script>
