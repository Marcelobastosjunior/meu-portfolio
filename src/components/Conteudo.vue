<script>
export default {
  methods: {
    redirecionarParaGit() {
      window.open("https://github.com/Marcelobastosjunior", "_blank")
    },
    redirecionarParaLinkedin() {
      window.open("https://www.linkedin.com/in/marcelo-bastos-jr-380869255/", "_blank")
    }
  }
};
</script>

<template>
  <main class="apresentacao">
    <section class="apresentacao__conteudo">
      <h1 class="cabecalho__titulo">Bem-vindo ao meu <strong class="titulo-destaque">Portfólio</strong></h1>
      <p class="apresentacao__texto">Olá, meu nome é Marcelo Bastos Junior, entusiasta e estudante de programação.
        Atualmente, estou focado no aprendizado das linguagens JavaScript, Node.js e Vue. Estou animado para
        expandir meu conhecimento e
        aplicar minhas habilidades na criação de novos projetos.</p>
      <div class="apresentacao__links">
        <h2 class="apresentacao_links_subtitulo">Acesse minhas redes:</h2>
        <button class="apresentacao__botoes__links" @click="redirecionarParaLinkedin">
          <img src="../assets/icons/icons-linkedin.png" alt="icone do linkedin">
          Linkedin
        </button>
        <button class="apresentacao__botoes__links" id="botaoGit" @click="redirecionarParaGit">
          <img src="../assets/icons/icons-github.png" alt="icone do github">
          GitHub
        </button>
      </div>
    </section>
    <img src="../assets/icons/sp-becobatman.jpeg" alt="Foto de Marcelo" class="imgFoto">
  </main>
</template>

<style scoped>
.cabecalho__titulo {
   font-size: 2.5rem;
   font-family: 'Space Grotesk', sans-serif;
   padding: 1% 0% 0% 0%;
}

.titulo-destaque {
   color: #468eec;
}
</style>