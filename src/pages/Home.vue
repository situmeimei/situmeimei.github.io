<template>
  <div class="homePage" :style="note">
    
  </div>
</template>

<script>
export default {
  data() {
    return {
      note: {
        backgroundImage: 'url(' + require('../assets/img/catBg.png') + ')'
      }
    };
  }
};
</script>

<style lang="scss" scoped>
.homePage {
  width: 100%;
  height: 100%;
  // background: 'url(' + require('../assets/img/catBg.png') + ')';
}
</style>


