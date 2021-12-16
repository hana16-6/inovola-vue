<template>
  <div className="hero_box text-center mt-4">
    <h1>طور متجرك ووسع آفاق تجارتك مع سوق تطبيقات زد</h1>
    <p className="mt-4">
      طور تجارتك من خلال تطبيقات وحلول سوق تطبيقات تساعدك في نمو أرباحك عبر
      إدارة عمليات متجرك بشكل فعال واحترافي
    </p>
    <button className="py-2 px-5 mt-5" type="button">
      تصفح التطبيقات
      <img className="me-2" src="../assets/icons/chevron.svg" alt="" />
    </button>
  </div>
</template>

<script>
export default {
  name: "HeroBox",
};
</script>
<style scoped lang="scss">
$primary-color: #8d5da7;
.hero_box {
  h1 {
    color: $primary-color;
  }

  p {
    width: 512.44px;
    margin: 0 auto;
    line-height: 34px;
    font-size: 18px;
    font-weight: normal;
  }
  button {
    background-color: $primary-color;
    color: #fdb515;
    border: none;
    outline: none;
    border-radius: 10px;
  }
}
</style>