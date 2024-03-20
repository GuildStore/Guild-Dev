<template>
  <div class="navigation">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="https://bulma.io">
          <img
            src="https://bulma.io/images/bulma-logo.png"
            width="112"
            height="28"
          />
        </a>
        <a
          role="button"
          class="navbar-burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
      <div class="navbar-menu">
        <div class="navbar-start">
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link"> Jogos de Cartas </a>
            <div class="navbar-dropdown">
              <a class="navbar-item"> One Piece </a>
              <a class="navbar-item"> Pokemon </a>
              <a class="navbar-item"> Digimon </a>
              <a class="navbar-item"> Lorcana </a>
            </div>
          </div>

          <a class="navbar-item"> Jogos de Tabuleiro </a>

          <a class="navbar-item"> Acessórios </a>
        </div>
        <div class="navbar-end">
          <div class="navbar-item">
            <div class="buttons">
              <a class="button has-background-link-dark has-text-white">
                <strong>Discord</strong>
              </a>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>
