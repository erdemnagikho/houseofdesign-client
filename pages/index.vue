<template>
  <div></div>
</template>

<script>
export default {
  beforeMount() {
    this.$router.push({
      name: 'designs.search'
    });
  }
};
</script>
