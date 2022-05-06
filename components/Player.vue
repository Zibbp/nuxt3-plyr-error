<script setup>
import Plyr from "plyr";

// const player = ref(null);

const newPlayer = Plyr("#player");
</script>

<template>
  <div>
    Client only player

    <div>
      <video id="player" ref="player" playsinline controls crossorigin="">
        <source
          src="https://storage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4"
          type="video/mp4"
        />
      </video>
    </div>
  </div>
</template>
