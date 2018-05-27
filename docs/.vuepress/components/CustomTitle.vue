<template>
  <h1>{{ customText }}</h1>
</template>

<script>
export default {
  props: {
    customText: {
      type: String,
      default: 'me'
    }
  }
}
</script>

