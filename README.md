# Artículo Ponencia XI Congreso de Software Libre UNIMINUTO (Villavicencio)
Instale todo el entorno de Latex primero (en un entorno linux tipo basado en Debian)
```latex
apt install texlive-full
```
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
