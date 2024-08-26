<template>
    <div class="cardManu" id="app">
      <header class="mainHeader">
        <div class="container">
          <div>
            <h2 class="logo">
              <span class="strong">TRAVEL</span>FY
            </h2>
          </div>
          <div>
            <ul class="menuList">
              <li class="menuItem"><a href="#">HOME</a></li>
              <li class="menuItem"><a href="#">DESTINOS</a></li>
              <li class="menuItem"><a href="#">PACOTES</a></li>
              <li class="menuItem"><a href="#">CONTATO</a></li>
            </ul>
          </div>
          <div>
            <button class="btnLogin">LOGIN</button>
            <button class="btnRegister">SIGN UP</button>
          </div>
          <div>
            <div v-if="isVisible" class="responsive-div">
             
              <img :src="imagePath" alt="Menu" @error="handleImageError">
            </div>
           
          </div>
        </div>
      </header>
    </div>
  </template>
  
  <script>
  import { ref, onMounted, onBeforeUnmount } from 'vue';
  
  export default {
    setup() {
      const isVisible = ref(true);
      const imagePath = '/menu.svg'; // Caminho da imagem
  
      const checkWidth = () => {
        console.log('Largura da tela:', window.innerWidth);
        isVisible.value = window.innerWidth <= 1200;
        console.log('isVisible:', isVisible.value);
      };
  
      onMounted(() => {
        checkWidth(); // Verifica a largura da tela ao montar o componente
        window.addEventListener('resize', checkWidth); // Adiciona um listener para mudanças de tamanho da janela
      });
  
      onBeforeUnmount(() => {
        window.removeEventListener('resize', checkWidth); // Remove o listener ao destruir o componente
      });
  
      const handleImageError = (event) => {
        console.error('Erro ao carregar a imagem:', event);
      };
  
      return {
        isVisible,
        imagePath,
        handleImageError
      };
    },
  };
  </script>
  
  <style scoped>
  /* Estilo básico para verificar visibilidade */
 
  </style>
  