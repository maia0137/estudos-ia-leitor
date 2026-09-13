# 📚 Estudos IA — Leitor

Leitor e editor de anotações de estudo em **Markdown** com suporte a **LaTeX**, **checklists interativos**, **campos de preenchimento** e **temas de acessibilidade** (TDAH e Dislexia).

Roda em **um único arquivo HTML**, sem build, sem servidor, sem conta. Todos os dados ficam no seu dispositivo (`localStorage`).

## ✨ Recursos

- 📖 **Markdown completo** com renderização bonita (marked.js)
- ∑ **Fórmulas LaTeX** inline (`$x$`) e em bloco (`$$x$$`) via KaTeX
- ☑ **Checklists clicáveis** (`- [ ]`) que salvam o estado automaticamente
- ▭ **Campos de preenchimento** (`{{ }}`) para anotar valores direto na leitura
- 🗂️ **Organização** em Disciplinas → Subpastas → Tópicos
- 🎨 **8 temas** (Floresta, Sépia, Escuro, Alto Contraste, Conforto Ocular…)
- 🔤 **7 fontes**, incluindo OpenDyslexic e Lexend (foco/TDAH)
- 🛸 **Modo foco** (esconde a barra e deixa só o texto)
- 🔍 **Busca global** em todos os tópicos
- 🕘 **Histórico de versões** por tópico
- 🚮️ **Lixeira** com retenção de 30 dias
- 📊 **Exportar tabelas para Excel** (.xlsx)
- 🧮 **Calculadora** embutida
- 💾 **Backup/Restauração** em `.json`
- 👆 **Swipe** entre tópicos no modo leitura
- 📈 **Barra de progresso** de leitura

## 🚀 Como usar

### Opção 1 — Direto no navegador
1. Baixe o arquivo `APP_ESTUDOS-MN.html`
2. Abra com duplo clique (Chrome, Firefox, Edge, Safari)
3. Pronto. Nenhuma instalação necessária.

### Opção 2 — GitHub Pages
1. Suba este repositório
2. Vá em **Settings → Pages**
3. Em *Source*, escolha `main` / `/(root)`
4. Acesse `https://SEU-USUARIO.github.io/NOME-DO-REPO/APP_ESTUDOS-MN.html`

### Opção 3 — Instalar como app (PWA-like)
No celular, abra pelo navegador e use **"Adicionar à tela inicial"**. Funciona como app nativo.

## ⌨️ Sintaxe suportada

| Você escreve | Você vê |
|---|---|
| `# Título` | Título grande |
| `**negrito**` / `*itálico*` | **negrito** / *itálico* |
| `- item` / `1. item` | listas |
| `- [ ] tarefa` | ☑ checklist clicável |
| `> citação` | bloco de citação |
| `` `código` `` | código inline |
| `[texto](url)` | link |
| `$E = mc^2$` | fórmula inline |
| `$$\\frac{a}{b}$$` | fórmula em bloco |
| `{{ valor }}` | campo preenchível |
| `\| a \| b \|` | tabela (exportável para Excel) |

## 🔒 Privacidade

- **Nada é enviado para servidores.** Sem analytics, sem login, sem nuvem.
- Tudo fica no `localStorage` do seu navegador.
- ⚠️ Limpar o cache do navegador apaga os dados → **faça backup** pelo botão "Backup" na tela inicial.

## 🛠️ Tecnologias

- HTML/CSS/JS puro (vanilla, sem framework)
- [marked](https://github.com/markedjs/marked) — parser Markdown
- [KaTeX](https://katex.org/) — LaTeX
- [SheetJS](https://sheetjs.com/) — geração de .xlsx
- Google Fonts + Fontsource (OpenDyslexic)

## 📄 Licença

MIT — use, modifique e distribua livremente.