<template>
  <header class="h-20 bg-white flex items-center px-4 border border-zinc-200 justify-between gap-4">
    <img src="https://kong.quero.com/logotype-querobolsa.svg" alt="Quero Bolsa" height="28px" width="181px"/>

    <form action="#" method="get" role="search" class="flex-1 flex gap-2">
      <label for="site-search" class="hidden">Buscar cursos e bolsas</label>
      <input
          type="search" id="site-search" name="q" placeholder="Busque o curso ideal para você"
          aria-label="Buscar cursos e bolsas"
          class="border border-zinc-300 w-full block rounded p-2"
      />
      <button type="submit" class="bg-blue-500 text-white p-2 rounded">Buscar</button>
    </form>
  </header>

  <aside>
    <form>
      <h1>Filtros</h1>

      <fieldset>
        <legend>Graduação</legend>

        <label for="bacharelado">
          <input type="checkbox" id="bacharelado"/>
          <span>Bacharelado</span>
          <small>(23)</small>
        </label>

        <label for="licenciatura">
          <input type="checkbox" id="licenciatura"/>
          <span>Licenciatura</span>
          <small>(10)</small>
        </label>

        <label for="tecnologo">
          <input type="checkbox" id="tecnologo"/>
          <span>Técnologo</span>
          <small>(98)</small>
        </label>
      </fieldset>

      <fieldset>
        <legend>Modalidade do curso</legend>

        <label for="presencial">
          <input type="checkbox" id="presencial"/>
          <span>Presencial</span>
          <small>(87)</small>
        </label>

        <label for="ead">
          <input type="checkbox" id="ead"/>
          <span>A distância - EaD</span>
          <small>(24)</small>
        </label>
      </fieldset>

      <fieldset>
        <legend>Turno do curso</legend>

        <label for="manha">
          <input type="checkbox" id="manha"/>
          <span>Manhã</span>
          <small>(87)</small>
        </label>

        <label for="tarde">
          <input type="checkbox" id="tarde"/>
          <span>Tarde</span>
          <small>(21)</small>
        </label>

        <label for="noite">
          <input type="checkbox" id="noite"/>
          <span>Noite</span>
          <span>(34)</span>
        </label>
      </fieldset>

      <fieldset>
        <legend>Preço da mensalidade</legend>

        <label for="mensalidade">
          <span>R$ <output for="mensalidade">500,00</output></span>
          <input type="range" id="mensalidade" min="0" max="1000" value="500"/>
        </label>
      </fieldset>
    </form>
  </aside>

  <main>
    <h1>Veja as opções que encontramos</h1>

    <button type="button">Ordenar</button>

    <ul>
      <li>
        <article>
          <figure>
            <img
                src="https://assets.querobolsa.com.br/logos/colorido/large/27/logo_1489432810.png"
                alt="Cruzeiro do Sul"
            >
            <figcaption>Cruzeiro do Sul</figcaption>
          </figure>
          <h2>Administração</h2>
          <span>4.8</span>
          <div>
            <svg
                xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="size-6"
            >
              <path
                  stroke-linecap="round" stroke-linejoin="round"
                  d="M11.48 3.499a.562.562 0 0 1 1.04 0l2.125 5.111a.563.563 0 0 0 .475.345l5.518.442c.499.04.701.663.321.988l-4.204 3.602a.563.563 0 0 0-.182.557l1.285 5.385a.562.562 0 0 1-.84.61l-4.725-2.885a.562.562 0 0 0-.586 0L6.982 20.54a.562.562 0 0 1-.84-.61l1.285-5.386a.562.562 0 0 0-.182-.557l-4.204-3.602a.562.562 0 0 1 .321-.988l5.518-.442a.563.563 0 0 0 .475-.345L11.48 3.5Z"
              />
            </svg>
            <svg
                xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="size-6"
            >
              <path
                  stroke-linecap="round" stroke-linejoin="round"
                  d="M11.48 3.499a.562.562 0 0 1 1.04 0l2.125 5.111a.563.563 0 0 0 .475.345l5.518.442c.499.04.701.663.321.988l-4.204 3.602a.563.563 0 0 0-.182.557l1.285 5.385a.562.562 0 0 1-.84.61l-4.725-2.885a.562.562 0 0 0-.586 0L6.982 20.54a.562.562 0 0 1-.84-.61l1.285-5.386a.562.562 0 0 0-.182-.557l-4.204-3.602a.562.562 0 0 1 .321-.988l5.518-.442a.563.563 0 0 0 .475-.345L11.48 3.5Z"
              />
            </svg>
            <svg
                xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="size-6"
            >
              <path
                  stroke-linecap="round" stroke-linejoin="round"
                  d="M11.48 3.499a.562.562 0 0 1 1.04 0l2.125 5.111a.563.563 0 0 0 .475.345l5.518.442c.499.04.701.663.321.988l-4.204 3.602a.563.563 0 0 0-.182.557l1.285 5.385a.562.562 0 0 1-.84.61l-4.725-2.885a.562.562 0 0 0-.586 0L6.982 20.54a.562.562 0 0 1-.84-.61l1.285-5.386a.562.562 0 0 0-.182-.557l-4.204-3.602a.562.562 0 0 1 .321-.988l5.518-.442a.563.563 0 0 0 .475-.345L11.48 3.5Z"
              />
            </svg>
            <svg
                xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="size-6"
            >
              <path
                  stroke-linecap="round" stroke-linejoin="round"
                  d="M11.48 3.499a.562.562 0 0 1 1.04 0l2.125 5.111a.563.563 0 0 0 .475.345l5.518.442c.499.04.701.663.321.988l-4.204 3.602a.563.563 0 0 0-.182.557l1.285 5.385a.562.562 0 0 1-.84.61l-4.725-2.885a.562.562 0 0 0-.586 0L6.982 20.54a.562.562 0 0 1-.84-.61l1.285-5.386a.562.562 0 0 0-.182-.557l-4.204-3.602a.562.562 0 0 1 .321-.988l5.518-.442a.563.563 0 0 0 .475-.345L11.48 3.5Z"
              />
            </svg>
            <svg
                xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 12 24" stroke-width="1.5"
                stroke="currentColor" class="size-6"
            >
              <path
                  stroke-linecap="round" stroke-linejoin="round"
                  d="M11.48 3.499a.562.562 0 0 0-1.04 0l-2.125 5.111a.563.563 0 0 1-.475.345l-5.518.442c-.499.04-.701.663-.321.988l4.204 3.602a.563.563 0 0 1 .182.557l-1.285 5.385a.562.562 0 0 0 .84.61l4.725-2.885a.562.562 0 0 1 .293-.08V3.499z"
              />
            </svg>
          </div>
          <p>
            <del>R$ 550,00</del>
            <ins>R$ 299,99</ins>
            <small>-27%</small>
          </p>
          <strong>Presencial</strong>
          <span>Graduação (bacharelado)</span>
          <a href="#">Quero esta bolsa</a>
        </article>
      </li>
    </ul>
  </main>

  <footer>
    <section>
      <p>Precisa de uma ajuda?</p>
      <a href="#">Fale conosco</a>
    </section>
    <section>
      <small>&copy; 2024 Quero Bolsa • CNPJ
        <data value="10542212000154">10.542.212/0001-54</data>
      </small>
    </section>
  </footer>
</template>