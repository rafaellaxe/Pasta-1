# ♻ ECOPONTO

> *recicle, ganhe.*

A plataforma de reciclagem com recompensas. Site de visualização — sem sistema de login por enquanto.

---

## 🗂 Estrutura do Projeto

```
ecoponto/
├── index.html              ← Página inicial (homepage)
├── css/
│   └── style.css           ← Todos os estilos
├── js/
│   └── main.js             ← Interações (navbar, animações)
├── pages/
│   └── template.html       ← Template para novas páginas
└── README.md
```

---

## 🚀 Como publicar no GitHub Pages

1. **Crie um repositório** no GitHub (ex: `ecoponto`)
2. **Faça upload dos arquivos** ou use Git:

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/seu-usuario/ecoponto.git
git push -u origin main
```

3. No GitHub, vá em **Settings → Pages**
4. Em *Source*, selecione **Deploy from a branch → main → / (root)**
5. Clique em **Save** — seu site estará disponível em `https://seu-usuario.github.io/ecoponto`

---

## ➕ Como adicionar uma nova página

1. Copie `pages/template.html` e renomeie (ex: `pages/como-funciona.html`)
2. Edite o conteúdo dentro da seção `MAIN CONTENT`
3. No navbar do `index.html`, troque o `href="#"` do tab correspondente:

```html
<!-- Antes -->
<a href="#" class="nav-link placeholder">
  Como Funciona <span class="badge">Em Breve</span>
</a>

<!-- Depois -->
<a href="pages/como-funciona.html" class="nav-link">
  Como Funciona
</a>
```

4. Na nova página, marque o link correto com `class="nav-link active"`

---

## 🎨 Paleta de Cores

| Nome            | Hex       |
|-----------------|-----------|
| Verde escuro    | `#1A3C2A` |
| Verde floresta  | `#2D6A4F` |
| Verde acento    | `#52B788` |
| Verde menta     | `#95D5B2` |
| Verde pálido    | `#D8F3DC` |
| Fundo           | `#F0F7F1` |

---

## 🔧 Tecnologias

- HTML5 semântico
- CSS3 puro (variáveis CSS, Grid, Flexbox, animações)
- JavaScript vanilla (sem frameworks)
- Google Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) + [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans)

---

© 2025 ECOPONTO
