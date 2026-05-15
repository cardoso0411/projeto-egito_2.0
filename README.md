# Volta ao Mundo Egito 2.0

Este projeto é uma continuação do trabalho original em [cardoso0411/volta_ao_mundo_egito](https://github.com/cardoso0411/volta_ao_mundo_egito). O objetivo é aperfeiçoar conhecimentos em desenvolvimento web, criar um site interativo com foco no Egito Antigo e aplicar técnicas de design, animação e usabilidade.

## Sobre o projeto

O site apresenta uma experiência temática de viagem ao Egito, com páginas dedicadas a locais históricos como as pirâmides de Gizé, a Esfinge, o rio Nilo, o Vale dos Reis, o Templo de Karnak e Abu Simbel. Inclui uma página especial de mapa interativo com estilo visual inspirado em jogos modernos, efeitos sonoros e interações durante a navegação.

## GitHub Pages

O projeto está disponível no GitHub Pages:

https://seu-usuario.github.io/projeto-egito_2.0/

## Estrutura do projeto

- `index.html` – página principal com introdução ao tema, navegação e seções principais.
- `mapa-interativo.html` – página com interação especial, animações e redirecionamento opcional via SweetAlert2.
- `abu-simbel.html` – página dedicada ao Templo de Abu Simbel.
- `esfinge.html` – página dedicada à Grande Esfinge.
- `piramides-gize.html` – página dedicada às Pirâmides de Gizé.
- `rio-nilo.html` – página sobre o Rio Nilo.
- `vale-dos-reis.html` – página sobre o Vale dos Reis.
- `templo-karnak.html` – página dedicada ao Templo de Karnak.
- `script.js` – lógica JavaScript para interação, animação, navegação suave, tabs, modal de galeria e formulário.
- `styles.css` – estilo personalizado do site.
- `img/` – imagens temáticas utilizadas nas páginas.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- Tailwind CSS via CDN para rápida prototipação e design responsivo
- Google Fonts (`Cinzel`, `Lato`, `Press Start 2P`) para estilo tipográfico
- Animate.css para animações de entrada suaves
- Anime.js para animações de elementos e microinterações
- Vanta.js (`VANTA.NET`) para efeitos de plano de fundo dinâmico
- Howler.js para controle de áudio e trilha sonora interativa
- SweetAlert2 para mensagens de confirmação com estilo moderno
- Lucide Icons para ícones leves e consistentes

## Funcionalidades principais

- Layout responsivo para web e mobile
- Menu mobile com botão hambúrguer e overlay
- Navegação suave para âncoras internas
- Header dinâmico que muda ao rolar a página
- Animações de fade-in com Intersection Observer
- Tabs interativas para conteúdos culturais
- Botões de "Saiba Mais" com notificações em toast
- Modal de galeria para visualização ampliada de imagens
- Formulário de contato simulado com feedback de envio
- Página de mapa interativo com alertas customizados e redirecionamento

## O que este projeto ajudou a aprender

- Como usar bibliotecas externas via CDN
- Manipulação de DOM usando JavaScript puro
- Criação de interfaces interativas e responsivas
- Uso de APIs modernas do navegador como `IntersectionObserver`
- Animação de elementos com bibliotecas como Anime.js
- Como organizar páginas estáticas em um site multipágina
- Como aplicar design visual temático com cores e tipografia coerentes

## Como usar

1. Clone ou baixe o repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Navegue entre as páginas para explorar o conteúdo e as interações.

> Recomendo abrir com um servidor local se quiser testar funcionalidades que dependem de recursos externos e evitar possíveis bloqueios de CORS em navegadores mais restritivos.

## Inspiração

Esse projeto foi feito como uma evolução do trabalho original do GitHub e como forma de praticar desenvolvimento web, design de interfaces e uso de bibliotecas modernas em um site estático.