<template>
  <div class="home">
    Index.vue
    <p><router-link to="/error/error404">/error/error404</router-link></p>
    <p><router-link to="/notice/list">/notice/list</router-link></p>
    <p><router-link to="/meeting/list">번개모임</router-link></p>
    <p><router-link to="/meeting/write">번개모임작성</router-link></p>
    <p><router-link to="/login">login</router-link></p>
    <p><router-link to="/main">main</router-link></p>
  </div>
</template>


<script>
export default {
  

}

let param1 = 'hoyong';
console.log(param1);

param1 = 'hoyong2';

let helloMan = `hello ${param1}`;
console.log(param1);

</script>