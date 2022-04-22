<template>
  <div class="container">
    <div class="row">
      <div id="navbar" class="col-12  header">
        <div class="col-2">
          <router-link class="nav-link2" to="/">claudiapur</router-link>
        </div>
        <div class="col-8 "></div>
        <div class="col-2  some">
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
          
              <div class="break"></div>
          <div class="col-12 displayPhotos">
             <div class="col-5 nameImage">
               <p>CD cover <br> Connected</p>
              </div>
              <div class="col-7 cd_cover nameImage">
                <img src="../assets/photo_web/design_page/cd_cover.png" height="95%" width="90%" alt=""/>
              </div>
              </div>
              <div class="break"></div>
              <br>

              <div class="col-12 displayPhotos">
             <div class="col-1">
              </div>
              <div class="col-8 ticket_final">
                <img src="../assets/photo_web/Beckov/ticket_final-2.jpg" height="95%" width="90%" alt=""/>
              
              </div>
              <div class="col-3 nameImage">
                <p>Theatre tikcket for <br> Giselle ballet</p>
              </div>
              </div>
              <div class="break"></div>

              <div class="col-12 displayPhotos">
                <div class="col-1"></div>
             <div class="col-2 semotus_logo_left">
               <img src="../assets/photo_web/design_page/paper-stickers-mockup.png" height="95%" width="90%" alt=""/>
             </div>
             <div class="col-3 nameImage">
               <p>logo & stickers for <br> job portal called SEMOTUS </p>
             </div>
              <div class="col-5 semotus_logo_right ">
              <img src="../assets/photo_web/design_page/semotus_logo.png" height="95%" width="90%" alt=""/>
              </div>
              <div class="col-1">
              </div>
              </div>
              <div class="break"></div>

              <div class="col-12 displayPhotos">
             <div class="col-1">
              </div>
              <div class="col-5 trapholt">
                <img src="../assets/photo_web/design_page/mockups/mac-pro-2019-mockup.jpg"  width="90%" alt=""/>
              </div>
              <div class="col-6 trapholt nameImage">
                <p>Design of a website for TRAPHOLT museum </p>
                <img src="../assets/photo_web/design_page/mockups/mac-pro-2019-mockup2.jpg"  width="70%" alt=""/>
              </div>
              </div>


               <div class="break"></div>

              <div class="col-12 displayPhotos">
              <div class="col-5 trapholt nameImage">
                <p>Design of a website for TRAPHOLT museum </p>
                <img src="../assets/photo_web/design_page/trapholt_logo.jpg"  width="70%" alt=""/>
              </div>
              <div class="col-7 trapholt nameImage">
                <img src="../assets/photo_web/design_page/mockups/reusable-bag-top-view-mockup(1).png"  width="90%" alt=""/>

              </div>
              </div>


               <div class="break"></div>

              <div class="col-12 displayPhotos">
              <div class="col-6 win_95_left">
                <img src="../assets/photo_web/design_page/mockups/imac-screen-mockup.png"  width="90%" alt=""/>
              </div>
              <div class="col-6 win_95_right nameImage">
                <p>Design of a website for computer retail e-shop </p>
                <img src="../assets/photo_web/design_page/mockups/imac-screen-mockup2.jpg"  width="80%" alt=""/>

              </div>
              </div>

 <div class="break"></div>

              <div class="col-12 displayPhotos">
                <div class="col-3"></div>
                <div class="col-1 sideTextRotate">
                  <p>Halloween party poster</p>
                </div>
              <div class="col-5 poster">
                <img src="../assets/photo_web/design_page/shutterstock_741720202.jpg"  width="90%" alt=""/>
              </div>
              <div class="col-3">
                </div>
              </div>
 <div class="breakDown"></div>

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
        <div class="col-4 choose">
          <p>scroll down and enjoy the journey</p>
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
.break{
  height: 250px;
}

.breakDown{
  height: 100px;
}
.break2{
  height: 50px;
}
 .scroll-div{
    overflow: hidden;
    overflow-y: scroll;
  }
  .scroll-object{
    color: white;
    font-size: 15px;
  }
.nameImage {
  text-align: center;
}
.displayPhotos {
  display: flex;
  justify-content: center;
  align-items: center;
}
.trapholt, .win_95_left, .win_95_right{
  text-align: center;
}
.container ::-webkit-scrollbar { 
    display: none; 
}
.cd_cover{
  padding-top: 50px;
}
.semotus_logo_left{
  padding-bottom: 20%;
  text-align: center;
}
.semotus_logo_right{
  text-align: center;
}
.win_95_left{
  padding-bottom: 150px;
}
.sideTextRotate p {
  writing-mode: vertical-rl;
  text-orientation: mixed;
-webkit-transform: rotate(-180deg);
}
</style>
