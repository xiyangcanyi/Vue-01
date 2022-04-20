<template>
    <div>
      <school></school>
      <student></student>
    </div>
</template>

<script>
//引入组件
    import school from './School.vue'
    import student from './Student1.vue'

    export default {
     
      name:'App',
      components:{
        school,
        student
      }
    }
</script>

<style>
</style>