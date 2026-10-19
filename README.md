# Índice de Desarrollo Humano e Índice de Densidad del Estado, Perú

Tablero interactivo del IDH (1993-2024) y del IDE (2017-2024) por departamento, provincia y distrito, con mapa coroplético, ranking, lámina comparativa regional, evolución, relación IDH–IDE y tabla de detalle.

## Indicadores

| Índice | Unidad | Años | Componentes |
|---|---|---|---|
| IDH | Puntaje 0 a 1 | 1993, 2000, 2005 (solo departamental); 2003, 2007, 2010-2012, 2015; 2017-2024 | Esperanza de vida, educación, ingreso familiar per cápita |
| IDE | Puntaje 0 a 1 | 2017-2024 | Agua y saneamiento, electricidad, matrícula secundaria (12-16 años), médicos por 10 mil hab. |

El IDH tiene tres series con metodologías distintas (1993-2005 departamental, 2003-2015 y 2017-2024); el tablero solo calcula variaciones dentro de cada serie. Para 1993, 2000 y 2005 no hay datos provinciales ni distritales.

## Mapas

- **Cuartiles del ámbito** (por defecto): cuatro clases con los cuartiles de las unidades del ámbito elegido (Perú o un departamento). Rojo = cuartil más bajo; azul oscuro = cuartil más alto, como en las láminas del PNUD.
- **Cuartiles nacionales**: los mismos cortes para todo el país, comparables entre regiones.
- **Variación**: cambio en puntos del índice frente al año anterior disponible (azul = mejora, rojo = retroceso).

Al elegir un departamento (selector «Ámbito» o clic en el mapa) se muestran sus provincias o distritos, con rótulos de la capital y de los valores extremos.

**Comparación regional**: lámina de tres regiones lista para informes, descargable en PNG o SVG.

## Contenido

| Ruta | Descripción |
|---|---|
| `index.html` | Tablero autocontenido (datos y límites incluidos). |
| `data/idh_ide_distrital.csv` | Datos en formato largo (índice, año, ubigeo, nivel, valor y componentes). |

## Publicar en GitHub Pages

1. Cree el repositorio (por ejemplo, `tablero_idh_ide`) y suba los archivos.
2. En **Settings → Pages**, elija *Deploy from a branch*, rama `main`, carpeta `/ (root)`.

Fuente: PNUD, Informe Nacional sobre Desarrollo Humano Perú 2025 (IDH e IDE 2017-2024) y El reto de la igualdad (2019) para el IDH 2003-2015. Límites: INEI. Elaboración: Good Guys Insight.
