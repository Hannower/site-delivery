# 🍔 Mega-Lanches - Sua Plataforma de Delivery Cearense

Este é o código-fonte de um website de delivery de lanches focado na culinária cearense. O projeto apresenta uma estrutura limpa e modularizada, com foco em uma experiência de usuário responsiva e agradável, desde o desktop até o mobile.

---

## ✨ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica do conteúdo.
* **CSS3:** Estilização, layout e responsividade.

---

## 🏗️ Estrutura do Projeto

O projeto é composto pelos seguintes arquivos principais:

| Arquivo/Pasta | Descrição |
| :--- | :--- |
| `index.html` | Arquivo principal com a estrutura completa do site (Header, Cards de Serviços, Artigos de Conteúdo e Footer). |
| `css/style.css` | Folha de estilos principal, incluindo o design, cores e as media queries para responsividade. |
| `assets/` | Pasta que contém todas as imagens utilizadas no projeto (ícones de serviços, planos de fundo e imagens dos artigos). |

---

## 🎨 Visão Geral do Design e Estilo

### Cores Principais

| Cor | Código Hex | Uso |
| :--- | :--- | :--- |
| **Vermelho Principal (Destaque)** | `#ff4b2b` | Fundo do cabeçalho, botões de ação e links. |
| **Fundo Secundário (Rodapé)** | `#1d1a19` | Fundo do rodapé e hover de botões escuros. |
| **Branco** | `#ffffff` | Cor do texto principal, títulos no header. |

### Componentes Chave

1.  **Header (`.cabecalho`):**
    * Fundo com imagem e cor de destaque (`#ff4b2b`).
    * Layout centralizado com título principal e barra de pesquisa funcional.
2.  **Cards de Serviços (`.cards`):**
    * Três cards principais (Entrega, Lojas, Contato) utilizando ícones em estilo de caricatura para ilustrar os serviços.
    * Design baseado em flexbox para fácil alinhamento e empilhamento em telas menores.
3.  **Artigos (`.artigos`):**
    * Seções de conteúdo com layout alternado (imagem à esquerda, texto à direita e vice-versa).
    * Utilizam imagens realistas de lanches e piquenique.
4.  **Rodapé (`footer`):**
    * Organizado em quatro colunas (`grid-template-columns: repeat(4, 1fr)`).
    * Contém links institucionais, ajuda, parceiros e um campo para inscrição na Newsletter.

## 📱 Responsividade

O projeto é totalmente responsivo, adaptando-se a diferentes dispositivos através do uso de **Media Queries** no `style.css`:

* **Layout Flexível:** As seções principais (`.cards` e `.artigos`) utilizam `display: flex` ou são ajustadas via `grid` para se adaptarem à largura da tela.
* **Mobile (max-width: 768px):** As colunas de cards e artigos são transformadas em **linhas empilhadas** (`flex-direction: column`) para garantir uma leitura confortável em smartphones. O rodapé também é ajustado para uma única coluna.
* **Foco na Imagem:** Foi dada atenção especial para que as imagens de fundo e de conteúdo não fiquem cortadas em diferentes resoluções.

---

## 🛠️ Acesse o projeto  


(Clique aqui para acessar o projeto) https://hannower.github.io/site-delivery/