# 2-1-websites

Add `_quarto.yml`

project:
  type: website

website:
  title: "Quarto website"
  navbar:
    left:
      - href: index.qmd
        text: Home
      - hello-penguins.qmd

format:
  html:
    theme: cosmo
    toc: true