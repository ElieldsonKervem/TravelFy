<script setup>
import { ref } from 'vue'

</script>

<template>

    <div class="cardSlider"> 
         <div class="sliderSection">
            <h1>Destino Nacionais</h1>
            <p>Oferecemos roteiros exclusivos que destacam o melhor do Brasil, desde suas vibrantes cidades até suas paisagens deslumbrantes. Explore cada canto do país com conforto e estilo, e viva experiências inesquecíveis sem sair do território nacional.</p>                 
         </div>
          <div class="containerSlider">
                <div class="slider">
                    <div class="slide">
                        <img src="../../public/rj.png" alt="rio de janeiro">
                        <div class="content">
                            <h3>Rio de Janeiro</h3>
                            <i></i>
                            <button>{{$valor}}</button>
                            <h6>4,8 (940 reviews)</h6>
                        </div>
                    </div>
                    <div class="slide">
                        <img src="../../public/saopaulo.png" alt="são paulo">
                        <div class="content">
                            <h3>São paulo</h3>
                            <i></i>
                            <button>{{$valor}}</button>
                            <h6>4,8 (940 reviews)</h6>
                        </div>
                    </div>
                    <div class="slide">
                        <img src="../../public/natal.png" alt="fortaleza">
                        <div class="content">
                            <h3>Natal</h3>
                            <i></i>
                            <button>{{$valor}}</button>
                            <h6>4,8 (940 reviews)</h6>
                        </div>
                    </div>
                    <div class="slide">
                        <img src="../../publiC/amazonia.png" alt="amazonia">
                        <div class="content">
                            <h3>Amanzonia</h3>
                            <i></i>
                            <button>{{$valor}}</button>
                            <h6>4,8 (940 reviews)</h6>
                        </div>
                    </div>
                    <div class="slide">
                        <img src="../../publiC/amazonia.png" alt="amazonia">
                        <div class="content">
                            <h3>Amanzonia</h3>
                            <i></i>
                            <button>{{$valor}}</button>
                            <h6>4,8 (940 reviews)</h6>
                        </div>
                    </div>
                </div>
          </div>
    </div>
</template>

<style scoped>

</style>
