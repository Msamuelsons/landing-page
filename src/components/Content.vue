<template>
  <div class="grid grid-cols-2 justify-between items-center">
    <section class="content">
      <p>OUR VISION</p>
      <h2>DESIGN</h2>
      <p>
        "Revolutionize your visual content with our cutting-edge AI image
        generation technology. Enhance your brand with unique and captivating
        visuals, made easy with our AI platform."
      </p>
      <ul class="content__options">
        <li><span>Take A Look</span></li>
        <li>3D Art</li>
        <li>AI Image Generation</li>
      </ul>

      <div class="content_boxs grid grid-cols-2 mt-9">
        <div class="box box__one rounded-xl"></div>
        <div class="box box__two rounded-xl"></div>
      </div>
    </section>
    <section class="grid self-end content__global">
      <img src="./../assets/globo.png" alt="" />
    </section>
  </div>
</template>
<style scoped>
.content {
  padding: 70px 80px;
  line-height: 1.1;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: start;
  transform: scale(0.9);
}
.content p:nth-child(1) {
  font-family: "Roboto";
  font-weight: bold;
  font-size: 20px;
  color: #fff;
}
.content h2 {
  font-size: 125px;
  font-family: "Viga";
  color: #fff;
  position: relative;
  left: -10px;
}
.content p:nth-child(3) {
  font-size: 15px;
  font-family: "Roboto";
  color: #fff;
  opacity: 70%;
  width: 26vw;
  line-height: 26px;
  font-weight: 400;
}
.content ul {
  margin-top: 2px;
  margin-left: 16px;
}
.content__options li {
  font-family: "Roboto";
  color: #fff;
  margin-top: 16px;
  list-style: circle;
}
.content__options li span {
  content: "";
  width: 0%;
  height: 2px;
  position: relative;
}
.content__options li span::after {
  content: "";
  width: 90%;
  height: 1px;
  background: #fff;
  position: absolute;
  left: 0;
  bottom: 0;
  margin-bottom: -2px;
}
.box {
  background-color: #fff;
  margin-right: 50px;
  position: relative;
  right: 30px;
}
.box__one {
  width: 260px;
  height: 130px;
}
.box__two {
  width: 200px;
  height: 130px;
}
.content__global {
  position: relative;
  right: 0;
  bottom: 0;
}
</style>
