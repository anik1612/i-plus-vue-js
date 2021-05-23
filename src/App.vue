<template>
  <div class="main-container">
    <div class="header-section">
      <Header />
    </div>
    <div class="main-body-section row">
      <div class="video-player-section col-md-8">
        <VideoPlayer />
      </div>
      <div class="chatting-section col-md-4 d-flex flex-column">
        <div class="top-image-portion mb-5">
          <img src="./assets/images/chat-bubbles.jpg" class="chat-img" alt="">
        </div>
        <div class="chat-portion card p-2">
          <Chat />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Chat from './components/Chat.vue';
import Header from "./components/Header";
import VideoPlayer from './components/VideoPlayer'

export default {
  name: "App",
  components: {
    Header,
    VideoPlayer,
    Chat,
  },
};
</script>

<style>
.row {
  margin: 0;
  padding: 0 !important;
}

.chat-img {
  width: 100%;
  height: 300px;
}
</style>
