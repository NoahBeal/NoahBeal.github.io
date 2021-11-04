---
layout: post
title: "Tarea 3. Dublin Core, un ejemplo comentado (ejercicio incompleto)"
date: 2021-09-27
author: Noah Beal 
---

<span style="color:red">Este ejercicio debe completarse correctamente o elminarse</span>

Dublin Core es una iniciativa para crear una tarjeta de biblioteca digital para la web. Contiene 15 elementos de metadatos que ofrecen información ampliada y ayudan a mejorar la indexación de los programas de motores de búsqueda. Se utiliza con mucha frecuencia en museos, bibliotecas y muchas otras plataformas de publicación. 


Para este ejercicio, echamos un vistazo a una postal de Federico García Lorca a José María Chacón y Calvo. Aquí, puede desglosar los metadatos para ampliar su conocimiento sobre la fuente. La fuente proviene de la colección de la biblioteca de la Universidad de Miami. : [enlace a la postal](https://merrick.library.miami.edu/cdm/compoundobject/collection/chc5324/id/31/rec/19)

 

````
<?xml version="1.0"?>
<metadata xmlns:dc="http://purl.org/dc/elements/1.1/">
...
</metadata>
````

El título corresponde a.. 

````
    <dc:title>El título</dc:title>
````
  
En la etiqueta "creador" se añade la información correspondiente a ...: 

 ````
    <dc:creator>
        Quien creó el recurso
    </dc:creator>
    <dc:subject>
        Palabra clave 1, Palabra clave 2, ...
    </dc:subject>
    <dc:description>
        Esta es la descripción del record...
    </dc:description>
 ````
 
 Otra explicación de otro elemento: 
 
 ````
    <dc:publisher>
        Quien lo publica
    </dc:publisher>
    <dc:contributor>
        Quienes contribuyen
    </dc:contributor>
    <dc:date>
        2021-09-22
    </dc:date>
    <dc:type>
        Imagen,...
    </dc:type>
    <dc:format>
        jpg
    </dc:format>
    <dc:identifier>
        Identificador
    </dc:identifier>
    <dc:source>
        La biblioteca
    </dc:source>
    <dc:language>
        español
    </dc:language>
````

Con cada uno de los elementos se explica brevemente qué son. 

Una breve reflexión final. 



