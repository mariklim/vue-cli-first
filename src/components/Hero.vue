<template>
    <div>
        <img :src= "msg">
    </div>
</template>
<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>
<style scoped>
div img{
    max-width:400px ;
}
 
</style>