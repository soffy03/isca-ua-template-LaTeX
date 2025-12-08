# 📚 Template LaTeX ISCA-UA

[![LaTeX](https://img.shields.io/badge/LaTeX-Template-blue?logo=latex)](https://www.latex-project.org/)
[![Overleaf](https://img.shields.io/badge/Overleaf-Ready-green?logo=overleaf)](https://www.overleaf.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![UA](https://img.shields.io/badge/Universidade-Aveiro-red)](https://www.ua.pt/pt/isca)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17850570.svg)](https://doi.org/10.5281/zenodo.17850570)

Template LaTeX **modular** para dissertações de mestrado e relatórios do **Instituto Superior de Contabilidade e Administração da Universidade de Aveiro (ISCA-UA)**.

> ✅ Conforme as normas oficiais da UA (atualizado maio 2025)

---

## ✨ Características

- 🎨 **Cores oficiais do ISCA** (Pantone 301 + 1787)
- 📐 **Margens e espaçamentos** conforme normas da UA
- 📁 **Estrutura modular** — fácil de editar e organizar
- 🖼️ **Logos oficiais** incluídos
- 📝 **Declaração de IA** (obrigatória desde 2024)
- 🔢 **Numeração automática** — romana (pré-textuais) e árabe (corpo)
- 📑 **Índices automáticos** — conteúdo, figuras, tabelas
- 📚 **Bibliografia** com BibLaTeX (APA, IEEE, etc.)

---

## 📁 Estrutura do Projeto

```
isca-ua-template/
├── 📄 main.tex                 # Documento principal
├── 📄 resumo.tex              # Agradecimentos, Resumo e Abstract
├── 📄 acronimos.tex           # Lista de acrónimos
├── 📄 glossario.tex           # Glossário
├── 📄 biblio.bib              # Referências bibliográficas
│
├── 📁 config/
│   ├── config.sty             # Estilos (não editar)
│   └── logos/                 # Logos UA e ISCA
│
├── 📁 chapter1/               # Capítulo 1: Introdução
│   ├── include.tex
│   ├── content/
│   ├── images/
│   └── tables/
│
├── 📁 chapter2/ ... chapter5/ # Restantes capítulos
├── 📁 annexes/                # Anexos
└── 📁 rascunho/               # Área de testes
```

---

## 🚀 Como Usar

### Opção 1: Overleaf (Recomendado)

1. **Descarrega** este repositório como ZIP (botão verde "Code" → "Download ZIP")
2. No Overleaf: **New Project** → **Upload Project**
3. Seleciona o ficheiro ZIP
4. Compila com **pdfLaTeX**

### Opção 2: Local (TeXLive/MiKTeX)

```bash
git clone https://github.com/SEU-USERNAME/isca-ua-template.git
cd isca-ua-template
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

---

## ⚙️ Configuração

Edita o ficheiro `main.tex` e preenche os teus dados:

```latex
\titulo{O Teu Título em Português}
\tituloingles{Your Title in English}
\autor{O Teu Nome Completo}
\curso{Contabilidade}  % ou Marketing, Finanças, etc.
\orientador{Prof. Doutor Nome, Professor Associado do ISCA-UA}
\ano{2025}
```

---

## 🎨 Cores por Área Científica

| Área | Pantone | RGB | Cor |
|------|---------|-----|-----|
| **Contabilidade** | 301 + 1787 | (0,82,147) + (245,63,91) | 🔵🔴 |
| Economia e Gestão | 1787 | (245,63,91) | 🔴 |
| Artes | 264 | (193,175,229) | 🟣 |
| Ciências | 3105 | (113,214,224) | 🔵 |
| Engenharia | 484 | (152,50,34) | 🟤 |
| Saúde | 115 | (255,218,37) | 🟡 |

Para alterar a cor, edita as referências no ficheiro `config/config.sty`.

---

## 📋 Checklist Antes de Entregar

- [ ] Dados do documento preenchidos (`main.tex`)
- [ ] Resumo e Abstract escritos (`resumo.tex`)
- [ ] Declaração de IA atualizada
- [ ] Lista de acrónimos completa
- [ ] Referências bibliográficas (`biblio.bib`)
- [ ] Membros do júri preenchidos (após nomeação)
- [ ] PDF revisto sem erros

---

## 📖 Normas da UA

Este template segue as normas oficiais:

| Elemento | Especificação |
|----------|---------------|
| **Margens** | Esq: 3cm, Dir: 2.5cm, Sup: 3cm, Inf: 3cm |
| **Espaçamento** | 1.5 linhas |
| **Fonte** | 10-12pt (este template usa 12pt) |
| **Indentação** | 1.25cm |

📎 **Documentação oficial:**
- [Normas para Mestrados](https://www.ua.pt/pt/sga/page/12810)
- [Lista de cores por curso](https://www.ua.pt/file/68147)
- [Identidade Visual UA](https://www.ua.pt/pt/recursos-identidadeUA)

---

## 🤝 Contribuir

Contribuições são bem-vindas! Se encontrares algum problema ou tiveres sugestões:

1. Abre uma **Issue**
2. Ou faz um **Pull Request**

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

---

## 📖 Como Citar

Se utilizares este template no teu trabalho académico, podes citá-lo:


> Correia de Araújo, S. (2025). Template LaTeX ISCA-UA (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.17850570

Ou em BibTeX:
```bibtex
@software{correia_de_araujo_2025,
  author       = {Correia de Araújo, Sofia},
  title        = {Template LaTeX ISCA-UA},
  version      = {v1.0.0},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.17850570},
  url          = {https://doi.org/10.5281/zenodo.17850570}
}
```

---
## 👥 Créditos

Desenvolvido e disponibilizado por **Sofia Correia de Araújo**, estudante finalista da Licenciatura em Contabilidade no ISCA-UA.

- Template criado para a comunidade **ISCA-UA**
- Baseado nas normas oficiais da Universidade de Aveiro (maio 2025)

---

## ⭐ Apoiar

Se este template te foi útil, deixa uma ⭐ no repositório!

---

<p align="center">
  <i>Feito com ❤️ por Sofia Correia de Araújo para estudantes do ISCA-UA</i>
</p>
