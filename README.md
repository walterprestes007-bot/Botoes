🎨 Button Lab 2.0

Button Lab 2.0 é um projeto educacional desenvolvido para estudar, na prática, a criação de interfaces web utilizando HTML, CSS e JavaScript.

O projeto reúne 50 exemplos diferentes de botões e componentes interativos, indo desde botões básicos até efeitos mais avançados, como neon, glassmorphism, holográfico, animações 3D, progresso circular, confirmação por deslize, long press, clipboard e efeitos controlados por JavaScript.

A proposta principal não é apenas mostrar botões prontos, mas servir como um laboratório de estudos de Front-End, permitindo entender como estrutura, aparência, animação e comportamento trabalham juntos.

📌 Sumário

Sobre o projeto

Objetivos

Funcionalidades

Os 50 exemplos

Tecnologias utilizadas

Estrutura do projeto

Como executar

Como estudar o projeto

HTML

CSS

JavaScript

Eventos utilizados

Acessibilidade

Responsividade

Animações

Interações JavaScript

Conceitos importantes

Guia dos 50 botões

Desafios para estudo

Possíveis melhorias

Objetivo acadêmico

Autor

📖 Sobre o projeto

O Button Lab 2.0 funciona como uma coleção interativa de componentes de interface.

Cada cartão da página apresenta:

O nome do efeito ou tipo de botão.

Uma explicação resumida.

Uma demonstração visual.

Interações de mouse, teclado ou toque quando necessárias.

A página possui uma aparência moderna, utilizando:

Tema escuro.

Gradientes.

Efeitos de brilho.

Glassmorphism.

Cartões com elevação.

Animações.

Layout responsivo.

Barra de pesquisa/filtros.

Alternância de tema claro/escuro.

Notificações visuais.

O projeto foi estruturado para que seja possível estudar cada efeito separadamente.

🎯 Objetivos

O projeto possui quatro objetivos principais.

1. Aprender HTML

Entender como estruturar componentes utilizando:

<button>

além de elementos como:

<span>
<div>
<a>

e atributos personalizados:

data-*

2. Aprender CSS

Praticar propriedades e recursos como:

background

linear-gradient

radial-gradient

border

border-radius

box-shadow

text-shadow

transform

transition

animation

@keyframes

::before

::after

clip-path

backdrop-filter

color-mix

variáveis CSS

responsividade

3. Aprender JavaScript

Praticar:

Seleção de elementos.

Eventos.

Manipulação de classes.

Manipulação de atributos.

Timers.

Animações controladas por código.

Clipboard.

Eventos de mouse.

Eventos de toque.

Interação com o DOM.

4. Entender Front-End na prática

O projeto demonstra uma ideia fundamental:

HTML
  ↓
Estrutura

CSS
  ↓
Visual + animações

JavaScript
  ↓
Comportamento + interação

Essas três tecnologias trabalham juntas para transformar elementos HTML simples em componentes interativos.

✨ Funcionalidades

O projeto possui uma página de laboratório com diversos recursos.

🔎 Pesquisa

Permite localizar exemplos de botões através de uma barra de pesquisa.

🏷️ Filtros

Os exemplos podem ser organizados/filtrados por categoria.

🌙 Tema

O projeto possui suporte visual para tema claro através da classe:

body.classList.add("light")

🔔 Notificações

Diversos exemplos utilizam uma função de notificação para mostrar ao usuário o resultado de uma interação.

📋 Clipboard

O botão de cópia utiliza:

navigator.clipboard.writeText()

para copiar conteúdo.

📱 Mouse e Touch

Alguns componentes possuem suporte tanto para:

mouse;

toque.

Isso é especialmente importante em exemplos como Long Press e Slide to Confirm.

🧩 Os 50 exemplos

O projeto apresenta os seguintes exemplos:

Nº

Exemplo

Conceito principal

01

Primary

Botão principal

02

Secondary

Ação secundária

03

