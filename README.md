# Apuntes de GIT para la postulación a la SCESI 2025

## Prerrequisitos para la compilación

- Instalar el compilador de LaTeX `xelatex`:

    ```bash
    # En Debian/Ubuntu:
    sudo apt install texlive-xetex texlive-fonts-recommended texlive-latex-extra

    # En Arch Linux:
    sudo pacman -S texlive-core

    # En Fedora:
    sudo dnf install texlive-xetex texlive-collection-fontsrecommended texlive-collection-latexextra
    ```

- Se recomienda tener una distribución completa de LaTeX (como `texlive-full` en Debian/Ubuntu) para evitar errores por paquetes faltantes.

El repositorio contiene únicamente archivos `.tex` listos para la compilación.

## Comando de compilación

```bash
xelatex -shell-escape -interaction=nonstopmode main.tex
```
En caso de no tener la disponibilidad de instalar un compilador de latex, el archivo `main.pdf` es el output generado listo para la visualizacion.