
<template>
  <div className="container">
    <div className="intro row justify-content-center mt-5 pt-5">
      <img className="w-75" src="../assets/images/Intro.png" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Intro",
};
</script>
<style scoped lang="scss">
.intro {
  position: relative;
  background-image: url("../assets/images/Dot-Pattern.png"),
    url("../assets/images/yellow-ellipse.png");
  background-repeat: no-repeat;
  background-position: 73px -21px, 700px 313px;
  padding-bottom: 200px;
}
</style>