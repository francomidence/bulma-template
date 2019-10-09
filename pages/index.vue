<template>
  <div>
    <!-- <login /> -->
    <!-- <div class="columns">
      <div class="column">
        <div class="card">
          <header class="card-header">Card header</header>
          <div class="card-conent">Card content</div>
          <footer class="card-footer">Card footer</footer>
        </div>
        First column
      </div>
      <div class="column">Second column</div>
      <div class="column">Third column</div>
    </div>
    <button class="button is-primary is-loading">Button</button>
    <div class="card">
      <header class="card-header">Card header</header>
      <div class="card-conent">Card content</div>
      <footer class="card-footer">Card footer</footer>
    </div>-->
    <NavBar />
    <Main />
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import Main from '@/components/Main.vue'
export default {
  components: {
    NavBar,
    Main
  }
}
</script>

<style lang="sass"></style>
