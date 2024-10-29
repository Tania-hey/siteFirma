<template>
  <H3>Despre noi</H3>
    <div class="row content mx-3">
        <div class="col-lg-6 d-flex flex-column align-items-center justify-content-center">
            <p>Imperial Detailing, cu sediul în Oradea</p>
            <ul class="d-flex flex-column align-items-start ">
                <li><i class="ri-check-double-line"></i>oferă servicii de  înaltă calitate</li>
                <li><i class="ri-check-double-line"></i> produse premium</li>
                <li><i class="ri-check-double-line"></i> personal cu experiență</li>
                <li><i class="ri-check-double-line"></i> rezultate exceptionale</li>
            </ul>
        </div>
        <div class="col-lg-6 pt-4 pt-lg-0">
        <p class="aboutText">
            Mașina ta merită să arate ca-n prima zi a vieții sale, fiind îngrijită cu cele mai de calitate produse, de oameni experimentați și pasionați.
            Imperial detailing, locul unde masina ta straluceste, este motto-ul nostru.
        </p>
        </div>
    </div>
</template>
  
  <script>
  export default {
    name: 'DespreNoi',
  }
  </script>
  
  <style scoped>
 h3 {
  font-weight: 600;
  font-size: 26px;
  padding: 5rem 0rem;
}

.aboutText{
    width: 35rem;
    margin-top: 2rem;
}

ul li i {
  left: 0;
  top: 2px;
  font-size: 25px;
  color: #89e42e;
  line-height: 1;
} 

ul {
    list-style: none; 
    padding-left: 0; 
}

@media (max-width: 575px) {
  .aboutText {
    width: 20rem; /* Dimensiune specifică pentru ecrane mari */
  
  }
}
</style>