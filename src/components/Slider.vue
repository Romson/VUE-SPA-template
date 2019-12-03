<template>
  <section class="hero-area">
    <div class="container">

      <div class="row">
        <div class="col hero-content">
          <h1>Lorem ipsum dolor sit amet sed do eiusmod.</h1>
          <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium.
          </p>
          <div class="hero-form">
            <form action="">
              <div class="form-group">
                <input type="text" class="form-control" placeholder="Enter your email address">
                <button class="submit-btn btn-primary">Get Started</button>
              </div>
              <p class="form-text">Lorem ipsum? <a href="" class="link">Sign In</a></p>
            </form>
          </div>
        </div>

        <div class="col hero-image">
          <img src="../assets/img/hero-image.png" alt="">
        </div>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: 'Slider'
}
</script>

<style lang="scss" scoped>
  .hero-area {
    padding: 115px 0 110px;
  }
  .hero-content {
    text-align: left;
  }
</style>