Outline

Borda sem preenchimento

04

Ghost

Botão transparente

05

Danger

Ação destrutiva

06

Success

Confirmação

07

Warning

Aviso

08

Neon Glow

Brilho neon

09

Gradient

Gradientes animados

10

3D

Profundidade

11

Pill

Formato cápsula

12

Ícones

Botões circulares

13

Loading

Estado de carregamento

14

Toggle

Alternância

15

Ripple

Efeito de onda

16

Shine

Reflexo/brilho

17

Magnetic

Movimento magnético

18

Animated Border

Borda animada

19

Glassmorphism

Efeito vidro

20

Gradient Border

Borda com gradiente

21

Cut Corner

Cantos recortados

22

Holographic

Efeito holográfico

23

Social

Botões sociais

24

Login CTA

Chamada para login

25

Download

Progresso de download

26

Copy

Cópia para clipboard

27

Disabled

Estado desabilitado

28

Link

Botão com comportamento de link

29

Hamburger

Menu hambúrguer

30

Squishy

Efeito de compressão

31

Flip 3D

Giro tridimensional

32

Liquid

Efeito líquido

33

Pulse

Pulsação

34

Typing

Efeito de digitação

35

Alert

Alerta

36

Double Click

Duplo clique

37

Long Press

Pressão prolongada

38

Confirm

Confirmação

39

Split Button

Botão dividido

40

Progress Circular

Progresso circular

41

Cursor

Interação com cursor

42

Double Border

Dupla borda

43

Hover Text

Texto alterado no hover

44

Scan

Efeito de escaneamento

45

Orbit

Movimento orbital

46

Falling

Elementos em queda

47

Gooey

Efeito viscoso

48

Slide to Confirm

Confirmação por deslize

49

Notification

Notificações

50

Favorite

Favoritar/desfavoritar

🛠️ Tecnologias utilizadas

HTML5

Utilizado para estruturar:

Página.

Títulos.

Descrições.

Cartões.

Botões.

Campos de pesquisa.

Controles.

Elementos de demonstração.

CSS3

Responsável pela identidade visual e pelos efeitos.

Principais recursos:

:root

para variáveis;

:hover
:active

para estados;

::before
::after

para pseudo-elementos;

@keyframes

para animações;

transform

para movimento;

box-shadow

para profundidade e brilho.

JavaScript

Responsável pelas interações que não podem ser resolvidas somente com CSS.

Exemplos:

addEventListener()

classList.toggle()

setTimeout()

setInterval()

navigator.clipboard.writeText()

📂 Estrutura do projeto

A estrutura principal é:

botoes/
│
├── index.html
├── style.css
├── script.js
├── README.md
│
├── .vscode/
│   └── settings.json
│
├── projeto-botoes-css-js-v2/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   └── README.md
│
└── suporte_botoes/
    ├── Button_Lab_2_Notion.md
    └── Button Lab 2.0 — Guia Completo de CSS + JavaScript.pdf

O ZIP também contém uma cópia compactada da versão projeto-botoes-css-js-v2.

📄 Arquivos principais

index.html

É a estrutura da página.

Nele ficam:

Cabeçalho.

Título.

Barra de ferramentas.

Pesquisa.

Filtros.

Cartões.

Demonstrações.

Botões.

Elementos usados pelos efeitos.

O HTML define o que existe na página.

style.css

É responsável pela apresentação visual.

Contém:

Variáveis de cores.

Tema claro.

Layout.

Grid.

Cards.

Botões.

Hover.

Active.

Animações.

Pseudo-elementos.

Efeitos visuais.

Responsividade.

O CSS define como as coisas aparecem.

script.js

Controla as interações.

Ele localiza os componentes com:

document.querySelectorAll()

e adiciona comportamentos através de:

addEventListener()

O JavaScript define o que acontece quando o usuário interage.

Button_Lab_2_Notion.md

É um material complementar de estudo.

Ele explica detalhadamente:

