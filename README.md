# Art�culo Ponencia XI Congreso de Software Libre UNIMINUTO (Villavicencio)
Instale todo el entorno de Latex primero (en un entorno linux tipo basado en Debian)
```latex
apt install texlive-full
```
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
