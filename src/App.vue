<template>
  <div class="test">
    <iframe src="https://ebd.cda.pl/620x368/13620795e7" width="100%" height="100%" style="border:none;" scrolling="no" allowfullscreen name="v2" allow="encrypted-media"></iframe>
  </div>
  <video src="https://ebd.cda.pl/620x368/13620795e7"></video>
  <div class="player-box">
    <iframe
      src="https://player.twitch.tv/?channel=rozowakaczuszka&parent=lixad.github.io"
      height="400"
      width="600"
      allowfullscreen
      class="player"
    >
    </iframe>
  </div>
  <div class="chat-box">
    <iframe
      id="twitch-chat-embed"
      src="https://www.twitch.tv/embed/rozowakaczuszka/chat?parent=lixad.github.io"
      height="100%"
      width="100%"
      class="chat"
    >
    </iframe>
  </div>
</template>

<style scoped>
.test {
  position: absolute;
  height: 100vh;
  width: 80vw;
  top: 0;
  left: 0;
  z-index: 0;
}

.chat-box {
  position: absolute;
  top: 0px;
  right: 4px;
  width: 19vw;
  height: 100vh;
}

.player-box {
  position: absolute;
  top: 0px;
  left: 0px;
  z-index: 10;
}

</style>
