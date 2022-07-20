<template>
  <main class="">
    <div class="grid remover-espaco">
      <div class="col-2 remover-espaco">
        <SideBar/>
      </div>
      <div class="col">2</div>
      
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import SideBar from "./components/SideBar.vue";
export default defineComponent({
  name: "App",
  components: {
    SideBar
  }
});
</script>

<style>
.remover-espaco{
  margin: 0 !important;
  padding: 0 !important;
  }
body{
  margin: 0;
  padding: 0;
  
}
</style>
