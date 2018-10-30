# Artículo Ponencia XI Congreso de Software Libre UNIMINUTO (Villavicencio): "Un Acercamiento con IoT al procesamiento y gestión de datos que ofrece BBIG DATA"

### Contenido
En esta sección se encuentra el articulo de la ponencia, para compilar la ponencia realice lo siguiente: 

## Contexto
Este documento fué presentado como ponencia en el evento mencionado, compartiendo parte de la experiencia recopilada en el proyecto ReA. 

Si bien la temática central del congreso fué Big Data, la aproximación experimentada desde la creación de los dos prototipos de hardware involucrados: Autenticación por NFC (de orden pedagógico) y Captura de lecturas de posicionamiento vía GPS (para el mapeo inicial de la bodega), junto con las proyecciones de generación de datos por dispositivos como las gafas de realidad aumentada, como las EPSON BT300 del proyecto, hicieron atractiva la iniciativa para los organizadores del evento. Las imagenes de participación en el mismo pueden verse en la [página principal de ReA](http://rea.opensai.org){:target="_blank"}.

## Generación del documento

### Instalación entorno de trabajo

Es necesario instalar todo el entorno de Latex, requiere varias gigas de espacio en disco.

Para sistemas basados en Debian:
```latex
apt install texlive-full
```

Para un sistema Fedora:
```latex
dnf install texlive-scheme-full
```

### Actualización y generación del documento
Una vez instalado el entorno, puede usar su editor favorito para trabajar con el documento (PaperAPP.tex). 

Utilice los siguientes comandos para generar el archivo en formato tipo pdf:

Compilación inicial:
```latex
pdflatex  PaperAPP.tex
```

Integración de la bibliografia: 
```latex
bibtex PaperAPP.aux
```

Versión final: 
```latex
pdflatex  PaperAPP.tex
```
