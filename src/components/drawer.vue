<template>
  <div
    style="
      position: fixed;
      top: 0;
      right: 0;
      display: flex;
      align-items: center;
    "
  >
    <div class="switchBar" @click="toggleDrawer">
      <i class="el-icon-caret-left"></i>
    </div>
    <transition name="el-fade-in-linear">
      <el-card v-show="isShow" class="box-card"> </el-card>
    </transition>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isShow: false,
    };
  },
  methods: {
    toggleDrawer() {
      this.isShow = !this.isShow;
    },
  },
};
</script>

<style scoped>
.drawer-body {
  width: 300px;
}
</style>
