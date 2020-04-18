<template>
  <div class="hello">
    <p v-text='msg' class="msg"></p>
 
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'HelloWorld'
    }
  }
}
</script>

<style scoped>
   .hello {
    position: relative;
    width: 300px;
    height: 300px;
    background-color: #99e2d7;
    border: 1px solid #c4e0a9;
    color: #180e33;
    font-size: 30px;
    margin: auto;


  }
  .msg {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
  }

</style>
