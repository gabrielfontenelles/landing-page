<template>
  <section class="py-5 bg-light" id="benefits">
    <div class="container text-center">
      <h2 class="mb-4">Benefícios</h2>
      <div id="benefitsCarousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="card mx-auto" style="width: 18rem">
              <div class="card-body">
                <h5 class="card-title">Fácil de usar</h5>
                <p class="card-text">
                  Mesmo iniciantes podem aproveitar todos os recursos sem
                  dificuldades.
                </p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="card mx-auto" style="width: 18rem">
              <div class="card-body">
                <h5 class="card-title">Acesso 24 horas</h5>
                <p class="card-text">
                  Ferramenta disponível para você em qualquer momento.
                </p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="card mx-auto" style="width: 18rem">
              <div class="card-body">
                <h5 class="card-title">Resultados rápidos</h5>
                <p class="card-text">
                  Tenha sua produtividade dobrada com nossos recursos.
                </p>
              </div>
            </div>
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#benefitsCarousel"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#benefitsCarousel"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
        </button>
      </div>
    </div>
  </section>
</template>
