<!-- Ejercicio: Creación de un Portafolio Digital para la Gestión de Imágenes en un Proyecto Web
Contexto

Una empresa de diseño web está desarrollando un sitio para un cliente que requiere la integración de imágenes en diferentes secciones (galería, banners, miniaturas, etc.). El portafolio de evidencias incluye un análisis de necesidades que indica la importancia de seleccionar formatos de imagen adecuados para optimizar el rendimiento del sitio, garantizar calidad visual y cumplir con requisitos de accesibilidad y compatibilidad.


Desarrolla un portafolio digital que cumpla con los requisitos mencionados, utilizando un formato estructurado  que integre:

    Una tabla comparativa de los formatos de imagen más comunes (JPEG, PNG, GIF, WebP, SVG).
    Ejemplos de archivos optimizados para diferentes casos de uso en el sitio web (por ejemplo, una imagen para un banner, una miniatura y un ícono).
    Una justificación detallada de por qué se eligió cada formato para cada caso.


Instrucciones para Resolver el Ejercicio

    Análisis del caso práctico: Revisa las necesidades del cliente (rendimiento web, calidad visual, compatibilidad) para confirmar los formatos seleccionados.
    Creación de la tabla comparativa: Usa la tabla proporcionada como base, ajustándola si es necesario para otros contextos (por ejemplo, incluir formatos como AVIF si el cliente lo requiere).
    Optimización de archivos:
        Simula la creación de los archivos (puedes usar herramientas como Photoshop, GIMP o ImageOptim para generar versiones optimizadas).
        Asegúrate de que las resoluciones y configuraciones sean adecuadas para el medio digital (web).
    Justificación: Explica claramente por qué cada formato es adecuado para su caso de uso, considerando factores como carga rápida, escalabilidad, compatibilidad y calidad.
    Entregable: Compila el portafolio en un formato digital (Markdown, HTML o PDF) e incluye la tabla, ejemplos de archivos (o rutas simuladas) y justificaciones. -->

# Formatos de imagen adecuados para la web

André Daniel Aguilar Cavazos #25551

DSM3A
## Introducción

Los sitios web tienen distintos factores que afectan a su uso. Uno de ellos es la cantidad de información incluida en cada pagina: entre mas datos se tengan que enviar, mas sera el procesamiento requerido por el cliente para poder visualizarse, lo cual puede llegar a ser un punto de molestia para este. Uno de estos datos son las imágenes incluidas. 


## Explicación

Existen varios tipos de formatos para las imágenes web existentes, cada uno con sus propias ventajas y desventajas. Saber elegir cual es el ideal requiere entender que es lo que se necesita.

Necesitas algo grande con bajo tamaño como una imagen de fondo? JPG esta ahi. <br>
Necesitas algo mediano con alta calidad como para un icono? PNG puede funcionar. <br>
Necesitas algo animado para demostrar algo? GIF o WEBP pueden servirte. Cada uno tiene sus ventajas, desventajas y casos de uso.

He aquí la siguiente tabla comparativa:

<table>
    <tr>
        <th> Formato </th> 
        <th> Calidad </th>
        <th> Tamaño </th>
        <th> Animado </th>
        <th> Notas </th>
        <th> Ventajas </th>
        <th> Desventajas </th>
    </tr>
    <tr>
        <td> PNG </td>
        <td> Alta </td>
        <td> Medio </td>
        <td> No </td>
        <td> Transparencia, compresión sin pérdida </td>
        <td> Alta calidad, compatible con todos los navegadores </td>
        <td> Pesado y no permite animaciones </td>
    </tr>
    <tr>
        <td> JPG </td>
        <td> Media </td>
        <td> Bajo </td>
        <td> No </td>
        <td> Compresión con pérdida </td>
        <td> Bajo tamaño, compatible con todos los navegadores. Ideal para fondos</td>
        <td> Perdida de calidad, ruido y falta de transparencia </td>
    </tr>
    <tr>
        <td> WEBP </td>
        <td> Alta </td>
        <td> Bajo </td>
        <td> Sí </td>
        <td> Compresión con y sin pérdida </td>
        <td> Compatible con la mayor parte de navegadores </td>
        <td> Baja compatibilidad con programas de Windows</td>
    </tr>
    <tr>
        <td> GIF </td>
        <td> Baja </td>
        <td> Medio </td>
        <td> Sí </td>
        <td> Compresión sin pérdida </td>
        <td> Compatible con todos los navegadores </td>
        <td> No permite transparencia, compresión de colores </td>
    </tr>
    <tr>
        <td> SVG </td>
        <td> Alta </td>
        <td> Bajo </td>
        <td> No </td>
        <td> Vectorial </td>
        <td> Compatible con todos los navegadores, escalable, y modificable a tiempo real </td>
        <td> Caro en renderizar, puede mostrarse incorrectamente. No ideal para imagenes rasterizadas. </td>
    </tr>
</table>


La mejor decision para la web seria utilizar WEBP debido a su gran versatilidad con los tamaños y la calidad. También el uso de SVG para iconos y elementos que puedan necesitar algún retoque en tiempo real.

## Comparaciones


### Icono pequeño (x24)

![type 1](https://github.com/noise-programming/school-stuff/blob/main/design/project1/img/comp4-1.png?raw=true)

![type 1](https://github.com/noise-programming/school-stuff/blob/main/design/project1/img/comp4-2.png?raw=true)

### Icono sencillo
![icono sencillo](https://github.com/noise-programming/school-stuff/blob/main/design/project1/img/comp2.png?raw=true)

---
### Logo
![Logo](https://github.com/noise-programming/school-stuff/blob/main/design/project1/img/comp.png?raw=true)

---

### Banner
![Comparacion 3](https://github.com/noise-programming/school-stuff/blob/main/design/project1/img/comp3.png?raw=true)


## Casos de uso

### Banners: JPG / PNG
![Banner](https://github.com/noise-programming/school-stuff/blob/main/design/project1/yo/yo3/yosh_g76.jpg?raw=true)

El bajo peso de JPG es util para banners, en especial si son para fotografias con ruido, pero para ilustraciones mas determinadas es mejor la calidad de png o webp

### Iconos: SVG / PNG
![svg](https://raw.githubusercontent.com/noise-programming/school-stuff/fc4581282781682e4005edec64a16518da5ec201/design/project1/yo/yo4/yosh_use2.svg)
![png](https://raw.githubusercontent.com/noise-programming/school-stuff/fc4581282781682e4005edec64a16518da5ec201/design/project1/yo/yo4/yosh_use2.png)

La escalabilidad de svg es vital para iconos, pero los png tambien son buena opcion si no se busca tanto eso.

### Cualquier otra cosa: WEBP
![webp](https://raw.githubusercontent.com/noise-programming/school-stuff/refs/heads/main/design/project1/yo/yo/yosh_lil%20guy.webp)

Por ser muy versatil en la web, este formato se puede utilizar para varios casos en lugar de png