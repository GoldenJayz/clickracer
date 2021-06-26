<template>
  <div>
      <button @click="ging++">click here</button>
      {{ ging }}
      <p>
        {{ ouser }}
      </p>
  </div>
</template>

<script>

export default {
    data: function() {
        return {
            ging: 0
        }
    }
}
//make a program that makes a counter for each time you click a button
</script>

<style scoped>

</style>