<script>
export default {
      data() {
            return {
                  message: 'La mia prima app con Vite!'
            }
      }
}
</script>

<template>
      <h1>
            {{ message }}
      </h1>
</template>

<style scoped>
h1 {
      position: absolute;
      top: 50%;
      left: 50%;
      translate: -50% -50%;
      background-color: rgba(148, 146, 146, 0.5);
}
</style>