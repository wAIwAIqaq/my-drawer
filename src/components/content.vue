<template>
  <div
    style="
      border: 1px solid #ebeef5;
      border-radius: 4px;
      box-shadow: 0 2px 12px 0 rgb(0 0 0 / 10%);
    "
  >
    <div>
      素胚勾勒出青花笔锋浓转淡
      <el-button @click="toggleDrawer" type="text">toggle </el-button
      >瓶身描绘的牡丹一如你初妆 冉冉檀香透过窗心事我了然 宣纸上走笔至此搁一半
      釉色渲染仕女图韵味被私藏 而你嫣然的一笑如含苞待放 你的美一缕飘散
      去到我去不了的地方 天青色等烟雨 而我在等你 炊烟袅袅升起 隔江千万里
      在瓶底书汉隶仿前朝的飘逸 就当我为遇见你伏笔 天青色等烟雨 而我在等你
      月色被打捞起 晕开了结局 如传世的青花瓷自顾自美丽
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    toggleDrawer() {
      this.$emit("toggleDrawer");
    },
  },
};
</script>

<style lang="scss" scoped></style>
