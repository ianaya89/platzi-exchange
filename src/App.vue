<template>
  <main>
    <px-header />
    <px-assets-table />
  </main>
</template>

<script>
import PxHeader from "@/components/PxHeader";
import PxAssetsTable from "@/components/PxAssetsTable";

export default {
  name: "app",
  components: { PxHeader, PxAssetsTable }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
