# Civil 3D - Vies Ciclistes Catalunya

Archivo XML de estándares de diseño para Autodesk Civil 3D, desarrollado para incorporar comprobaciones geométricas asociadas al diseño de vías ciclistas en Cataluña.

El archivo toma como referencia el *Manual per al disseny de vies ciclistes de Catalunya* e incluye criterios de diseño geométrico como radios mínimos, peraltes, longitudes de transición de peralte y parámetros para acuerdos verticales.

## Contenido del archivo

El XML incluye:

- Tablas de radios mínimos para vías ciclistas pavimentadas.
- Tablas de peralte con un peralte máximo del 2%.
- Métodos de transición de peralte.
- Longitudes mínimas de transición.
- Comprobaciones de acuerdos verticales convexos y cóncavos.
- Parámetros configurados para unidades métricas.

## Uso en Civil 3D

Copiar el archivo XML en la carpeta de estándares de diseño de Civil 3D:

```text
C:\ProgramData\Autodesk\Civil 3D 202x\enu\Data\Corridor Design Standards\
```

Sustituir `202x` por la versión correspondiente de Civil 3D instalada.

Después, el archivo puede cargarse desde las opciones de diseño geométrico de Civil 3D como estándar de diseño para alineaciones y perfiles.

## Archivo incluido

```text
Viaciclista_Catalunya_v5.xml
```

## Referencia técnica

Generalitat de Catalunya.  
*Manual per al disseny de vies ciclistes de Catalunya.*

## Nota de uso

Este archivo no es una herramienta oficial ni sustituye la revisión técnica del proyectista.

Debe considerarse como una adaptación auxiliar para facilitar comprobaciones dentro de Civil 3D. Antes de utilizarlo como criterio de diseño definitivo, se recomienda validar los parámetros incorporados frente al manual original y frente a los requisitos específicos de cada proyecto.

## Estado

Versión inicial en revisión.

Se agradecen comentarios, correcciones o propuestas de mejora.
