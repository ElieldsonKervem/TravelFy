<script setup>
import { ref } from 'vue'

</script>

<template>

    <div class="cardNav"> 
         <div class="seachContainer">
            <div class="searchDrawer">
                <div>
                    <ul class="listDestiny">
                        <li class="listItemDrawer">
                            DESTINOS
                            <img src="../../public/arrowdown.svg" alt="arrow" >
                        </li>
                        <li class="listItemDrawerMsg">
                            <p>Para onde <br> deseja viajar?</p>
                        </li>
                    </ul>
                </div>
                <div>
                    <ul class="listDestiny">
                        <li class="listItemDrawer">
                            DATAS
                            <img src="../../public/arrowdown.svg" alt="arrow" >
                        </li>
                        <li class="listItemDrawerMsg">
                            <p>Quando deseja <br> viajar ?</p>
                        </li>
                    </ul>
                </div>
                <div>
                    <ul class="listDestiny">
                        <li class="listItemDrawer">
                            PESSOAS
                            <img src="../../public/arrowdown.svg" alt="arrow" >
                        </li>
                        <li class="listItemDrawerMsg">
                            <p>Quantas <br> pessoas ?</p>
                        </li>
                    </ul>
                </div>
                <div>
                    <ul class="listDestiny">
                        <li class="listItemDrawer">
                            PROMOÇÕES
                            <img src="../../public/arrowdown.svg" alt="arrow" >
                        </li>
                        <li class="listItemDrawerMsg">
                            <p>Escolha <br> a classe ?</p>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="search">
                 <div>
                    <input class="btnSearch" type="button" value="Buscar" >
                    <img src="../../public/search.svg" alt="" style="color: aliceblue;">
                 </div>
            </div>
         </div>
    </div>
</template>

<style scoped>

</style>
