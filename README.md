# ✈️ TripMe - Landing Page de Viagens

## 📌 Resumo do Projeto

Este projeto consiste no desenvolvimento de uma **Landing Page** temática de viagens,
com foco em destinos europeus. A página apresenta seções informativas, navegação interna
e visual moderno com estilo editorial.

O projeto foi desenvolvido como parte do curso **DEVstart - SENAI**,
utilizando HTML e CSS puros.

---

## 📖 Introdução

Uma landing page é uma página criada com o objetivo de **fisgar o visitante** —
apresentando um produto, serviço ou experiência de forma atraente e objetiva.

Neste projeto, a TripMe é uma agência de viagens fictícia que convida o usuário
a explorar destinos únicos ao redor do mundo.

---

## ⚙️ Especificações do Projeto

### 🗂️ Estrutura de Arquivos

```
viagens--landing-page/
│
├── index.html      → Estrutura e conteúdo da página
├── style.css       → Estilização completa da página
└── README.md       → Documentação do projeto
```

---

### 📄 Seções da Página

| Seção | ID | Descrição |
|---|---|---|
| Banner | `#banner` | Imagem de fundo com texto em overlay |
| MinhaViagem | `#tripme` | Cards com destinos turísticos |
| NosEncontre | `#meetus` | Apresentação da equipe e estatísticas |
| Conselhos | `#advice` | Dicas práticas para viajantes |

---

## 📏 Requisitos Atendidos

### 🖼️ 1. Banner
- Imagem de fundo de paisagem alpina (Hallstatt, Áustria)
- Texto em overlay com `<h1>` e subtítulo
- Botão de chamada para ação (CTA)

### 🧭 2. Navegação
- `<nav>` fixo no topo com links internos para todas as seções
- Navegação também presente no `<footer>`
- Efeito hover com sublinhado animado nos links

### 🔝 3. Retorno ao Topo
- Botão "↑ Voltar ao topo" em cada seção
- Âncora `<div id="home">` posicionada no início do `<body>`
- Rolagem suave via `scroll-behavior: smooth`

### 🎨 4. Estilo e Interatividade
- Efeito `:hover` em links, cards, botões e dicas
- Transições suaves com `transition`
- Layout responsivo com `@media` para dispositivos móveis

---

## 🏷️ Tags Semânticas Utilizadas

```html
<nav>       → Barra de navegação
<main>      → Conteúdo principal da página
<section>   → Divisão de seções temáticas
<article>   → Cards de destinos e dicas individuais
<footer>    → Rodapé com links e créditos
```

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:
```
git clone https://github.com/Ailtss/viagens--landing-page
```

2. Acesse a pasta do projeto:
```
cd viagens--landing-page
```

3. Abra o arquivo no navegador:
```
Clique duas vezes no arquivo index.html
```
> 💡 Dica: Use a extensão **Live Server** no VS Code para visualizar com atualização automática.

---

## 🚀 Tecnologias Utilizadas

- HTML5 (semântico)
- CSS3 (variáveis, flexbox, grid, animações)
- Google Fonts (Playfair Display + Jost)
- Unsplash (imagens de destinos)

---

## 👨‍💻 Autor - Ailton Gabriel

Projeto desenvolvido como parte do curso **DEVstart - SENAI**.

---

## 📌 Observação

Este projeto demonstra conhecimentos em:

- Estruturação semântica com HTML5
- Estilização avançada com CSS3
- Navegação interna com âncoras e IDs
- Design responsivo com media queries
- Boas práticas de acessibilidade (`alt`, `lang`, navegação por teclado)
- Organização e legibilidade de código
