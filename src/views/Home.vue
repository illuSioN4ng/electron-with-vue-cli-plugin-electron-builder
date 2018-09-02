<template>
  <div class="home">
    <div class="list-item"
         @click="$router.push('/register')">
      Register
    </div>
    <div class="list-item"
         @click="$router.push('/login')">
      Login
    </div>
    <div class="list-item"
         @click="$router.push('/facebook')">
      Facebook
    </div>
    <div class="list-item"
         @click="$router.push('/twitter')">
      Twitter
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: 'home'
}
</script>

<style lang="scss">
.list-item {
  width: 80%;
  margin: 20px auto;
  background-color: #f5f5f5;
  line-height: 60px;
  color: #333;
  cursor: pointer;
}
</style>

