# Artículo Ponencia XI Congreso de Software Libre UNIMINUTO (Villavicencio): _Un Acercamiento con IoT al procesamiento y gestión de datos que ofrece BIG DATA_

## Contenido
En esta sección se encuentra el articulo de la ponencia, para compilar la ponencia realice lo siguiente: 

## Contexto
Este documento fué presentado como ponencia en el evento mencionado, compartiendo parte de la experiencia recopilada en el proyecto ReA. 

Si bien la temática central del congreso fué Big Data, la aproximación experimentada desde la creación de los dos prototipos de hardware involucrados: Autenticación por NFC (de orden pedagógico) y Captura de lecturas de posicionamiento vía GPS (para el mapeo inicial de la bodega), junto con las proyecciones de generación de datos por dispositivos como las gafas de realidad aumentada, como las EPSON BT300 del proyecto, hicieron atractiva la iniciativa para los organizadores del evento. Las imagenes de participación en el mismo pueden verse en la [página principal de ReA](http://rea.opensai.org).
## Generación del documento

### Instalación entorno de trabajo

Es necesario instalar todo el entorno de Latex, requiere varias gigas de espacio en disco, la instalación requiere permisos administrativos (como usuario root o via comando _sudo_).

Para sistemas basados en Debian:
```
apt install texlive-full
```
Para un sistema Fedora:
```
dnf install texlive-scheme-full
```

### Actualización y generación del documento
Una vez instalado el entorno, puede usar su editor favorito para trabajar con el documento (PaperAPP.tex). Utilice los siguientes comandos para generar el archivo en formato tipo pdf (es posible que sea necesario repetir repetirlos varias veces para que las referencias bibliográficas enlacen adecuadamente):

Compilación inicial:
```
pdflatex  PaperAPP.tex
```
Integración de la bibliografia: 
```
bibtex PaperAPP.aux
```
Versión final: 
```
pdflatex  PaperAPP.tex
```
