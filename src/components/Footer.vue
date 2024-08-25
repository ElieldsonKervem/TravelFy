<script setup>
import { ref } from 'vue'

</script>

<template>

    <div  class="footer">
        <div class="newLatterCard">
            <div class="headerLatterCard">
                <h2>Assine nossas newsletter e 
                    receba promoções e dicas incriveis</h2>
                    <p>Assine nossa newsletter e fique por dentro das melhores promoções e dicas exclusivas!</p>
            </div>
            <div class="serchNewsLatter">
                <input type="email" placeholder="digite seu amail aqui" class="emaiInput">
               <button class="subscribe">
                  Subscrever
                  <i></i>
               </button>

            </div>
        </div>
        <img src="../../public/fly.svg" alt="air fly svg" class="flysvg
        ">
        <footer>
            <div class="footerfirstContainer">
                <h3>TRAVELFY</h3>
                <p>Endereço: Rua Exemplo, 123, Centro, Cidade, País
                    Telefone: +55 (XX) XXXX-XXXX
                    E-mail: contato@exemplo.com</p>
                <div class="iconsFooter">
                    <img src="../../public/instaIcon.svg" alt="">
                    <img src="../../public/telegramIcon.svg" alt="">
                    <img src="../../public/telegramIcon.svg" alt="">
                </div>
            </div>
            <div class="footerSecondContainer">
             
                <ul>
                  
                    <ul> 
                        <li>Serviços</li>
                        <li>Passagens</li>
                        <li>Hotéis</li>
                        <li>Pacotes</li>
                    </ul>
                    
                     <ul>
                        <li>Mapa do site</li>
                        <li>Brasil</li>
                        
                        <li>América do Norte</li>
                        <li>Europa</li>
                       
                     </ul>
                
                     <ul>
                        <li>Contato</li>
                        <li>FAQ</li>
                        <li>Contato</li>
                        <li>Política de Privacidade</li>
                     </ul>
                  
                     <ul>
                        <li>Ajuda</li>
                        <li>Telefone</li>
                        <li>E-mail</li>
                        <li>Endereço</li>
                     </ul>
                </ul>
            </div>
        </footer>
    </div>
</template>

<style scoped>

</style>
