
# Projeto — Entrega I e II (HTML5 + CSS3)

Este projeto reúne a **Entrega I (Fundamentos e Estruturação)** e a **Entrega II (Estilização e Leiautes)**.

## O que foi feito (Entrega II)
- **Design System** com variáveis CSS em `assets/css/tokens.css`: paleta com 8+ cores, tipografia (5+ tamanhos) e espaçamentos modulares (8–64px).
- **CSS Modular**: `base.css`, `layout.css`, `components.css`, `forms.css` e `style.css` (faz `@import` de todos).
- **Leiautes**: grade **12 colunas** com classes utilitárias `.row` e `.col-*`, **CSS Grid** e **Flexbox** em componentes.
- **Breakpoints**: 480, 640, 768, 1024, 1280, 1536px.
- **Navegação**: menu principal com **submenu dropdown** e **menu hambúrguer** para mobile.
- **Componentes**: cards responsivos, botões com estados (hover/focus/active/disabled), formulários estilizados com validação visual, **alerts**, **toasts**, **modal**, **badges**.
- **Acessibilidade**: estrutura semântica, `aria-*`, contraste, foco visível e navegação por teclado.

## Estrutura de Pastas
```
entrega-projeto-html5/
├── index.html
├── projetos.html
├── cadastro.html
└── assets/
    ├── css/
    │   ├── tokens.css
    │   ├── base.css
    │   ├── layout.css
    │   ├── components.css
    │   ├── forms.css
    │   └── style.css
    ├── js/
    │   ├── mask.js
    │   └── app.js
    ├── images/
    │   ├── hero.png
    │   ├── hero.webp
    │   ├── poster.png
    │   ├── aula.png
    │   ├── feira.png
    │   └── tec.png
    └── video/
        └── institucional.mp4 (placeholder)
```