HTML.

CSS.

JavaScript.

Fundamentos.

Exemplos.

Os diferentes efeitos.

Como estudar os componentes.

PDF de suporte

A pasta suporte_botoes também possui um PDF:

Button Lab 2.0 — Guia Completo de CSS + JavaScript.pdf

Ele serve como material de apoio para estudar os conceitos do laboratório.

🚀 Como executar

Como o projeto utiliza HTML, CSS e JavaScript puro, não é necessário instalar Node.js ou um framework para executá-lo.

Método 1 — Abrindo diretamente

Entre na pasta:

botoes/

e abra:

index.html

no navegador.

Método 2 — VS Code + Live Server

A forma recomendada para desenvolvimento é utilizar o VS Code.

Passo 1

Abra a pasta no VS Code.

Passo 2

Abra:

index.html

Passo 3

Instale a extensão:

Live Server

Passo 4

Clique com o botão direito em index.html.

Selecione:

Open with Live Server

O navegador será aberto automaticamente.

🧠 Como estudar o projeto

A melhor maneira de aprender com o Button Lab não é simplesmente copiar o código.

Use este processo:

1. Escolha um botão

Por exemplo:

Neon Glow

2. Leia o HTML

Descubra:

Qual elemento foi utilizado?

Quais classes existem?

Existem span?

Existem data-*?

Existem atributos aria-*?

3. Leia o CSS

Identifique:

Fundo.

Borda.

Sombra.

Transformações.

Transições.

Pseudo-elementos.

Animações.

4. Leia o JavaScript

Veja se existe:

addEventListener()

ou:

setTimeout()

ou:

setInterval()

5. Tente modificar

Mude:

Cores.

Velocidade.

Tamanho.

Texto.

Intensidade do efeito.

6. Tente recriar

Feche o código e tente fazer uma versão própria.

Esse processo ensina muito mais do que simplesmente copiar.

🧱 HTML

O HTML é a camada estrutural.

Um botão simples pode ser:

<button class="btn btn-primary">
  Entrar
</button>

O navegador entende:

button
└── conteúdo: Entrar

O CSS pode então localizar:

.btn-primary

e alterar sua aparência.

🎨 CSS

O projeto utiliza várias técnicas modernas.

Variáveis CSS

No início do CSS existem variáveis como:

:root {
  --bg: #090b11;
  --panel: #11151e;
  --text: #f5f7fb;
  --muted: #9da6b8;
  --accent: #8b5cf6;
}

Depois elas podem ser utilizadas:

color: var(--text);

Isso facilita a manutenção.

Se quiser alterar a cor principal do projeto, é possível alterar a variável em um único lugar.

Gradientes

Exemplo:

background:
  linear-gradient(
    135deg,
    #7c3aed,
    #5b21b6
  );

Um gradiente mistura duas ou mais cores.

Sombras

Exemplo:

box-shadow:
  0 10px 24px
  rgba(124, 58, 237, 0.28);

As sombras são utilizadas para criar:

profundidade;

brilho;

destaque;

efeito neon.

Transform

Exemplo:

transform: translateY(-2px);

Move o botão para cima.

Outro exemplo:

transform: scale(1.08);

Aumenta o botão.

Transitions

Exemplo:

transition:
  transform 0.18s ease,
  box-shadow 0.18s ease;

Sem transição, as mudanças podem acontecer instantaneamente.

Com transition, elas ficam suaves.

⚙️ JavaScript

O JavaScript é utilizado principalmente para comportamentos interativos.

Selecionando elementos

Exemplo:

document
  .querySelectorAll(".favorite-btn")

Isso localiza todos os elementos que possuem a classe:

favorite-btn

Eventos

Exemplo:

button.addEventListener("click", () => {
  // ação
});

Isso significa:

Quando o usuário clicar no botão, execute essa função.

ClassList

O projeto utiliza bastante:

classList.add()

classList.remove()

