<template>
  <div class="homepage_container">
    <div class="homepage_choose">
      <n-button class="choose_random" @click="randomWhereEat">中午吃什么</n-button>
      <n-button class="choose_more" @click="addWhereEat">加菜</n-button>
    </div>
  </div>
</template>
<script>
export default {
    name: 'HomePage',
    methods: {
      randomWhereEat(){
        
      },
      addWhereEat() {

      }
    }
}
</script>
<style scoped lang="less">
  .homepage_container {
    display: flex;
    justify-content: center;
    align-items: center;
    .homepage_choose {
      margin-top: 100px;
    }
  }
</style>