<template>
  <div class="random_container">
    <n-page-header :subtitle="reuslt" @back="handleBack">
    <template #header>
      <n-breadcrumb>
        <n-breadcrumb-item>首页</n-breadcrumb-item>
        <n-breadcrumb-item>选好了</n-breadcrumb-item>
      </n-breadcrumb>
    </template>
  </n-page-header>
    <div class="result_container">
      <span>{{restaurantInfo}}</span>
    </div>
  </div>
</template>
<script>
export default {
  name: 'RandomRestaurant',
  data(){
    return {
      reuslt: '温馨餐厅',
      restaurantInfo: '温馨餐厅简介'
    }
  },
  methods: {
    handleBack(){

    }
  }
}
</script>
<style scoped lang="less">
  .random_container{
    padding: 10px;
    .result_container {
      padding: 10px 20px;
    }
  }
</style>