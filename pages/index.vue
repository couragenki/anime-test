<template>
  <div class="wrapper">
    <div class="content hoge1">
      hoge1
    </div>
    <div class="content hoge2">
      hoge2
    </div>
    <div class="movie">
      <p class="animation-text">
        hogehogehogehoge
      </p>
      <video
        autoplay
        muted
        loop
        src="https://www.apple.com/105/media/ww/imac-24/2021/5e004d75-3ad6-4bb9-ab59-41f891fc52f0/anim/display-hero/large_2x.mp4"
      />
    </div>
    <div class="content hoge3">
      hoge3
    </div>
    <div class="content hoge4">
      hoge4
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.wrapper {
  width: 100%;
  background-color: cornsilk;
}
.content {
  width: 100%;
  height: 2000px;
}
.movie {
  width: 100%;
}
.movie video {
  width: 100%;
}
.animation-text {
  width: 100%;
  position: absolute;
  color: #FFF;
  font-size: 100px;
  text-align: center;
}

.hoge1 {
  background-color: crimson;
}
.hoge2 {
  background-color: yellow;
}
.hoge3 {
  background-color: cyan;
}
.hoge4 {
  background-color: blue;
}

</style>
