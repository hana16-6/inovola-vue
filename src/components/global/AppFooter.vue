<template>
  <footer className="p-2">
    <div className="container">
      <div className="row justify-content-center pt-3">
        <div className="col-4 text-center">
          <img src="../../assets/images/zid-logo-white.png" alt="" />
        </div>
      </div>
      <ul className=" list-unstyled d-flex justify-content-center p-0 mt-4">
        <li className="mx-3">
          <img src="../../assets/icons/social/youtube.svg" alt="" />
        </li>
        <li className="mx-3">
          <img src="../../assets/icons/social/linkedin.svg" alt="" />
        </li>
        <li className="mx-3">
          <img src="../../assets/icons/social/insta.svg" alt="" />
        </li>

        <li className="mx-3">
          <img src="../../assets/icons/social/twitter.svg" alt="" />
        </li>
      </ul>
      <div className="row justify-content-between">
        <div className="col-2">
          <img src="../../assets/images/chat.png" alt="" />
        </div>

        <div className="col-2 text-end">
          <img src="../../assets/images/up.png" alt="" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>
<style scoped lang="scss">
$primary-color: #8d5da7;
footer {
  background-color: $primary-color;
}
</style>