<template>
  <div class="home">
    <h1 class="homeOverskrift">Velkommen!</h1>
  </div>
  <div class="content">
    <img class="img1" src="../../public/artwork-smoke-old-people-old-wallpaper-preview.png" alt="">
    <img class="img2" src="../../public/70997208.png" alt="russ">
  </div>
  <div class="content2">
    <iframe src="https://giphy.com/embed/zFegkS85TBi8w" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>
    <p><a class="gif" href="https://giphy.com/gifs/funny-lady-gaga-drugs-zFegkS85TBi8w%22%3Evia GIPHY"></a></p>
  </div>
</template>

<script>
export default {

}
</script>

<style>

.home {
  display: flex;
  justify-content: center;
}

.homeOverskrift {
  font-size: 80px;
}

.img1 {
  width: 700px;
  height: 500px;
  margin: 5rem;
}

.img2 {
  width: 500px;
  height: 350px;
  margin: 5rem;
  margin-top: 10rem;
}

.content, .content2 {
  display: flex;
  justify-content: center;
}
</style>