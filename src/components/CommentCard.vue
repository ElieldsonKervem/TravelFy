<script setup>
import { ref } from 'vue'

</script>

<template>
     <div>
    <div  class="cardComment">
         <div class="commentFistCard">
             <h1>Recomendados por mais de 5.000 clientes !</h1>
             <p>
                Mais de 5.000 clientes já confiam em nossos serviços.
                Junte-se a eles e descubra por que somos a escolha preferida.
                Sua satisfação é nossa maior prioridade!
             </p>
         </div>
         <div class="commentSecondCard">
              <div class="commentCard">
                   <img src="../../public/Ellipse 4.svg" alt="img de quem está comentando">
                    <h4>H. laurence</h4>
                    <p>
                        "O melhor serviço de viagens que já usei! 
                        Eles são muito profissionais e sempre dispostos a ajudar. 
                        Eu recomendo a todos os meus amigos e familiares."
                    </p>
                    <div class="cardTags">
                            <span>#good</span>
                            <span>#service</span>
                            <span>#travel</span>
                    </div>
              </div>
                    <div class="prevBtnComment">
                        <i></i>
                    </div>
                    <div class="nextBtnComment">
                        <i></i>
                    </div>
         </div>
         
         
    </div>
          <div class="companies">
                <div class="cardPanies">
                    <img src="../../public/tripavisor.png" alt="">
                </div>
                <div class="cardPanies">
                    <img src="../../public/espedia.png" alt="">
                </div>
                <div class="cardPanies">
                    <img src="../../public/booking.png" alt="">
                </div>
          </div>
 
        </div>
</template>

<style scoped>

</style>
