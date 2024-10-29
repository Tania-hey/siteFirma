<template>
<H3>Întrebări frecvente</H3>
<div class="d-flex flex-row">
    <div class="accordion questionContent" id="accordionExample">
        <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
            <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                <span>01</span> Folosiți aspirator cu abur și inserție-extracție?
            </button>
            </h2>
            <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
            <div class="accordion-body">
                Da folosim aspirator de acest tip. Suprafața murdară se curață în profunzime cu aburul la 130°C.
            </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header" id="headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                <span>02</span>Cât timp durează realizarea un detailing interior complet?
            </button>
            </h2>
            <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
            <div class="accordion-body">
                Un detailing complet durează între 8 si 12 ore în funcție de starea în care se află autovehiculul.
            </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header" id="headingThree">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                <span>03</span>După polish vor dispărea toate zgârieturile?
            </button>
            </h2>
            <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
            <div class="accordion-body">
                Depinde cât de adânci sunt zgârieturile. Deasemenea și zgârieturile mai adânci pot dispărea, dar cu anumite riscuri, așadar, decizia îi aparține clientului.
            </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header" id="headingFour">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">
                <span>04</span> Tapițeria din piele se curață? 
            </button>
            </h2>
            <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                    Da se curăță, recomandarea noastră este să fie curățată și <strong>hidratată</strong> de 1-3 ori pe an, în funcție de numărul de kilometri parcurși.
                </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header" id="headingFive">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFive" aria-expanded="false" aria-controls="collapseFive">
                <span>05</span>După un detailing interior vor dispărea toate petele?
            </button>
            </h2>
            <div id="collapseFive" class="accordion-collapse collapse" aria-labelledby="headingFive" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                    Petele de murdărie dispar, dar dacă petele au ajuns în țesătura materialului și acesta este pătat, din păcate acestea nu se mai pot scoate.
                </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header" id="headingSix">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSix" aria-expanded="false" aria-controls="collapseSix">
                <span>06</span>Cum pot menține aspectul lucios mai mult timp dupa un polish?
            </button>
            </h2>
            <div id="collapseSix" class="accordion-collapse collapse" aria-labelledby="headingSix" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                    Pentru o durabilitate mai lungă de timp este necesar aplicarea 
                    unei protecții ceramice. Evitarea spălării mașinii la perii. 
                    Un alt factor poate fi modul de spălare și uscare a mașinii,
                    după aplicarea spunei, pentru a îndepărta murdăria este recomandat spălarea cu o mănușă, iar uscarea să fie neapărat cu prosoape din microfibră.
                </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header" id="headingSeven">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSeven" aria-expanded="false" aria-controls="collapseSeven">
                <span>07</span>Cum pot menține aspectul lucios mai mult timp dupa un polish?
            </button>
            </h2>
            <div id="collapseSeven" class="accordion-collapse collapse" aria-labelledby="headingSeven" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                    Pentru o durabilitate mai lungă de timp este necesar aplicarea 
                    unei protecții ceramice. Evitarea spălării mașinii la perii. 
                    Un alt factor poate fi modul de spălare și uscare a mașinii,
                    după aplicarea spunei, pentru a îndepărta murdăria este recomandat spălarea cu o mănușă, iar uscarea să fie neapărat cu prosoape din microfibră.
                </div>
            </div>
        </div>
    </div>
    <div class="d-none d-lg-flex align-items-center">
        <img src="../assets/img/questionMark.png" alt="">
    </div>
</div>
</template>

<script>
export default {
  name: 'IntrebariFrecvente',
}
</script>

<style scoped>
 h3 {
  font-weight: 600;
  font-size: 26px;
  padding: 5rem 0rem;
}
.accordion span {
  color: #111110;
  font-weight: 600;
  font-size: 18px;
  padding-right: 10px;
}
/* 
.questionContent{
    width: 50rem;
    margin: 0rem 6rem 0rem 4rem;
} */
.questionContent {
  width: 100%; /* Lățime completă pe ecrane mici și medii */
  margin: 0;
}

/* Doar pentru ecrane mari (de la 992px în sus) */
@media (min-width: 992px) {
  .questionContent {
    width: 50rem; /* Dimensiune specifică pentru ecrane mari */
    margin: 0rem 6rem 0rem 4rem;
  }
}
.accordion-button:not(.collapsed){
    color: black;
    background-color: #caf59e;
    box-shadow: none;
}
.accordion-button :active{
  
    box-shadow: none;
}
</style>