<template>
  <nav class="navbar has-shadow">
    <div class="navbar-brand">
      <a class="navbar-item">
        <img src="~/assets/images/catlogo.png" />
      </a>
      <div class="navbar-burger">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>

    <div class="navbar-menu">
      <div class="navbar-start">
        <div class="navbar-item">
          <small>Home</small>
        </div>
      </div>
      <div class="navbar-end">
        <div class="navbar-item has-dropdown is-hoverable">
          <div class="navbar-link">Franco Midence</div>
          <div class="navbar-dropdown">
            <a class="navbar-item">
              <div>
                <span class="icon is-small">
                  <i class="fa fa-user-circle-o"></i>
                </span>
                Profile
              </div>
            </a>
            <a class="navbar-item">
              <div>
                <span class="icon is-small">
                  <i class="fa fa-bug"></i>
                </span>
                Report a bug
              </div>
            </a>
            <a class="navbar-item">
              <div>
                <span class="icon is-small">
                  <i class="fa fa-sign-out"></i>
                </span>
                Sign out
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {}
</script>

<style scoped>
.is-primary {
  background-image: url('https://media.giphy.com/media/VOPK1BqsMEJRS/giphy.gif');
  background-repeat: repeat-x repeat-y;
}

.button:hover {
  background-color: aquamarine;
}
</style>
