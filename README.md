# 🖥️ Desafio de Front-End - Quero Educação 🚀

Bem-vindo(a) ao desafio de front-end da **Quero Educação**! 🎉

Este desafio foi criado para avaliar suas habilidades em desenvolvimento de aplicações, com foco na implementação de
funcionalidades e correção de CSS. Vamos lá? 👇

---

## 📋 O Desafio

Seu objetivo é trabalhar em um projeto já iniciado, corrigindo alguns detalhes de **CSS** e implementando
funcionalidades em **JavaScript** utilizando **Vue 3**. Abaixo estão os detalhes das tarefas a serem realizadas:

### 🎨 Correção de CSS:

- [ ] Corrigir o layout da página:
    - [ ] A sidebar deve ficar fixa na lateral esquerda da página 📏.
    - [ ] A sidebar deve ter uma largura de 220px 📏.
    - [ ] A sidebar deve desaparecer em telas menores 📱 _(abaixo de 1023px)_.
    - [ ] O conteúdo principal deve ocupar o restante da largura da página 📏.
    - [ ] Ajuste o layout conforme necessário para melhorar a experiência do usuário 🎨.
- [ ] Ajustar a listagem de cards de ofertas com as seguintes regras:
    - [ ] Deve haver um espaçamento de 16px entre os cards 📏.
    - [ ] Exibir 1 card por linha em telas menores 📱 _(até 639px)_.
    - [ ] Exibir 2 cards por linha em telas médias 📱 _(640px ~ 767px)_.
    - [ ] Exibir 3 cards por linha em telas grandes 📱 _(768px ~ 1023px)_.
    - [ ] Exibir 4 cards por linha em telas extra grandes 📱 _(1024px ~ 1535px)_.
    - [ ] Exibir 5 cards por linha em telas maiores 📱 _(1536px ou mais)_.

### 🛠️ Implementação de Funcionalidades:

- [ ] Fazer uma requisição para a API de ofertas e exibir os cards na listagem 📦.
  _(`GET http://localhost:3000/offers`)_
- [ ] Exibir corretamente os detalhes do card:
    - [ ] O tipo `presencial` deve ser exibido como `Presencial` 🏫.
    - [ ] O tipo `ead` deve ser exibido como `EaD` 🏠.
    - [ ] O nível `bacharelado` deve ser exibido como `Graduação (bacharelado)` 🎓.
    - [ ] O nível `tecnologo` deve ser exibido como `Graduação (tecnólogo)` 🎓.
    - [ ] O nível `licenciatura` deve ser exibido como `Graduação (licenciatura)` 🎓.
    - [ ] Exibir a quantidade de estrelas de acordo com a propriedade `rating` 🌟.
    - [ ] Valores fracionados de `rating` devem exibir meia estrela 🌟 _(Ex: `4.9`)_.
    - [ ] Exibir os valores de `fullPrice` e `offeredPrice` no formato de moeda 💰 _(Ex: `R$ 550,00`)_.
    - [ ] Calcular e exibir a porcentagem de desconto com base nas propriedades `fullPrice` e `offeredPrice` 📉.
    - [ ] Exibir a porcentagem de desconto no formato `27%` 📉.
- [ ] Implementar a busca de ofertas pelo nome do curso 📝:
    - [ ] A busca deve ser realizada nos dados em memória, sem uma nova requisição 🔄.
    - [ ] A busca deve ser **case-insensitive** 🔄.
    - [ ] A busca só deve ser realizada após o usuário pressionar o botão de busca 🔍.
- [ ] Implementar a ordenação de ofertas 📊:
    - [ ] Permitir a ordenação pelo nome do curso 📝.
    - [ ] Permitir a ordenação pelo `offeredPrice` 📉.
    - [ ] Permitir a ordenação pelo `rating` 🌟.
- [ ] Implementar os filtros de ofertas 📌:
    - [ ] O filtro deve ser realizada nos dados em memória, sem uma nova requisição 🔄.
    - [ ] Permitir filtrar por `level` 🎓.
    - [ ] Permitir filtrar por `kind` 🏫.
    - [ ] Permitir filtrar pelo `offeredPrice` 📉 _(preço deve ser formatado como `R$ 550,00`)_.
    - [ ] Permitir aplicar múltiplos filtros simultaneamente 📌.

---

## ⚙️ Tecnologias Utilizadas

Este projeto utiliza as seguintes tecnologias:

- **Vue 3** 🖥️
- **CSS (Tailwind CSS)** 🎨
- **Typescript** 🧑‍💻

Sinta-se à vontade para utilizar CSS puro se preferir, isso não será um problema. 🚀

---

## 📝 Instruções para Iniciar

Certifique-se de ter o Node instalado na versão `20.x` ou superior.

Siga os passos abaixo para começar o desenvolvimento:

1. Instale as dependências:
   ```bash
   npm install
   ```

2. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```
   
3. Acesse a aplicação em `http://localhost:3001`.
4. Acesse a API de ofertas em `http://localhost:3000/offers`.

---

## 🧑‍💻 Como Entregar

Ao finalizar o desafio, siga os passos abaixo para enviar seu código:

1. Faça um **fork** deste repositório.
2. Suba suas alterações no **seu fork**.
3. Envie o link do repositório com suas alterações para o e-mail: `desafio@queroeducacao.com`.

---

## 📅 Prazo

Você tem até **[Data]** para concluir e enviar o desafio. Boa sorte! 🍀

---

## 🔍 O que Avaliamos

Os principais pontos que serão avaliados são:

- Qualidade na resolução de cada problema 📈.
- Organização e legibilidade do código 🧑‍💻.
- Boas práticas de desenvolvimento 🚀.
- Aderência às instruções do desafio 📝.
- Funcionamento correto das funcionalidades 🛠️.

---

## 💡 Dicas

O desafio foi intencionalmente projetado para não ser completamente resolvido em pouco tempo. Então fica tranquilo(a) se
não conseguir finalizar todas as tarefas, o importante é mostrar o seu conhecimento e habilidades. 🚀

Não existe uma ordem específica para realizar as tarefas, então sinta-se à vontade para começar por onde preferir. 🎯

Aqui vão algumas dicas para te ajudar a organizar o seu trabalho:

- Leia o desafio com atenção 📖.
- Compreenda o código existente antes de começar 🧐.
- Foque em uma tarefa por vez 🎯.
- Utilize checkboxes para marcar seu progresso 📝.

Em caso de dúvidas, entre em contato pelo e-mail: `email@quero.com`.

Boa sorte e bom código! 🚀
