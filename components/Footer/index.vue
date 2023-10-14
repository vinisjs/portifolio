<template lang="">
  <footer>
    <div class="bg-zinc-900 p-2 mt-4">
      <div
        class="mx-auto grid grid-cols-1 gap-4 md:grid md:grid-cols-2 grid-flow-row max-w-5xl p-4"
      >
        <h1 class="text-2xl uppercase font-bold md:text-4xl">
          viniccius.com.br
        </h1>
        <!-- Links -->
        <ul
          class="grid grid-cols-2 text-sm gap-4 sm:grid-cols-3 sm:justify-end"
        >
          <ul>
            <h3 class="font-bold uppercase">Institucional</h3>
            <li>
              <nuxt-link class="hover:text-sky-500" to="/">Sobre</nuxt-link>
            </li>
            <li>
              <nuxt-link class="hover:text-sky-500" to="/"
                >Termos de Uso</nuxt-link
              >
            </li>
            <li>
              <nuxt-link class="hover:text-sky-500" to="/"
                >Política de Privacidade</nuxt-link
              >
            </li>
          </ul>
          <ul>
            <h3 class="font-bold uppercase">Serviços</h3>
            <li>
              <nuxt-link class="hover:text-sky-500" to="/"
                >Web - Simple</nuxt-link
              >
            </li>
            <li>
              <nuxt-link class="hover:text-sky-500" to="/"
                >Web - Product
              </nuxt-link>
            </li>
            <li>
              <nuxt-link class="hover:text-sky-500" to="/"
                >Wp - Blog/E-commerce</nuxt-link
              >
            </li>
          </ul>
          <ul>
            <h3 class="font-bold uppercase">Siga-me</h3>
            <li>
              <nuxt-link class="hover:text-sky-500" to="/">Instagram</nuxt-link>
            </li>
            <li>
              <nuxt-link class="hover:text-sky-500" to="/">Github</nuxt-link>
            </li>
            <li>
              <nuxt-link class="hover:text-sky-500" to="/">X</nuxt-link>
            </li>
          </ul>
        </ul>
        <!-- Credits -->
        <div>
          <span>
            <p>2023 © viniccius studios - todos os direitos reservados</p>
          </span>
        </div>
      </div>
    </div>
  </footer>
</template>
