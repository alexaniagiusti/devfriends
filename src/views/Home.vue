<template>
  <div id="principal">
    <toolbar />
    <mensagem />
  </div>
</template>

<script>
import Toolbar from '../components/Toolbar.vue'
import Mensagem from '../components/Mensagem.vue'
export default {
  data (){
    return {

    }
  },
  components: {
    Toolbar,
    Mensagem
  }
}
</script>

<style>
#principal {
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 100%;
  background-color: #4A148C
}
</style>
