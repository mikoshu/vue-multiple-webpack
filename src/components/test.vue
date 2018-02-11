<style>
.hello{
  font-size:24px;
  color:rgb(84, 122, 245);
}
</style>

<template>
  <div class="hello">这里是测试页面！！内容   {{hello}}</div>
</template>

<script>
export default {
  data(){
    return {
      hello: 'hellow'
    }
  }
}
</script>
