<template>
  <div class="contPerson">
    <div class="singlePer">
      <img class="rounded-image" :src="avatar" alt="avatar" />
    </div>
    <p class="pseldo">{{ name }}</p>
  </div>
</template>

<script lang="ts">
export default {
  props: {
    name: String,
    avatar: String,
  },
}
</script>