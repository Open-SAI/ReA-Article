# Art�culo Ponencia XI Congreso de Software Libre UNIMINUTO (Villavicencio): _Un Acercamiento con IoT al procesamiento y gesti�n de datos que ofrece BIG DATA_

## Contenido
En esta secci�n se encuentra el articulo de la ponencia, para compilar la ponencia realice lo siguiente: 

## Contexto
Este documento fu� presentado como ponencia en el evento mencionado, compartiendo parte de la experiencia recopilada en el proyecto ReA. 

Si bien la tem�tica central del congreso fu� Big Data, la aproximaci�n experimentada desde la creaci�n de los dos prototipos de hardware involucrados: Autenticaci�n por NFC (de orden pedag�gico) y Captura de lecturas de posicionamiento v�a GPS (para el mapeo inicial de la bodega), junto con las proyecciones de generaci�n de datos por dispositivos como las gafas de realidad aumentada, como las EPSON BT300 del proyecto, hicieron atractiva la iniciativa para los organizadores del evento. Las imagenes de participaci�n en el mismo pueden verse en la [p�gina principal de ReA](http://rea.opensai.org).
## Generaci�n del documento

### Instalaci�n entorno de trabajo

Es necesario instalar todo el entorno de Latex, requiere varias gigas de espacio en disco, la instalaci�n requiere permisos administrativos (como usuario root o via comando _sudo_).

Para sistemas basados en Debian:
```
apt install texlive-full
```
Para un sistema Fedora:
```
dnf install texlive-scheme-full
```

### Actualizaci�n y generaci�n del documento
Una vez instalado el entorno, puede usar su editor favorito para trabajar con el documento (PaperAPP.tex). Utilice los siguientes comandos para generar el archivo en formato tipo pdf (es posible que sea necesario repetir repetirlos varias veces para que las referencias bibliogr�ficas enlacen adecuadamente):

Compilaci�n inicial:
```
pdflatex  PaperAPP.tex
```
Integraci�n de la bibliografia: 
```
bibtex PaperAPP.aux
```
Versi�n final: 
```
pdflatex  PaperAPP.tex
```
