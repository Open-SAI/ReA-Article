# Artículo Ponencia XI Congreso de Software Libre UNIMINUTO (Villavicencio): "Un Acercamiento con IoT al procesamiento y gestión de datos que ofrece BBIG DATA"

## Contexto
Este documento fué presentado como ponencia en el evento mencionado, compartiendo parte de la experiencia recopilada en el proyecto ReA. 

Si bien la temática central del congreso fué Big Data, la aproximación experimentada desde la creación de los dos prototipos de hardware involucrados: Autenticación por NFC (de orden pedagógico) y Captura de lecturas de posicionamiento vía GPS (para el mapeo inicial de la bodega), junto con las proyecciones de generación de datos por dispositivos como las gafas de realidad aumentada

## Generación del documento

### Instalación

Es necesario instalar todo el entorno de Latex, requiere varias gigas de espacio en disco.

Para sistemas basados en Debian:
```latex
apt install texlive-full
```

Para un sistema Fedora:
```latex
dnf install texlive-scheme-full
```

### Contenido

En esta sección se encuentran dos carpetas, una con el articulo de la ponencia que se realizo en Colombia Villavicencio en el XI Congreso de Software Libre, donde se ha expuesto lo relacionado con realidad aumentada, IoT y bigdata para la visualización del trabajo realizado con OpenSAI y el SENA para la elaboración de un prototipo de realidad aumentada para el apoyo logístico a empresas de almacenaje con smart glass usando software y hardware libre.

En esta sección se encuentra el articulo de la ponencia, para compilar la ponencia realice lo siguiente: 
```latex
pdflatex  PaperAPP.tex
```

dar enter, luego escribir lo siguiente 
```latex
bibtex PaperAPP.aux
```

oprimir enter, luego compilar dos veces con 
```latex
pdflatex  PaperAPP.tex
```
