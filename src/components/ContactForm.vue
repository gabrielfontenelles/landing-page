<template>
  <section class="py-5 bg-light" id="contact">
    <div class="container">
      <h2 class="text-center mb-4">Entre em Contato</h2>
      <form class="mx-auto" style="max-width: 600px">
        <div class="mb-3">
          <label for="name" class="form-label">Seu Nome</label>
          <input
            type="text"
            class="form-control"
            id="name"
            placeholder="Digite seu nome"
          />
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">Seu E-mail</label>
          <input
            type="email"
            class="form-control"
            id="email"
            placeholder="Digite seu e-mail"
          />
        </div>
        <div class="mb-3">
          <label for="message" class="form-label">Mensagem</label>
          <textarea
            class="form-control"
            id="message"
            rows="4"
            placeholder="Digite sua mensagem"
          ></textarea>
        </div>
        <button type="submit" class="btn btn-primary w-100">Enviar</button>
      </form>
    </div>
  </section>
</template>
