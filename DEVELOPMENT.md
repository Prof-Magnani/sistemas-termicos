
# DEVELOPMENT.md

Este documento explica como preparar o ambiente de desenvolvimento do repositório, organizar os arquivos e gerar as saídas (HTML, PDF, slides Reveal.js e PPTX).

---

## 1. Instalação do ambiente completo (para rodar notebooks e renderizar)

- **Anaconda ou Miniconda** – gerenciar Python e pacotes científicos.  
  https://www.anaconda.com/download

- **VS Code** – editor recomendado (extensões: *Python*, *Jupyter*).  
  https://code.visualstudio.com/

- **MiKTeX** (ou TeX Live) – necessário para gerar PDFs via Quarto.  
  https://miktex.org/download

- **Quarto** – ferramenta central para renderização.  
  https://quarto.org/docs/download/

---

## 2. Instalação mínima (só para renderizar com Quarto)

Se você já tem os notebooks prontos e não precisa editar/rodar células Python localmente, basta instalar:

- **Quarto**
- **MiKTeX** (para PDF)

---

## 3. Estrutura de arquivos

A estrutura do repositório é:

```
repo/
  _quarto.yml          # configuração principal do projeto
  assets/
    slides.css         # estilos de slides (Reveal.js)
  notebooks/           # arquivos .ipynb (fonte principal)
  figures/             # figuras usadas nos notebooks
  html/                # saídas HTML
  pdf/                 # saídas PDF
  pptx/                # saídas PowerPoint
  revealjs/            # saídas Reveal.js
  README.md            # descrição do projeto
  DEVELOPMENT.md       # este documento
```

---

## 4. Renderização com Quarto

Comandos básicos (rodar a partir da **raiz do repositório**; trocar 'my-notebook' pelo nome do seu notebook):

- **Reveal.js (slides interativos):**
  > quarto render notebooks/my-notebook.ipynb --to revealjs --no-clean --output-dir revealjs --output my-notebook-slides.html

- **PDF:**
  > quarto render notebooks/my-notebook.ipynb --to pdf --no-clean --output-dir pdf --output my-notebook.pdf

- **HTML (página estática):**
  > quarto render notebooks/my-notebook.ipynb --to html --no-clean --output-dir html --output my-notebook.html

- **PowerPoint (PPTX):**
  > quarto render notebooks/my-notebook.ipynb --to pptx --no-clean --output-dir pptx   --output my-notebook.pptx

---

## 5. Git e GitHub

- Crie uma conta em: https://github.com  
- Instale o **GitHub Desktop** (interface simples) ou o **Git** (linha de comando):  
  https://desktop.github.com / https://git-scm.com/downloads
- Clone este repositório em sua máquina.
- Use commits regulares para salvar alterações (`.ipynb`, `_quarto.yml`, `assets/` etc).

---
