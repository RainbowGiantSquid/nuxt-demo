<template>
  <div class="flex">
    {{ title }}
    <div class="flex-1">
      <Nuxt />
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainLayout',

  data () {
    return {
      title: 'I am a title'
    }
  }
}
</script>
