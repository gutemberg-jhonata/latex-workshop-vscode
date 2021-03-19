# Latex + VSCode

## Requerimentos

- Text Live
- latexmk
- TeX Workshop

## Instalação

### Windows

Instale Tex Live através do gerenciador de pacotes Chocolatey.

    choco install texlive -y

Baixe e instale o Perl através do site https://strawberryperl.com/

Baixe e instale o MikTex através do site https://miktex.org/download

Instale o pacote latexmk através do MikTex.

Instale a extensão TeX Workshop através do Visual Studio Code Marketplace ou execute o comando:
    
    ext install latex-workshop

### VSCode

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