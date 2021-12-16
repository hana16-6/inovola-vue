<template>
  <div className="container py-5">
    <div className="text-center">
      <h2>التطبيقات المميزة</h2>
      <p>تطبيقات تقدم حلول وخدمات مميزة نوصي بتجربتها</p>
    </div>
    <div className="row mt-5">
      <div className="col-3 p-0">
        <AppItem />
      </div>
      <div className="col-3 p-0">
        <AppItem />
      </div>
      <div className="col-3 p-0">
        <AppItem />
      </div>
      <div className="col-3 p-0">
        <AppItem />
      </div>
    </div>
    <div className="text-center mt-4">
      <span className="gold-color"> تصفح التطبيقات</span>

      <img className="me-2" src="../../assets/icons/chevron.svg" alt="" />
    </div>
  </div>
</template>

<script>
import AppItem from "@/components/apps/AppItem.vue";
export default {
  name: "AppWrapper",
  components: {
    AppItem,
  },
};
</script>
<style scoped lang="scss">
.gold-color {
  color: #fdb515;
}
</style>