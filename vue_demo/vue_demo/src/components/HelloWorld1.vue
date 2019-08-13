<template>
    <div>
        {{msg}}
    </div>
</template>
<script>
  // import __ from '__' // __是需要手动引入的文件
  export default {
    name: 'HelloWorld',
    components: {},
    //必须写入一个函数
      data () {
          return {msg: '这个是Home模板页'}
      },
      methods: {}
  }
</script>
<style lang="postcss" scoped>
  body {
      background-color: #ff0000;
  }
</style>
