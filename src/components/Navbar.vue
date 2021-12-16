
<template>
  <div className="container">
    <nav className="mt-4 row justify-content-around align-items-center">
      <div className="logo col-2">
        <img src="../assets/images/zid-logo.png" alt="" />
      </div>
      <ul className="col-8 d-flex list-unstyled">
        <li className="mx-5">الرئيسية</li>
        <li className="mx-5">التصنيفات</li>
        <li className="mx-5">التطبيقات</li>
        <li className="mx-5">طور تطبيقك</li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>
<style scoped lang="scss">
$font-size: 50px;
$color: red;
h1 {
  font-size: $font-size;
  color: $color;
}
</style>