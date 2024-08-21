<script setup>
import { ref } from 'vue'

</script>

<template>

    <div  class="cardHero">
        <main class="widthLimit">
            <div class="cardHeroContainer ">
                <div class="mainCard">
                    <h1>Descubra o mundo <br> com a travelfy!</h1>
                    <p>Descubra novas culturas, paisagens deslumbrantes e experiências inesquecíveis com nossa agência de viagens. Estamos aqui para tornar suas aventuras ao redor do mundo simples e memoráveis</p>
                    <input type="button" value="Descubra" class="btnSearch">
                    <i></i>
                </div>
                <div class="cardImgsHighlights">
                    <div class="cardImgs">
                        <div class="card1">
                            <img src="../../public/rioDeJaneiro.png" alt="">
                        </div>
                        <div class="card2">
                            <img src="../../public/newyork.png" alt="">
                        </div>
                        <div class="card3">
                            <img src="../../public/dubai.png" alt="">
                        </div>
                        <div>
                            <img src="../../public/womanS.png" alt="" class="womanImg">
                        </div>
                        <div class="svgHero1">
                           <svg width="76" height="76" viewBox="0 0 76 76" fill="none" xmlns="http://www.w3.org/2000/svg"><ellipse id="Ellipse 1" cx="38" cy="37.8595" rx="38" ry="37.5071" fill="#7209B7"/></svg>
                        </div>
                    </div>
                </div>
            </div>
        </main>
    </div>
</template>

<style scoped>

</style>
