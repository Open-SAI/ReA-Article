# Art�culo Ponencia XI Congreso de Software Libre UNIMINUTO (Villavicencio): "Un Acercamiento con IoT al procesamiento y gesti�n de datos que ofrece BBIG DATA"

### Contenido
En esta secci�n se encuentra el articulo de la ponencia, para compilar la ponencia realice lo siguiente: 

## Contexto
Este documento fu� presentado como ponencia en el evento mencionado, compartiendo parte de la experiencia recopilada en el proyecto ReA. 

Si bien la tem�tica central del congreso fu� Big Data, la aproximaci�n experimentada desde la creaci�n de los dos prototipos de hardware involucrados: Autenticaci�n por NFC (de orden pedag�gico) y Captura de lecturas de posicionamiento v�a GPS (para el mapeo inicial de la bodega), junto con las proyecciones de generaci�n de datos por dispositivos como las gafas de realidad aumentada

## Generaci�n del documento

### Instalaci�n entorno de trabajo

Es necesario instalar todo el entorno de Latex, requiere varias gigas de espacio en disco.

Para sistemas basados en Debian:
```latex
apt install texlive-full
```

Para un sistema Fedora:
```latex
dnf install texlive-scheme-full
```

### Actualizaci�n y generaci�n del documento
Una vez instalado el entorno, puede usar su editor favorito para trabajar con el documento (PaperAPP.tex). 

Utilice los siguientes comandos para generar el archivo en formato tipo pdf:

Compilaci�n inicial:
``latex
pdflatex  PaperAPP.tex
```

Integraci�n de la bibliografia: 
```latex
bibtex PaperAPP.aux
```

Versi�n final: 
```latex
pdflatex  PaperAPP.tex
```
