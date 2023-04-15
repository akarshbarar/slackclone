<template>
    <div>
        <div class="jumbotron bg-primary text-white text-center">
          <h2 class="lead display-3">
            #SLACK#
          </h2>
          <p>Realtime Communication at it's Best</p>
        </div>
        <div class="container-fluid">
          <div class="row">
            <div class="col text-center mt-5">
              <button class="btn btn-outline-danger btn-l">
                Login with Google
              </button>
            </div>
          </div>
          <div class="row">
            <div class="col text-center mt-5">
              <button class="btn btn-outline-info btn-l">
                Login with Twitter
              </button>
            </div>
          </div>
        </div>
    </div>
</template>
<script>
export default {
  name: 'Login',
};
</script>
<style>
  .btn, .jumbotron {
      border-radius: 0px;
  }
</style>
