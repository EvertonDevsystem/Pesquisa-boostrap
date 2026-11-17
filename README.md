# Pesquisa  Framework Bootstrap

> **Aplicação de frameworks web para aumento de produtividade em aplicações web com HTML e CSS.**
> Baseado na documentação oficial de [getbootstrap.com](https://getbootstrap.com/) e no projeto de referência [micasa](https://github.com/wcrvieira/micasa).

---

##  Estrutura do Projeto

```
bootstrap-research/
├── index.html              ← Página principal da pesquisa (tudo em uma página)
├── exemplos/
│   ├── 01-containers.html  ← Exemplo prático de containers
│   ├── 02-navbar.html      ← Exemplo prático de navbar responsiva
│   └── 03-grid.html        ← Exemplo prático do sistema de grid (12 colunas)
└── README.md               ← Este arquivo
```

## O que contém na pesquisa

A página `index.html` reúne os elementos gráficos solicitados:

| Elemento | Seção | Descrição |
|---|---|---|
| 📊 **Infográfico** | `#infografico` | Bootstrap em números + comparativo de produtividade |
| 🗺️ **Mapa Conceitual** | `#mapa` | Diagrama SVG dos conceitos (Grid → Containers → Componentes → Utilitários) |
| 📌 **Padlet** | `#padlet` | Quadro de notas adesivas com os conceitos-chave |
| 📦 **Containers** | `#containers` | Exemplos com código (`.container`, `.container-fluid`, `.container-md`) |
| 🧭 **Navbars** | `#navbars` | Barra de navegação demo ao vivo + código completo |
| 🔲 **Grid** | `#grid` | Demonstração ao vivo das 12 colunas responsivas |
| 🧩 **Componentes** | `#componentes` | Galeria: botões, alertas, cards, modal, accordion, formulário |
| 🔗 **Referências** | `#referencias` | Links para documentação e repositório micasa |

## ▶️ Como executar

Não precisa instalar nada — o Bootstrap é carregado via **CDN**.

1. Baixe/clone este repositório
2. Dê dois cliques em `index.html` (abre no navegador)
3. Ou, de preferência, use um servidor local:
   ```bash
   # Python
   python -m http.server 8000
   # Node
   npx serve .
   ```
   Depois acesse `http://localhost:8000`

## Como subir no GitHub

### Opção 1 — Pelo site (mais fácil, sem instalar nada)

1. Crie uma conta em [github.com](https://github.com/) e clique em **New repository**
2. Dê um nome (ex: `bootstrap-research`) → **Create repository**
3. Na página do repositório, clique em **uploading an existing file**
4. Arraste a pasta `bootstrap-research` (todos os arquivos) para a tela
5. Clique em **Commit changes** — pronto!

### Opção 2 — Pelo terminal (Git)

```bash
# 1. Inicialize o Git na pasta
cd bootstrap-research
git init
git add .
git commit -m "Pesquisa Bootstrap - containers, navbar, grid"

# 2. Crie o repositório no GitHub e copie a URL, depois:
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/bootstrap-research.git
git push -u origin main
```

###  Publicar a página (GitHub Pages)

1. No repositório, vá em **Settings** → **Pages**
2. Em *Source*, selecione **Deploy from a branch**
3. Escolha a branch `main` e a pasta `/ (root)` → **Save**
4. Aguarde ~1 minuto. Sua página ficará online em:
   ```
   https://SEU-USUARIO.github.io/bootstrap-research/
   ```

##  Referências

- **Documentação oficial:** [getbootstrap.com](https://getbootstrap.com/) — Bootstrap 5.3
- **Projeto de referência (micasa):** [github.com/wcrvieira/micasa](https://github.com/wcrvieira/micasa) — por Wagner Cesar Vieira
- **Mi casa ao vivo:** [wcrvieira.github.io/micasa](https://wcrvieira.github.io/micasa/)


- [x] Testados os exemplos (arquivos separados em `exemplos/`)
- [x] Projeto pronto para subir no GitHub
- [x] Passo a passo de publicação pelo GitHub Pages incluso# Pesquisa-boostrap
