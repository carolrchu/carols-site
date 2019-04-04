
<template>
  <div class="page1">
    <ul class="nav justify-content-end">
  <li class="nav-item">
    <a class="nav-style" href="#">resume</a>
  </li>
  <li class="nav-item">
    <a class="nav-style" href="#">about</a>
  </li>
</ul>
    <div class="container">
      <div class="row">
        <div class="col-10 mx-auto text-center">
            <img src="@/assets/images/background-pic.png" class="img-fluid" alt="background-pic" style="margin-top: 2%">
            <div style="position: absolute; width: 100%;" class="display:flex; justify-content:center; align-items:center;">
              <h1 class="heading">Hi, I'm Carol.               <h1 class="heading-italicized">Carol Chu.</h1>
 </h1>

            </div>
        </div>
      </div>
    </div>
    <div class="mx-auto text-center">
      <!-- <h1 class="heading">Hi, I'm Carol.</h1> -->
      <!-- <h1 class="heading-italicized">Carol Chu.</h1> -->
    </div>

  <div class="container">
    <div class="row">
      <div class="col-12 mx-auto text-center">
          <img src="@/assets/images/tdlab.png" class="img-fluid" alt="tdlab" style="margin: 10% 0">
      </div>
    </div>
  </div>

  <div class="container">
    <div class="row">
      <div class="col-12 mx-auto text-center">
          <img src="@/assets/images/personalproject.png" class="img-fluid" alt="tdlab" style="margin: 5% 0">
      </div>
    </div>
  </div>

  <div class="container">
    <div class="row">
      <div class="col-12 mx-auto text-center">
          <img src="@/assets/images/grow.png" class="img-fluid" alt="tdlab" style="margin: 5% 0">
      </div>
    </div>
  </div>

  <div class="container">
    <div class="row">
      <div class="col-12 mx-auto text-center">
          <img src="@/assets/images/tablestory.png" class="img-fluid" alt="tdlab" style="margin: 5% 0">
      </div>
    </div>
  </div>



  </div>
</template>

<style lang="scss">
@import url("/@/assets/main.scss");
</style>

<script lang="ts">
import Vue from 'vue'
import HelloWorld from '@/components/HelloWorld.vue'

export default Vue.extend({
  name: 'page1',
  components: {
    HelloWorld
  }
})
</script>