classList.toggle()

Exemplo:

button.classList.toggle("active");

Isso alterna uma classe.

⏱️ Timers

O projeto utiliza:

setTimeout()

para executar algo depois de determinado período.

Exemplo:

setTimeout(() => {
  button.textContent = "Pronto!";
}, 1200);

Também utiliza:

setInterval()

para executar algo repetidamente.

Exemplo:

setInterval(() => {
  progress += 10;
}, 100);

📋 Clipboard

O botão Copy utiliza:

navigator.clipboard.writeText(value);

Isso permite copiar texto para a área de transferência do sistema.

O fluxo é:

Clique
  ↓
Pega data-copy
  ↓
Clipboard API
  ↓
Texto copiado
  ↓
Botão mostra "Copiado!"
  ↓
Notificação

🖱️ Eventos utilizados

O projeto trabalha com vários eventos.

Clique

click

Duplo clique

dblclick

Mouse entrando

mouseenter

Mouse saindo

mouseleave

Pressionar mouse

mousedown

Soltar mouse

mouseup

Movimento do mouse

mousemove

Toque

touchstart
touchmove
touchend

Isso permite que alguns efeitos funcionem também em dispositivos touch.

♿ Acessibilidade

O projeto também demonstra algumas práticas importantes de acessibilidade.

Um exemplo é:

aria-expanded="false"

Esse atributo pode informar a leitores de tela se determinado controle está aberto ou fechado.

No menu hambúrguer, o JavaScript atualiza:

button.setAttribute(
  "aria-expanded",
  String(isOpen)
);

Também atualiza:

aria-label

entre:

Abrir menu

e:

Fechar menu

Isso demonstra que efeitos visuais não devem ser pensados apenas para aparência.

📱 Responsividade

A página utiliza um grid responsivo.

A ideia é adaptar automaticamente a quantidade de cartões por linha.

O CSS utiliza:

grid-template-columns:
  repeat(
    auto-fit,
    minmax(280px, 1fr)
  );

Isso permite que os cards se ajustem de acordo com o espaço disponível.

Em uma tela grande:

┌──────┐ ┌──────┐ ┌──────┐
│ Card │ │ Card │ │ Card │
└──────┘ └──────┘ └──────┘

Em uma tela menor:

┌──────────┐
│   Card   │
└──────────┘

┌──────────┐
│   Card   │
└──────────┘

🎞️ Animações

O CSS utiliza @keyframes.

Exemplo:

@keyframes rotate {
  to {
    transform: rotate(360deg);
  }
}

Depois:

animation:
  rotate 0.7s linear infinite;

O resultado é uma animação contínua.

Outro exemplo é o movimento de gradiente:

@keyframes gradientMove {
  to {
    background-position: 200% center;
  }
}

🔥 Interações JavaScript

Alguns exemplos possuem comportamentos mais avançados.

Hamburger

Ao clicar:

button.classList.toggle("open");

A classe muda e o CSS pode representar o estado aberto.

Squishy

O JavaScript remove e adiciona novamente a classe:

button.classList.remove("squish");

void button.offsetWidth;

button.classList.add("squish");

O:

void button.offsetWidth;

é utilizado para forçar o navegador a recalcular o layout e permitir que a animação seja reiniciada.

Download

O botão simula um progresso:

0%
20%
40%
60%
80%
100%

O processo utiliza:

setInterval()

Depois de concluir, o botão informa:

✓ Download concluído

É uma simulação visual de download e não representa necessariamente uma transferência real de arquivo.

Double Click

O evento:

dblclick

é utilizado para detectar dois cliques rápidos.

Quando ocorre:

❤️ Clique 2x

é alterado para:

💖 Curtido!

Long Press

A pressão longa utiliza:

mousedown

e:

touchstart

Um timer é iniciado.

Se o usuário mantiver o botão pressionado por aproximadamente 1 segundo, a ação é confirmada.

Split Button

É um componente dividido em duas partes:

