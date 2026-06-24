# Proyecto 2 — Mapa y aplicación web de pobreza multidimensional (CASEN 2017)

**Diplomado en Manejo de Información Espacial — Universidad Mayor (2023)**
Publicación de un mapa web interactivo y una aplicación web (**ArcGIS Online + Web AppBuilder**) para visualizar la pobreza multidimensional por comuna en la Región Metropolitana, a partir de la encuesta CASEN 2017.

🔗 **Aplicación web:** <https://um.maps.arcgis.com/apps/webappviewer/index.html?id=927f7bc0615d42d3a842abcaaa162fe2>

---

## Contexto

El ejercicio simula un encargo del Ministerio de Desarrollo Social y Familia: disponer de una aplicación web en la que cualquier usuario pueda visualizar la pobreza multidimensional medida por la encuesta CASEN 2017 en las comunas de la Región Metropolitana.

## Objetivos

- Publicar la capa de pobreza multidimensional como capa de entidades alojada en ArcGIS Online.
- Construir un mapa web temático por comuna a partir del porcentaje de pobreza multidimensional.
- Configurar y compartir públicamente una aplicación web con leyenda, ventanas emergentes y pantalla de presentación.

## Marco conceptual

La medida de pobreza multidimensional (versión 2015–2017 del Ministerio de Desarrollo Social) considera **cinco dimensiones** del bienestar, cada una con sus indicadores y umbrales de carencia:

- **Educación** — asistencia escolar, escolaridad, rezago escolar.
- **Salud** — malnutrición infantil, adscripción a sistema de salud, atención de salud.
- **Trabajo y seguridad social** — ocupación, seguridad social, jubilaciones.
- **Vivienda y entorno** — habitabilidad, servicios básicos, entorno.
- **Redes y cohesión social** — apoyo y participación social, trato igualitario, seguridad pública.

*Fuente de los datos: Encuesta CASEN 2017, Ministerio de Desarrollo Social y Familia.*

## Datos de entrada

| Insumo | Descripción |
|--------|-------------|
| `Pobreza_multidimensional` (shapefile) | Polígonos comunales de la Región Metropolitana |
| Atributo `Pmultidime` | Porcentaje de pobreza multidimensional por comuna (variable mapeada) |
| Atributo `Nombre_com` | Nombre de la comuna (título de la ventana emergente) |
| Logos | Universidad Mayor y encuesta CASEN (marca de la aplicación) |


## Tecnologías

**ArcGIS Online**, **ArcGIS Web AppBuilder**, **Map Viewer Classic**, **ArcMap** (publicación del servicio).


## Créditos

Laboratorio del Diplomado en Manejo de Información Espacial, Universidad Mayor (2023).
Profesoras: Idania Briceño y Paulina Vidal.
Datos: Encuesta CASEN 2017, Ministerio de Desarrollo Social y Familia.
