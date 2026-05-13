<!-- BOOKWEAVER README -->
<div align="center">

# 🐛 BookWeaver
### *"Tecendo histórias digitais"*

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-orange?style=for-the-badge)](https://github.com/seu-usuario/bookweaver/releases)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge&logo=github)](CONTRIBUTING.md)

[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=flat-square)]()
[![Plataforma](https://img.shields.io/badge/Plataforma-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey?style=flat-square)]()
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=flat-square)]()

<br>

<img src="resources/screenshots/bookweaver_banner.png" alt="BookWeaver Banner" width="800">

**Criador de eBooks profissional inspirado no Kindle Create**

[📥 Download](#-instalação) • [🚀 Quick Start](#-quick-start) • [📚 Documentação](#-documentação) • [🤝 Contribuir](#-contribuindo) • [🐛 Reportar Bug](issues)

</div>

---

## 📖 Sobre o Projeto

**BookWeaver** é uma aplicação desktop open-source que permite criar, formatar e exportar eBooks profissionais nos formatos EPUB, MOBI (Kindle) e PDF. Desenvolvido em Python com interface gráfica PyQt5, oferece uma experiência intuitiva similar ao Kindle Create da Amazon, com recursos adicionais para autores independentes, editoras e criadores de conteúdo.

### 🎯 Por que BookWeaver?

- ✅ **Gratuito e Open Source** - Sem custos, sem limitações
- ✅ **Multi-plataforma** - Windows, Linux e macOS
- ✅ **Interface Intuitiva** - Familiar para quem usa Kindle Create
- ✅ **Formatos Profissionais** - EPUB 3.2, MOBI e PDF
- ✅ **Otimização Kindle** - Recursos específicos para dispositivos Amazon
- ✅ **Templates Prontos** - Ficção, técnico, acadêmico e mais

---

## ✨ Funcionalidades

### 📝 Edição e Formatação
- **Editor Rich Text** - Formatação completa de texto
- **Estilos de Parágrafo** - Títulos H1-H6, citações, código, normal
- **Formatação de Texto** - Negrito, itálico, sublinhado, tachado
- **Alinhamento** - Esquerda, centro, direita, justificado
- **Listas** - Numeradas e não-numeradas
- **Inserção de Mídia** - Imagens, tabelas e links
- **Notas de Rodapé** - Suporte completo com popups para Kindle

### 📂 Importação
| Formato | Status | Recursos |
|---------|--------|----------|
| DOCX (Word) | ✅ | Preserva estilos, imagens e formatação |
| Markdown (.md) | ✅ | Suporte GFM, YAML frontmatter |
| TXT | ✅ | Detecção automática de encoding |
| ODT (OpenDocument) | ✅ | Preserva estrutura completa |
| RTF | 🔄 | Em desenvolvimento |

### 📤 Exportação
| Formato | Status | Destino |
|---------|--------|---------|
| EPUB 3.2 | ✅ | Leitores universais |
| MOBI | ✅ | Kindle (todos modelos) |
| PDF | ✅ | Impressão e distribuição |

### 🎨 Templates Profissionais
- **📚 Ficção** - Fontes elegantes, drop caps, espaçamento otimizado
- **🔧 Técnico** - Blocos de código, callouts, tabelas estilizadas
- **🎓 Acadêmico** - Notas de rodapé, citações ABNT, referências
- **👶 Infantil** - Fontes grandes, suporte a muitas imagens
- **📜 Poesia** - Formatação especial para versos
- **📰 Revista** - Layout flexível para artigos

### 🚀 Recursos Avançados
- **📑 Sumário Automático** - Gerado a partir dos títulos
- **🖼️ Otimizador de Imagens** - Compressão e redimensionamento para e-ink
- **📊 Analytics** - Contagem de palavras, tempo de leitura, legibilidade
- **💾 Backup Automático** - Salvamento a cada 5 minutos
- **🌓 Tema Claro/Escuro** - Conforto visual em qualquer ambiente
- **🔍 Spell Check** - Correção ortográfica em português e inglês
- **📱 Preview Multi-dispositivo** - Visualize como ficará no Kindle, iPad, iPhone

---

## 🎬 Screenshots

<div align="center">

| Editor | Preview | Templates |
|--------|---------|-----------|
| ![Editor](resources/screenshots/editor.png) | ![Preview](resources/screenshots/preview.png) | ![Templates](resources/screenshots/templates.png) |

| Exportação | Capítulos | Temas |
|------------|-----------|-------|
| ![Export](resources/screenshots/export.png) | ![Chapters](resources/screenshots/chapters.png) | ![Themes](resources/screenshots/themes.png) |

</div>

---

## 🚀 Instalação

### Pré-requisitos
- **Python 3.8** ou superior
- **pip** (gerenciador de pacotes Python)
- **Git** (opcional, para clonar o repositório)
- **Pandoc** (opcional, para conversões avançadas)

### Método 1: Instalação Rápida (Windows)

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/bookweaver.git
cd bookweaver

# Execute o instalador automático
install_dependencies.bat
