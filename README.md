# Seminario de Título: XAI y clasificación de malware

Informe reformulado a partir de las 43 fichas bibliográficas del vault de Obsidian. La propuesta estudia la selección de características, la destilación de conocimiento y la explicación adaptativa para reducir el costo computacional de XAI.

- [Leer el informe PDF (32 páginas)](main.pdf)
- [Fuente principal LaTeX](main.tex)
- [Matriz de trazabilidad de los 43 papers](Matriz%20de%20los%2043%20papers.md)
- [Cambios y pendientes académicos](LEEME.md)
- [Verificación de la entrega](Verificaci%C3%B3n.md)

## Compilación

Se requiere una distribución LaTeX con pdfLaTeX, Biber y latexmk. Desde la raíz del repositorio:

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

El proyecto conserva el estilo institucional `pucv_inf_2024.sty` y las imágenes de portada. Los capítulos se editan en archivos separados.

## Alcance bibliográfico

Las 43 fichas están trazadas en el anexo y la matriz. La bibliografía principal contiene 13 referencias consolidadas; los antecedentes que requieren contraste están identificados. El documento presenta una propuesta experimental, no resultados de un prototipo ya validado.

Los enlaces de Obsidian y las rutas del manifiesto remiten al vault de origen. Este repositorio contiene el informe y su trazabilidad, no el vault ni los PDF de los artículos.
