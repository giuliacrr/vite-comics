<script>
export default {};
</script>

<template>
  <div>
    <!--Start info section-->
    <div class="info-bg">
      <div class="container">
        <div class="d-flex justify-content-between">
          <div class="d-flex align-items-center">
            <div class="d-flex">
              <!--first column-->
              <div>
                <span class="text-uppercase text-white fw-bold list-title">
                  dc comics</span
                >
                <ul class="text-white fs-6 text-white-50">
                  <li>Characters</li>
                  <li>Comics</li>
                  <li>Movies</li>
                  <li>TV</li>
                  <li>Games</li>
                  <li>Videos</li>
                  <li>News</li>
                </ul>
                <span class="text-uppercase text-white fw-bold list-title">
                  shop</span
                >
                <ul class="text-white fs-6 text-white-50">
                  <li>Shop DC</li>
                  <li>Shop DC Collectibles</li>
                </ul>
              </div>
              <!--second column-->
              <div>
                <span class="text-uppercase text-white fw-bold list-title">
                  dc</span
                >
                <ul class="text-white fs-6 text-white-50">
                  <li>Characters</li>
                  <li>Comics</li>
                  <li>Movies</li>
                  <li>TV</li>
                  <li>Games</li>
                  <li>Videos</li>
                  <li>News</li>
                  <li>News</li>
                  <li>News</li>
                  <li>News</li>
                </ul>
              </div>
              <!--third column-->
              <div>
                <span class="text-uppercase text-white fw-bold list-title">
                  sites</span
                >
                <ul class="text-white fs-6 text-white-50">
                  <li>DC</li>
                  <li>MAD Magazine</li>
                  <li>DC Kids</li>
                  <li>DC Universe</li>
                  <li>DC Power Visa</li>
                </ul>
              </div>
            </div>
          </div>
          <div><img src="../assets/img/dc-logo-bg.png" alt="dclogobg" /></div>
        </div>
      </div>
    </div>
    <!--End info section-->

    <!--Start Sign-up and follow-up section-->
    <div class="sign-n-follow">
      <div class="container">
        <div class="d-flex justify-content-between">
          <div>
            <button type="button" class="btn btn-outline-primary">
              sign-up now!
            </button>
          </div>
          <div class="d-flex align-items-center">
            <span class="text-uppercase text-primary fw-bold me-3"
              >follow us</span
            >
            <img
              class="social-icon"
              src="../assets/img/footer-facebook.png"
              alt="fb"
            />
            <img
              class="social-icon"
              src="../assets/img/footer-twitter.png"
              alt="x"
            />
            <img
              class="social-icon"
              src="../assets/img/footer-youtube.png"
              alt="yt"
            />
            <img
              class="social-icon"
              src="../assets/img/footer-pinterest.png"
              alt="pntr"
            />
            <img
              class="social-icon"
              src="../assets/img/footer-periscope.png"
              alt="ps"
            />
          </div>
        </div>
      </div>
    </div>
    <!--End Sign-up and follow-up section-->
  </div>
</template>

<style lang="scss" scoped>
.info-bg {
  min-height: 300px;
  background-image: url(../assets/img/footer-bg.jpg);
  background-size: cover;
  background-repeat: no-repeat;
}

.list-title {
  margin-left: 32px;
}

ul {
  list-style-type: none;
  margin-top: 5px;
}

.btn {
  color: white;
  text-transform: uppercase;
}
.btn-outline-primary {
  border-radius: 0%;
  border: 3px solid #0c7cec;
}

.sign-n-follow {
  background-color: #303030;
  padding-top: 30px;
  padding-bottom: 30px;
  position: relative;
  margin-top: -75px;
}

.social-icon {
  width: 30px;
  margin-right: 7px;
  margin-left: 7px;
}
</style>
