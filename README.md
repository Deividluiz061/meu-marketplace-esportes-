# ⚽ Marketplace de Esportes e Fitness

Este é o repositório oficial do **Marketplace de Esportes e Fitness**, uma plataforma de e-commerce de nicho projetada para oferecer uma experiência de compra fluida, rápida e intuitiva para atletas e entusiastas de atividades físicas.

O projeto foi desenvolvido com foco em performance, acessibilidade e design responsivo utilizando uma abordagem *mobile-first*.

---

## 🚀 Funcionalidades Implementadas

*   **Vitrine Dinâmica:** Grid de produtos responsivo que se adapta perfeitamente a telas de computadores, tablets e smartphones.
*   **Alinhamento Inteligente:** Cards de produtos estruturados com Flexbox para garantir que botões e preços fiquem perfeitamente alinhados, independente do tamanho do título.
*   **Busca Integrada:** Barra de pesquisa funcional no topo para filtragem e navegação rápida no catálogo.
*   **Navegação Híbrida:** 
    *   *Desktop:* Menu superior limpo com caminhos de navegação (*breadcrumbs*).
    *   *Mobile:* Barra de navegação inferior (*BottomNavBar*) otimizada para o alcance dos dedos, simulando a experiência de um aplicativo nativo.
*   **Identidade Visual Moderna:** Paleta de cores baseada em tons de azul para ações e gradientes energéticos nos banners de engajamento.

---

## 🛠️ Tecnologias Utilizadas

*   **HTML5:** Estruturação semântica de todas as páginas e seções.
*   **Tailwind CSS:** Framework utilitário para estilização rápida, moderna e responsiva.
*   **Material Symbols (Google Fonts):** Biblioteca de ícones vetoriais leves para os elementos de interface.
*   **Font Plus Jakarta Sans:** Tipografia moderna que garante excelente legibilidade em qualquer dispositivo.

---

## 📂 Estrutura de Pastas Recomendada

```text
meu-marketplace-esportes/
│
├── README.md                 # Instruções e documentação do projeto
├── index.html                # Página de entrada / Redirecionamento
│
├── home/
│   └── index.html            # Vitrine geral e banners principais
│
├── esportes/
│   └── index.html            # Página de categoria (Esportes e Fitness)
│
├── catalogo/
│   └── index.html            # Resultados de busca e filtros de produtos
│
├── carrinho/
│   └── index.html            # Fluxo de finalização de compra
│
├── favoritos/
│   └── index.html            # Lista de desejos do usuário
│
└── perfil/
    └── index.html            # Área do cliente logado
