<template>
  <div class="background">
    <video autoplay muted loop id="myVideo">
      <source src="../assets/CodeVideo.mp4" type="video/mp4" />
    </video>
  </div>
</template>

<script></script>

<style>
#myVideo{
  min-width: 100%;
  max-height: 100%;
}

.background {
  background: url('../assets/network.jpg');
  height: 500px;
}
</style>