┌───────────────┬───┐
│    Salvar     │ ▼ │
└───────────────┴───┘

A parte principal executa uma ação.

A seta abre opções adicionais.

Progress Circular

O progresso circular utiliza:

conic-gradient()

O JavaScript transforma porcentagem em graus:

0%   = 0°
25%  = 90°
50%  = 180°
75%  = 270°
100% = 360°

A fórmula utilizada é:

graus = progresso × 3,6

Hover Text

O texto muda quando o mouse entra:

mouseenter

e volta ao original quando sai:

mouseleave

Os textos podem ser armazenados em atributos:

data-default
data-hover

Notification

O botão de notificações lê o contador atual e depois o zera.

O projeto também aplica uma animação ao ícone para representar a interação.

Favorite

O favorito utiliza:

classList.toggle("active")

e troca o ícone:

♡

para:

♥

Também atualiza:

aria-label

para indicar a ação disponível.

Slide to Confirm

Esse componente permite arrastar um botão para confirmar uma ação.

O processo é:

Início
  ↓
Usuário segura
  ↓
Arrasta para a direita
  ↓
Calcula distância
  ↓
Chega ao limite
  ↓
✓ Confirmado

O JavaScript utiliza coordenadas do ponteiro para calcular o deslocamento.

🧠 Conceitos importantes

DOM

DOM significa Document Object Model.

É a representação da página que o JavaScript consegue manipular.

Por exemplo:

document.querySelector(".btn")

procura um elemento dentro do DOM.

Dataset

Atributos:

data-copy="npm install"

podem ser acessados através de:

button.dataset.copy

Isso é útil para guardar pequenas informações associadas a um elemento.

Estado

Um botão pode ter estados diferentes:

Normal
Hover
Active
Loading
Disabled
Completed

O projeto demonstra como CSS e JavaScript podem controlar esses estados.

📚 Guia rápido dos 50 exemplos

01–07 — Fundamentos

São os botões básicos para entender hierarquia visual:

Primary
Secondary
Outline
Ghost
Danger
Success
Warning

08–12 — Estilos

Introduzem:

Neon
Gradient
3D
Pill
Ícones

13–20 — Microinterações

Introduzem:

Loading
Toggle
Ripple
Shine
Magnetic
Animated Border
Glassmorphism
Gradient Border

21–28 — Efeitos e componentes

Incluem:

Cut Corner
Holographic
Social
Login CTA
Download
Copy
Disabled
Link

29–35 — Interações

Incluem:

Hamburger
Squishy
Flip 3D
Liquid
Pulse
Typing
Alert

36–43 — JavaScript e estados

Incluem:

Double Click
Long Press
Confirm
Split Button
Progress Circular
Cursor
Double Border
Hover Text

44–50 — Efeitos avançados

Incluem:

Scan
Orbit
Falling
Gooey
Slide to Confirm
Notification
Favorite

🧪 Desafios para estudo

Depois de entender os exemplos existentes, tente criar componentes novos.

Desafio 1 — Botão de partículas

Ao clicar, pequenas partículas devem aparecer ao redor do botão.

Desafio 2 — Botão de fogo

Crie um botão com:

brilho;

partículas;

animação;

mudança de cor.

Desafio 3 — Botão de som

Ao clicar:

🔊 Som ligado

e novamente:

🔇 Som desligado

Desafio 4 — Botão de tema

Crie um botão que alterne:

🌙 Dark
☀️ Light

Desafio 5 — Botão de carregamento real

Crie um botão que:

Mostre Carregando....

Desabilite o botão.

Aguarde.

Mostre Concluído.

Volte ao estado normal.

🚀 Possíveis melhorias

O projeto pode evoluir bastante.

Organização

Separar os estilos em arquivos:

css/
├── base.css
├── buttons.css
├── animations.css
├── themes.css
└── responsive.css

JavaScript modular

Criar módulos:

