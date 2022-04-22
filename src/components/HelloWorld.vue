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
           <div class="col-12 name">
          <h1>Claudia</h1>
          <h1>Purdiaková</h1>
          <h4>Welcome to my portfolio</h4>
        </div>
          <div class="break3"></div>

            <div class="col-12 displayPhotos">
            <div class="col-12 displayPhotos">
              <div class="col-6 me">
                <img
                  src="../assets/photo_web/me/DSC_1339.jpg"
                  height="95%"
                  width="100%"
                  alt=""
                />
              </div>
              <div class="col-6 me">
                <img
                  src="../assets/photo_web/me/DSC_1383.jpg"
                  height="95%"
                  width="90%"
                  alt=""
                />
              </div>
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
        <div class="col-4 choose">
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
  .displayPhotos {
  display: flex;
  justify-content: center;
  align-items: center;
}
.me{
  padding-bottom: 60px;
}
.break3{
  height: 150px;
}
h1 {
  font-size: 180px;
}
.border {
  border: white 1px solid;
  height: 820px;
  display: flex;
}
.border2 {
  height: 820px;
  display: flex;
}
.border2 ::-webkit-scrollbar { 
    display: none;  /* Safari and Chrome */
}
.border h4 {
  font-size: 50px;
  padding-left: 40px;
}
.name {
  padding-top: 100px;
  padding-left: 30px;
}

.header {
  height: 60px;
  display: flex;
  padding-top: 20px;
}
.some {
  display: flex;
  text-align: center;
}
.break {
  height: 130px;
}
.video {
  background-color: grey;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
.footer{
  display: flex;
  text-align: center;
  height: 57px;
  font-weight: 300;
}
.footerNav{
  display: flex;
  justify-content: center;
}
.choose{
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 18px;
}
.firstBorder{
  margin: 30px 0px;
  display: flex;
  align-items: center;
  justify-content: center;
}
@media screen and (max-width: 480px) {
  h1 {
    font-size: 65px;
    text-align: center;
    margin-left: -20px;
  }
  .name h4{
    font-size: 40px;
    text-align: center;
    margin-left: -60px;
  }
  .header{
    text-align: center;
  }
  .border{
    height: 500px;
  }
  .free{
    display: none;
  }
  .some p{
    text-align: center;
  }
  p{
    font-size: 14px;
  }
}


.nav-link {
  display: inline-block;
  position: relative;
  color: white;
  text-decoration: none;
}

.nav-link:after {
  content: '';
  position: absolute;
  width: 100%;
  transform: scaleX(0);
  height: 2px;
  top: 0;
  left: 0;
  background-color: white;
  transform-origin: bottom right;
  transition: transform 0.25s ease-out;
}

.nav-link:hover:after {
  transform: scaleX(1);
  transform-origin: bottom left;
}
.nav-link:hover{
  color: white;
}
.nav-link2:hover{
  color: white;
}

.fb img, .ig:hover {
 transition: transform .2s; /* Animation */
}
.fb img:hover, .ig img:hover {
    transform: scale(1.3);
}
.me img {
  transition: all 0.2s;
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
}
.me img {
  filter: grayscale(100%);
  -webkit-filter: grayscale(100%);
  -moz-filter: grayscale(100%);
}
.me img:hover {
  filter: grayscale(0%);
  -webkit-filter: grayscale(0%);
  -moz-filter: grayscale(0%);
  transform: scale(1.01);
  -webkit-transform: scale(1.01);
  -moz-transform: scale(1.01);
}

</style>
