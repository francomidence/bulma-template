<template>
  <section class="section">
    <div class="columns">
      <div class="column is-4-tablet is-3-desktop is-2-widescreen">
        <Menu />
      </div>
      <div class="column">second column</div>
    </div>
  </section>
</template>

<script>
import Menu from '@/components/Menu.vue'
export default {
  components: {
    Menu
  }
}
</script>

<style lang="scss" scoped></style>
