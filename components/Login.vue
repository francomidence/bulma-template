<template>
  <section class="hero is-primary is-fullheight">
    <div class="hero-body">
      <div class="container">
        <div class="columns is-centered">
          <div class="column is-5-tablet is-4-desktop is-3-widescreen">
            <form class="box box-color">
              <div class="field has-text-centered">
                <img
                  width="170"
                  src="https://99designs-blog.imgix.net/blog/wp-content/uploads/2018/11/attachment_78456430-e1541654366936.jpeg?auto=format&q=60&w=1000&h=750&fit=crop&crop=faces"
                />
              </div>
              <div class="field">
                <label class="label">Email</label>
                <div class="control has-icons-left">
                  <span class="icon is-small is-left">
                    <i class="fa fa-envelope"></i>
                  </span>
                  <input
                    type="email"
                    class="input"
                    placeholder="e.g. alexjohnson@gmail.com"
                  />
                </div>
              </div>
              <div class="field">
                <label class="label">Password</label>
                <div class="control has-icons-left">
                  <span class="icon is-small is-left">
                    <i class="fa fa-lock"></i>
                  </span>
                  <input
                    required
                    type="password"
                    class="input"
                    placeholder="*********"
                  />
                </div>
              </div>
              <div class="field">
                <label class="checkbox">
                  <input type="checkbox" required />
                  Remember me
                </label>
              </div>
              <div class="field">
                <button class="button is-success">Login</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
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
