# 📚 Biblioteca Digital UniFECAF

> Projeto acadêmico de uma **Biblioteca Digital responsiva e acessível**, desenvolvido
> em **HTML e CSS puros** (sem frameworks), seguindo a identidade visual e o Design
> System da **UniFECAF**.

Acesse livros, materiais acadêmicos e conteúdos de apoio de forma simples, rápida e intuitiva.

---

## 🎯 Sobre o projeto

A **Biblioteca Digital UniFECAF** é uma landing page que simula o portal de uma
biblioteca universitária. O objetivo é apresentar o acervo, as categorias de livros e
os serviços oferecidos aos alunos, com foco em:

- **Design responsivo** — funciona bem em celular, tablet e desktop (abordagem *mobile-first*).
- **Acessibilidade** — navegação por teclado, leitores de tela e bom contraste de cores.
- **Zero dependências** — todo o layout é feito apenas com **HTML5 semântico** e **CSS3**.

---

## ✨ Funcionalidades

| Seção | Descrição |
|-------|-----------|
| **Header** | Navegação fixa com menu hambúrguer no mobile (feito só com CSS). |
| **Hero** | Chamada principal com ilustração SVG e botões de ação. |
| **Destaques** | Cards dos livros mais procurados da semana. |
| **Categorias** | Grade com as áreas de conhecimento (Tecnologia, Saúde, etc.). |
| **Acervo** | Galeria de livros com status *Disponível* / *Emprestado*. |
| **Serviços** | Cards com os serviços de apoio ao aluno. |
| **CTA** | Chamada final para acessar a Biblioteca Virtual. |
| **Footer** | Contato, navegação e informações institucionais. |

---

## 🎨 Design System (UniFECAF)

| Token | Cor | Uso |
|-------|-----|-----|
| **Navy** | `#1A3666` | Cor primária — fundos, títulos, header. |
| **CTA Pink** | `#FF2B5F` | Cor de ação — botões e destaques. |
| **Yellow** | `#F2CB0A` | Cor de apoio — detalhes e sublinhados. |
| **Tipografia** | `DM Sans` | Fonte principal do projeto. |

---

## 🚀 Como executar

Por ser um site estático, basta abrir o arquivo `index.html` no navegador.

**Opção 1 — abrir direto:** dê um duplo clique no `index.html`.

**Opção 2 — servidor local (recomendado):**

```bash
# com Python 3
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000` no navegador.

---

## 📁 Estrutura de pastas

```
Biblioteca Digital UniFECAF/
├── index.html            # Página principal
├── css/
│   └── style.css         # Estilos, tokens e regras responsivas
└── assets/
    └── imagens/          # SVGs (logo, hero, capas dos livros, favicon)
```

---

## ♿ Acessibilidade

- *Skip link* para pular direto ao conteúdo principal.
- Estrutura semântica com `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
- Rótulos `aria-label` nos elementos interativos.
- Estilos de foco visíveis (`:focus-visible`).
- Respeita `prefers-reduced-motion` (reduz animações).

---

## 🛠️ Tecnologias

- HTML5
- CSS3 (Flexbox + Grid, variáveis CSS, media queries)
- SVG (ilustrações e ícones)

---

## 👤 Autor

**Erick** — projeto acadêmico desenvolvido para a disciplina de Designer Web / UniFECAF.

---

## 📄 Licença

Projeto de uso **acadêmico/educacional**.
