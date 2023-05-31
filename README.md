# Projeto de extensão: Movie Challenge

## Índice

- [1. Preâmbulo](#1-preâmbulo)
- [2. Resumo do projeto](#2-resumo-do-projeto)
- [3. Considerações gerais](#3-considerações-gerais)
- [4. Objetivos de aprendizagem](#4-objetivos-de-aprendizagem)
- [5. Critérios de aceitação mínimos do projeto](#5-critérios-de-aceitação-minimos-do-projeto)
- [6. Considerações técnicas](#6-considerações-tecnicas)

---

## 1. Preâmbulo

A forma que vemos filmes mudou radicalmente durante os últimos anos
devido, em parte, a aparição dos serviços de  [_streaming_](https://pt.wikipedia.org/wiki/Streaming)
que nos permite assistir em qualquer lugar e momento. O melhor reflexo
deste fenômeno é o sucesso da Netflix, HBO e Disney+, etc.

Em tempos em que uma das principais ferramentas para combater [a pandemia
de Covid-19](https://pt.wikipedia.org/wiki/COVID-19) é [evitar](https://pt.wikipedia.org/wiki/Distanciamento_social)
compartilhar espaços com muitas pessoas (como no cinema), e assistir _streaming_
será uma das poucas formas (ou a única) de ver filmes.

Acreditamos que há uma grande oportunidade de propor produtos/experiências inovadoras
de tudo tipo utilizando dados de filmes (directorxs, atores/atrizes, sagas, sequências,
datas, etc.). Poderíamos pensar em jogos, comunidades, catálogos, recomendações
baseadas em gostos pessoais, etc. (apenas para mencionar algumas ideias obvias).

![Pelis](https://live.staticflickr.com/117/257368762_38bf6fcf9f_h.jpg)

## 2. Resumo do projeto

A ideia deste projeto é que, usando uma API com informações de filmes,
possa idealizar, planejar, organizar e desenvolver uma aplicação web que aproveite
estes dados e tenha uma proposta de valor atrativa para os usuários.

Ainda que a decisão do que fazer é inteiramente sua, há algumas considerações
gerais que se apresentam a seguir. Pode atender esses requisitos em
projetos muitos distintos, depende de sua criatividade e do entendimento
dos seus potenciais usuários!

## 3. Considerações gerais

- Este projeto deve ser feito em equipes de 2 ou mais pessoas.
- Devem escolher qual problema ou necessidades estão resolvendo com o
produto que estão desenhando e desenvolvendo.
- Devem utilizar os dados da API de [OMDB](http://www.omdbapi.com/) (The Open
Movie Database) com [Fetch](https://developer.mozilla.org/es/docs/Web/API/Fetch_API)
ou qualquer outra API que encontrem.
- Pensem em _test driven development_ no momento de programar a
solução. Terão que escrever os testes unitários, aproveitem a oportunidade
de fazer-lo antes de escrever a funcionalidade.
- Este projeto é "agnóstico" a tecnologia, ou seja, podem desenvolver
em Vanilla JavaScript ou em algum _framework_ ou biblioteca de sua escolha.
- Pense em um escopo que, considerando a sua complexidade e a quantidade de
pessoas na equipe, permita a conclusão do projeto em 2 semanas.

## 4. Objetivos de aprendizagem

Reflita e depois enumere os objetivos que quer alcançar e aplique no seu projeto. Pense nisso para decidir sua estratégia de trabalho.

### HTML

- [ ] **Uso de HTML semântico**

  <details><summary>Links</summary><p>

  * [HTML semântico](https://curriculum.laboratoria.la/pt/topics/html/02-html5/02-semantic-html)
  * [Semantics in HTML - MDN](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#Semantics_in_HTML)
</p></details>

### CSS

- [ ] **Uso de seletores de CSS**

  <details><summary>Links</summary><p>

  * [Intro a CSS](https://curriculum.laboratoria.la/pt/topics/css/01-css/01-intro-css)
  * [CSS Selectors - MDN](https://developer.mozilla.org/pt_BR/docs/Web/CSS/CSS_Selectors)
</p></details>

- [ ] **Modelo de caixa (box model): borda, margem, preenchimento**

  <details><summary>Links</summary><p>

  * [Modelo de Caixa e Display](https://curriculum.laboratoria.la/pt/topics/css/01-css/02-boxmodel-and-display)
  * [The box model - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
  * [Introduction to the CSS box model - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
  * [CSS display - MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS/display)
  * [display - CSS Tricks](https://css-tricks.com/almanac/properties/d/display/)
</p></details>

- [ ] **Uso de flexbox em CSS**

  <details><summary>Links</summary><p>

  * [A Complete Guide to Flexbox - CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  * [Flexbox Froggy](https://flexboxfroggy.com/#pt-br)
  * [Flexbox - MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
</p></details>

### Web APIs

- [ ] **Uso de seletores de DOM**

  <details><summary>Links</summary><p>

  * [Modificando o DOM](https://curriculum.laboratoria.la/pt/topics/browser/02-dom/03-1-dom-methods-selection)
  * [Introdução ao DOM - MDN](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction)
  * [Locating DOM elements using selectors - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Document_object_model/Locating_DOM_elements_using_selectors)
</p></details>

- [ ] **Manipulação de eventos de DOM (listeners, propagação, delegação)**

  <details><summary>Links</summary><p>

  * [Introdução a eventos - MDN](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Building_blocks/Events)
  * [EventTarget.addEventListener() - MDN](https://developer.mozilla.org/pt-BR/docs/Web/API/EventTarget/addEventListener)
  * [EventTarget.removeEventListener() - MDN](https://developer.mozilla.org/pt-BR/docs/Web/API/EventTarget/removeEventListener)
  * [Objeto Event](https://developer.mozilla.org/pt-BR/docs/Web/API/Event)
</p></details>

- [ ] **Manipulação dinâmica de DOM**

  <details><summary>Links</summary><p>

  * [Introdução ao DOM](https://developer.mozilla.org/pt-BR/docs/DOM/Referencia_do_DOM/Introdu%C3%A7%C3%A3o)
  * [Node.appendChild() - MDN](https://developer.mozilla.org/pt-BR/docs/Web/API/Node/appendChild)
  * [Document.createElement() - MDN](https://developer.mozilla.org/pt-BR/docs/Web/API/Document/createElement)
  * [Document.createTextNode()](https://developer.mozilla.org/pt-BR/docs/Web/API/Document/createTextNode)
  * [Element.innerHTML - MDN](https://developer.mozilla.org/pt-BR/docs/Web/API/Element/innerHTML)
  * [Node.textContent - MDN](https://developer.mozilla.org/pt-BR/docs/Web/API/Node/textContent)
</p></details>

### JavaScript

- [ ] **Diferenciar entre tipos de dados primitivos e não primitivos**

- [ ] **Arrays (arranjos)**

  <details><summary>Links</summary><p>

  * [Arranjos](https://curriculum.laboratoria.la/pt/topics/javascript/04-arrays)
  * [Array - MDN](https://developer.mozilla.org//pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/)
  * [Array.prototype.sort() - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)
  * [Array.prototype.forEach() - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
  * [Array.prototype.map() - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
  * [Array.prototype.filter() - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
  * [Array.prototype.reduce() - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
</p></details>

- [ ] **Objetos (key, value)**

  <details><summary>Links</summary><p>

  * [Objetos em JavaScript](https://curriculum.laboratoria.la/pt/topics/javascript/05-objects/01-objects)
</p></details>

- [ ] **Variáveis (declaração, atribuição, escopo)**

  <details><summary>Links</summary><p>

  * [Valores, tipos de dados e operadores](https://curriculum.laboratoria.la/pt/topics/javascript/01-basics/01-values-variables-and-types)
  * [Variáveis](https://curriculum.laboratoria.la/pt/topics/javascript/01-basics/02-variables)
</p></details>

- [ ] **Uso de condicionais (if-else, switch, operador ternário, lógica booleana)**

  <details><summary>Links</summary><p>

  * [Estruturas condicionais e repetitivas](https://curriculum.laboratoria.la/pt/topics/javascript/02-flow-control/01-conditionals-and-loops)
  * [Tomando decisões no seu código — condicionais - MDN](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Building_blocks/conditionals)
</p></details>

- [ ] **Uso de laços (while, for, for..of)**

  <details><summary>Links</summary><p>

  * [Laços (Loops)](https://curriculum.laboratoria.la/pt/topics/javascript/02-flow-control/02-loops)
  * [Laços e iterações - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Loops_and_iteration)
</p></details>

- [ ] **Funções (params, args, return)**

  <details><summary>Links</summary><p>

  * [Funções (controle de fluxo)](https://curriculum.laboratoria.la/pt/topics/javascript/02-flow-control/03-functions)
  * [Funções clássicas](https://curriculum.laboratoria.la/pt/topics/javascript/03-functions/01-classic)
  * [Arrow Functions](https://curriculum.laboratoria.la/pt/topics/javascript/03-functions/02-arrow)
  * [Funções — blocos reutilizáveis de código - MDN](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Building_blocks/Functions)
</p></details>

- [ ] **Testes unitários (unit tests)**

  <details><summary>Links</summary><p>

  * [Introdução ao Jest - Documentação oficial](https://jestjs.io/docs/pt-BR/getting-started)
</p></details>

- [ ] **Módulos de ECMAScript (ES modules)**

  <details><summary>Links</summary><p>

  * [import - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/import)
  * [export - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/export)
</p></details>

- [ ] **Uso de linter (ESLINT)**

- [ ] **Uso de identificadores descritivos (Nomenclatura e Semântica)**

- [ ] **Diferença entre expressões (expressions) e declarações (statements)**

### Controle de Versões (Git e GitHub)

- [ ] **Git: Instalação e configuração**

- [ ] **Git: Controle de versão com git (init, clone, add, commit, status, push, pull, remote)**

- [ ] **Git: Integração de mudanças entre ramos (branch, checkout, fetch, merge, reset, rebase, tag)**

- [ ] **GitHub: Criação de contas e repositórios, configuração de chave SSH**

- [ ] **GitHub: Implantação com GitHub Pages**

  <details><summary>Links</summary><p>

  * [Site oficial do GitHub Pages](https://pages.github.com/)
</p></details>

- [ ] **GitHub: Colaboração pelo Github (branches | forks | pull requests | code review | tags)**

### Centrado no usuário

- [ ] **Desenhar e desenvolver um produto ou serviço colocando as usuárias no centro**

### Design de produto

- [ ] **Criar protótipos para obter feedback e iterar**

- [ ] **Aplicar os princípios de desenho visual (contraste, alinhamento, hierarquia)**

### Pesquisa

- [ ] **Planejar e executar testes de usabilidade**

## 5. Critérios de aceitação mínimos do projeto

- Utilizar a API de OMDB usando _Fetch_ para obter e mostrar uma interface baseada
nos dados de cada resposta.
- Independentemente do que decida fazer, deve selecionar dados aleatoriamente e mostrar-los
em alguma das características de seu projeto. Para isto geralmente
se usa o método `random` do objeto `Math` em JavaScript.
- Sua solução deve ser _responsive_. Deve se adaptar as telas desktop,
tablets e celulares.
- Deve implantar a sua aplicação usando [GitHub Pages](https://pages.github.com/).

## 6. Considerações técnicas

- Para usar a API de OMDB deve criar uma chave (_key_) de acesso e adiciona-la
em cada requisição que faça ao servidor (revisar seção _Usage_ de sua [documentação](http://www.omdbapi.com/)).
A chave pode ser gerada neste [link](http://www.omdbapi.com/apikey.aspx) preenchendo
o formulário com a versão gratuita (_free_) selecionada, precisando verificar seu
_email_ para ativar e usá-la.
- Lembre que o GitHub Pages serve suas páginas com um certificado [SSL](https://pt.wikipedia.org/wiki/Transport_Layer_Security),
portanto as requisições a OMDB devem incluir `https` na URL.
- Lembre que há um limite de 1.000 requisições diárias à API de OMDB
para cada [IP](https://pt.wikipedia.org/wiki/Endere%C3%A7o_IP). Acreditamos que é
suficiente, mas te recomendamos o uso responsável deste recurso gratuito.

## Conteúdo de referência

- [Fetch](https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API)
- [Math.random](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Math/random)

Se divirta e comece esta aventura 🎬!
