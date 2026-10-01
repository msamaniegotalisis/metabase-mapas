# Mapas GeoJSON para Metabase

## mexico_estados.geojson

Los 32 estados de México (coordenadas WGS84 / EPSG:4326).

| Propiedad | Ejemplo | Uso |
|---|---|---|
| `cve_ent` | `19` | Clave INEGI a 2 dígitos (con cero a la izquierda, ej. `05`) |
| `cve_ent_num` | `19` | Clave INEGI sin cero (ej. `5`), para columnas numéricas |
| `nombre` | `Nuevo León` | Nombre corto con acentos |
| `nombre_sin_acentos` | `Nuevo Leon` | Nombre sin acentos |
| `iso` | `MX-NLE` | Código ISO 3166-2 |

Fuente de geometrías: [angelnmara/geojson](https://github.com/angelnmara/geojson) (`mexicoHigh.json`); propiedades agregadas con las claves de entidad del INEGI.
