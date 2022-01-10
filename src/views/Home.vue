<template>
  <div class="home">
    <top-view></top-view>
    <sale-view></sale-view>
    <bottom-view></bottom-view>
    <map-view></map-view>
  </div>
</template>

<script>
import TopView from "../components/TopView/TopView.vue";
import SaleView from "../components/SaleView.vue";
import BottomView from "../components/BottomView.vue";
import MapView from "../components/MapView.vue";

export default {
  name: "Home",
  components: {
    TopView,
    SaleView,
    BottomView,
    MapView,
  },
};
</script>

<style lang="scss" scoped>
.home {
  width: 100%;
  height: 100%;
  padding: 20px;
  background-color: #eee;
  box-sizing: border-box;
}
</style>
