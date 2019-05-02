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
    Mensagem,
  }
}
</script>

<style>
#principal {
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 100%;
  background-image: url(https://firebasestorage.googleapis.com/v0/b/devfriends-5ab33.appspot.com/o/Fundo%20do%20Site%2F1.png?alt=media&token=3fcfbc19-ad9b-4475-afbd-a930b2a3a18e)
}
</style>
