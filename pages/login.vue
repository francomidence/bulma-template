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
                  src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/5984f9a3-7c06-4d9a-80e0-e001c8bf7a32/dcae6xw-4a7d507c-e716-4380-a776-865e4240b22e.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzU5ODRmOWEzLTdjMDYtNGQ5YS04MGUwLWUwMDFjOGJmN2EzMlwvZGNhZTZ4dy00YTdkNTA3Yy1lNzE2LTQzODAtYTc3Ni04NjVlNDI0MGIyMmUuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.xIHt54V2nxDaNSnJ2BDqhkkGRP6gM_qdtySLPxaMxrU"
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
                <button class="button is-primary">Login</button>
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
  background-image: url('https://media.giphy.com/media/pVGsAWjzvXcZW4ZBTE/giphy.gif');
  background-repeat: repeat-x repeat-y;
}

.button:hover {
  background-color: darkcyan;
}
</style>
