[comment]: spellcheck-off

# Latex + VSCode

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- Text Live
- latexmk
- TeX Workshop
- Spell Right

## 💻 Projeto

Este repositório tem o propósito de documentar a criação de um ambiente para desenvolvimento de trabalhos, relatórios e artigos com o Visual Studio Code e a extensão Latex Workshop. Além de conter modelos prontos para o desenvolvimento dos mesmos.

## ⚙️ Instalação

### Windows

Instale Tex Live através do gerenciador de pacotes Chocolatey.

    choco install texlive -y

Baixe e instale o Perl através do site https://strawberryperl.com/

Baixe e instale o MikTex através do site https://miktex.org/download

Instale o pacote latexmk através do MikTex.

### VSCode

Instale a extensão TeX Workshop através do Visual Studio Code Marketplace ou execute o comando:
    
    ext install latex-workshop

Instale a extensão Spell Right

    ext install ban.spellright

Adicione ao arquivo settings.json

    "latex-workshop.latex.autoClean.run": "onBuilt"
    "latex-workshop.latex.clean.fileTypes": [
        "*.aux",
        "*.fdb_latexmk",
        "*.fls",
        "*.log",
        "*.synctex.gz",
        "*.xdv"
    ]