<template>
  <div class="app">
    <p class="test">文字：{{count}}</p>
    <i class="icon"></i>
  </div>
</template>
<script>

export default{
  data(){
    return {
      count:1
    }
  }
}
</script>

<style scoped src="./app.less"></style>