# Art�culo Ponencia XI Congreso de Software Libre UNIMINUTO (Villavicencio): "Un Acercamiento con IoT al procesamiento y gesti�n de datos que ofrece BBIG DATA"

## Contexto
Este documento fu� presentado como ponencia en el evento mencionado, compartiendo parte de la experiencia recopilada en el proyecto ReA. 

Si bien la tem�tica central del congreso fu� Big Data, la aproximaci�n experimentada desde la creaci�n de los dos prototipos de hardware involucrados: Autenticaci�n por NFC (de orden pedag�gico) y Captura de lecturas de posicionamiento v�a GPS (para el mapeo inicial de la bodega), junto con las proyecciones de generaci�n de datos por dispositivos como las gafas de realidad aumentada

## Generaci�n del documento

### Instalaci�n

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

En esta secci�n se encuentran dos carpetas, una con el articulo de la ponencia que se realizo en Colombia Villavicencio en el XI Congreso de Software Libre, donde se ha expuesto lo relacionado con realidad aumentada, IoT y bigdata para la visualizaci�n del trabajo realizado con OpenSAI y el SENA para la elaboraci�n de un prototipo de realidad aumentada para el apoyo log�stico a empresas de almacenaje con smart glass usando software y hardware libre.

En esta secci�n se encuentra el articulo de la ponencia, para compilar la ponencia realice lo siguiente: 
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
