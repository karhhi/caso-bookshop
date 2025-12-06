# Caso Bookshop – Enunciado (versión adaptada)

## 1. Contexto

Una empresa de venta de libros (“Bookshop”) quiere analizar la información de sus ventas
realizadas en distintos países. La compañía vende a través de:
- Tiendas físicas distribuidas internacionalmente.
- Un portal web de comercio electrónico.

El objetivo es unificar y analizar estas fuentes de datos para entregar un reporte
de ventas útil para la gerencia.

## 2. Archivos de datos

Para este caso se entregan dos archivos de texto:

- `bookshop-stores-sales.txt`: registro de ventas realizadas en tiendas físicas.
- `bookshop-web-sales.txt`: registro de ventas realizadas a través del sitio web.

Cada archivo contiene información de:
- Tienda o canal de venta.
- Título del libro.
- Cantidad vendida.
- Precio de lista.
- Porcentaje o monto de royalty asociado.

## 3. Objetivos del análisis

1. Construir un dataset unificado que combine la información de las distintas fuentes
   de venta (tiendas y web).

2. Generar un reporte que incluya, para cada combinación relevante de tienda y libro:
   - Store (tienda o canal)
   - Title (título del libro)
   - Units sold (unidades vendidas)
   - List price (precio de lista)
   - Royalty (monto asociado al royalty)

3. A partir del dataset consolidado, responder las siguientes preguntas de negocio:
   - ¿Cuáles son los libros más vendidos?
   - ¿Cuáles son los libros que generan mayor beneficio para la empresa considerando
     el royalty?

## 4. Entregables

- Un notebook con el proceso completo de:
  - Carga de archivos.
  - Limpieza y transformación de los datos.
  - Construcción del dataset final.
  - Cálculo de indicadores solicitados.

- Un archivo en formato Excel con el reporte consolidado para la gerencia.

## 5. Tecnologías sugeridas

- Python
- Pandas
- Jupyter Notebook
- Excel o equivalente para el reporte final