js/
├── search.js
├── theme.js
├── notifications.js
├── buttons.js
└── utils.js

Componentes reutilizáveis

Criar funções para gerar botões dinamicamente.

Testes

Adicionar testes para garantir que:

Favorito funciona.

Clipboard funciona.

Progress funciona.

Toggle funciona.

Slide confirma corretamente.

Acessibilidade

Adicionar:

suporte completo a teclado;

foco visual;

aria-label;

aria-pressed;

aria-live;

contraste adequado;

redução de movimento com prefers-reduced-motion.

Produção

Caso o projeto seja utilizado em um sistema real, recomenda-se:

reduzir CSS não utilizado;

otimizar animações;

separar componentes;

evitar listeners desnecessários;

testar navegadores diferentes;

testar dispositivos touch;

melhorar acessibilidade.

🎓 Objetivo acadêmico

O Button Lab 2.0 pode ser utilizado como projeto de estudo ou apresentação para demonstrar conhecimentos em Desenvolvimento Web / Front-End.

Os principais conhecimentos demonstrados são:

HTML

Estrutura
Semântica
Formulários
Botões
Atributos
data-*
aria-*

CSS

Layout
Grid
Flexbox
Cores
Gradientes
Sombras
Pseudo-elementos
Transformações
Transições
Animações
Responsividade

JavaScript

DOM
Eventos
Classes
Timers
Clipboard
Mouse
Touch
Estados
Manipulação de atributos

📝 Forma recomendada de apresentar

Uma explicação simples para qualquer botão pode seguir quatro perguntas:

1. O que existe?

HTML.

<button>Salvar</button>

2. Como ele parece?

CSS.

button {
  background: purple;
}

3. O que acontece quando passo o mouse?

Pseudo-classe:

button:hover {
  transform: scale(1.05);
}

4. O que acontece quando clico?

JavaScript:

button.addEventListener("click", () => {
  // ação
});

Essa sequência facilita bastante a compreensão do projeto:

ESTRUTURA
   ↓
HTML
   ↓
APARÊNCIA
   ↓
CSS
   ↓
INTERAÇÃO
   ↓
JAVASCRIPT
   ↓
EXPERIÊNCIA DO USUÁRIO

📦 Conteúdo do pacote

O arquivo disponibilizado contém:

botoes/
│
├── Projeto principal
├── Segunda versão do projeto
├── Material de estudo
├── PDF de apoio
└── Arquivos de configuração

O projeto principal pode ser executado diretamente pelo navegador, enquanto os arquivos da pasta suporte_botoes servem como material complementar.

⚠️ Observações

Alguns efeitos são demonstrações visuais.

Por exemplo, o botão de download simula uma barra de progresso, mas não necessariamente realiza uma transferência real de arquivo.

Da mesma forma, componentes como login, confirmação, favoritos e notificações demonstram a interação no navegador, mas não representam necessariamente um sistema conectado a um backend ou banco de dados.

Para transformar esses componentes em funcionalidades reais, seria necessário conectá-los a serviços, APIs ou um backend.

👨‍💻 Autor

Walter Prestes

Projeto desenvolvido para estudos de:

HTML + CSS + JavaScript

Área:

Desenvolvimento Web / Front-End

⭐ Conclusão

O Button Lab 2.0 funciona como um laboratório de aprendizado para transformar elementos HTML simples em componentes modernos e interativos.

A principal ideia do projeto pode ser resumida em:

HTML
   +
CSS
   +
JavaScript
   =
INTERFACE INTERATIVA

O mais importante ao estudar o projeto é compreender por que cada propriedade e cada evento foram utilizados, e não apenas copiar o código.

Depois de dominar os 50 exemplos, o próximo passo é criar seus próprios componentes e começar a reutilizar essas técnicas em projetos reais, como:

dashboards;

sistemas web;

páginas de login;

landing pages;

sistemas administrativos;

portfólios;

lojas virtuais;

aplicativos web.
