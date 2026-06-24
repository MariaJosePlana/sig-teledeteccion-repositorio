# Ordenamiento Territorial — Subcuenca del Estero Alhué

**Herramienta:** ArcGIS Pro
**Metodología:** SUBDERE (2013) — Plan Regional de Ordenamiento Territorial, componente cuencas hidrográficas

---

## Contexto

Ejercicio de Ordenamiento Territorial para la subcuenca del Estero Alhué (Región del Libertador Bernardo O'Higgins), replicando la metodología del Plan Regional de Ordenamiento Territorial (PROT) para el componente de cuencas hidrográficas, en el contexto de problemáticas de recurso hídrico y disminución de precipitaciones por cambio climático.

---

## Metodología

La zonificación se construyó integrando tres criterios:

**1. Aptitud de suelo** — reclasificación de la Clase de Capacidad de Uso de Suelo en tres categorías: potencial agrícola (Clases I-IV), potencial ganadero-forestal (Clases V-VII) y potencial para vida silvestre (Clase VIII y N.C.).

**2. Aptitud hídrica** — delimitación de zonas de producción de agua (parte alta de la cuenca), zonas de aprovechamiento preferente (uso intensivo del recurso) y zonas de impacto hídrico (área de protección de 100 m a cada lado de los cursos de agua, según normativa chilena de zonas de protección de cauces).

**3. Áreas ambientalmente valiosas** — integración de SNASPE, sitios prioritarios para la conservación de biodiversidad, Santuarios de la Naturaleza, sitios RAMSAR y Áreas Silvestres Protegidas Privadas (ASPP), todas clasificadas como zonas de protección.

La combinación de aptitud de suelo y aptitud hídrica, mediante una regla de decisión (SUBDERE, 2013), define tres categorías finales de zonificación:
- **Zona adecuada para desarrollo productivo**
- **Zona adecuada para desarrollo productivo con manejo**
- **Zona adecuada para protección**

---

## Resultado

![Mapa de zonificación PROT - Subcuenca Estero Alhué](mapa_zonificacion.png)

El mapa final identifica zonas de desarrollo productivo concentradas en sectores de menor pendiente y mejor aptitud agrícola, zonas de desarrollo productivo con manejo en sectores de mayor fragilidad, y áreas de protección asociadas a cursos de agua, cuerpos de agua y sectores de alto valor ambiental dentro de la subcuenca.

---

## Geoprocesos aplicados

- Dissolve de capas vectoriales por atributo de capacidad de uso de suelo
- Reclasificación de atributos mediante tabla de decisión
- Buffer (zonas de protección de cauces, 100 m)
- Unión de capas vectoriales (Union)
- Construcción de regla de decisión multicriterio para zonificación final
