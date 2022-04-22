<template>
  <div class="container">
    <div class="row">
      <div id="navbar" class="col-12  header">
        <div class="col-2">
          <router-link class="nav-link2" to="/">claudiapur</router-link>
        </div>
        <div class="col-8 "></div>
        <div class="col-2 some">
          <div class="col cv">
            <router-link class="nav-link2" to="/cv">CV</router-link>
          </div>
          <div class="col fb">
            <a target="_blank" href="https://www.facebook.com/klaudia.purdiakova"><img src="../assets/photo_web/icons8-facebook-500.png" width="38%" alt=""></a>
          </div>
          <div class="col ig">
            <a target="_blank" href="https://www.instagram.com/_claudiapur_/"><img src="../assets/photo_web/icons8-instagram-500.png" width="38%" alt=""></a>
          </div>
        </div>
      </div>
      <div class="col-12 scroll-div border">
         <div class="col-12 scroll-object">

              <div class="col-12 displayPhotos">
                <div class="col-12 cvPhoto">
                  <img src="../assets/photo_web/cv-final_Klaudia.png" width="100%" alt="">
                </div>
              </div>

      </div>
      </div>
    </div>
  </div>
  <div class="container">
    <div class="row">
      <div class="col-12 footer">
        <div class="col-4 footerNav">
           <div class="col-4 firstBorder">
          <router-link class="nav-link" to="/photography">photography</router-link>
        </div>
        </div>
        <div class="col-4 choose chooseOne">
          <p>scroll</p>
        </div>
        <div class="col-4 footerNav">
          <div class="col-4 firstBorder">
          <router-link class="nav-link" to="/design">design</router-link>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {};
</script>

<style  lang="scss">
 .scroll-div{
    overflow: hidden;
    overflow-y: scroll;
  }
  .scroll-object{
    color: white;
    font-size: 15px;
  }
 .cvPhoto{
   margin-top: 10px;
   margin-bottom: 10Px;
 }
</style>
