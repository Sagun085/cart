<template>
  <div>
    <base-button @click="updateCounter" />
    {{ count }}
  </div>
</template>

<script>
export default {
  name: "about-page",
  data() {
    return {
      count: 0
    }
  },
  methods: {
    updateCounter() {
      this.count++
    }
  }
}
</script>

<style>

</style>