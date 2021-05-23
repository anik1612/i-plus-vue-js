<template>
  <div class="mt-3 video-player">
    <video
      id="my-video"
      class="video-js vjs-default-skin"
      controls
      preload="auto"
      width="1000"
      height="600"
      poster="http://video-js.zencoder.com/oceans-clip.jpg"
      data-setup="{}"
    >
      <source src="https://vjs.zencdn.net/v/oceans.mp4" type="video/mp4" />
      
      <p class="vjs-no-js">
        To view this video please enable JavaScript, and consider upgrading to a
        web browser that
        <a href="https://videojs.com/html5-video-support/" target="_blank"
          >supports HTML5 video</a
        >
      </p>
    </video>
  </div>

  <!-- video player additional funcition -->
  <div class="d-flex align-items-center">
    <div class="ms-1">
      <i class="fas fa-plus-square fa-3x"></i>
    </div>
    <div class="ms-5">
      <i class="fas fa-heart fa-2x text-danger"></i>
    </div>
    <div class="ms-5">
      <i class="fas fa-smile fa-2x"></i>
    </div>
    <div class="ms-5">
      <i class="fas fa-download fa-2x"></i>
    </div>
    <div class="ms-5">
      <i class="fas fa-star fa-2x text-warning"></i>
    </div>
    <div class="ms-5">
      <i class="fas fa-hand-paper fa-2x"></i>
    </div>
    <div class="ms-5">
      <i class="fas fa-trash fa-2x"></i>
    </div>
    <div class="ms-5">
      <i class="fas fa-share fa-flip-horizontal fa-2x"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: "VideoPlayer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* Show the controls (hidden at the start by default) */
.video-js .vjs-control-bar {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

/* Make the demo a little prettier */
body {
  margin-top: 20px;
  background: #222;
  text-align: center;
  color: #aaa;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  background: radial-gradient(#333, hsl(200, 30%, 6%));
}
</style>
