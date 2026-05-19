# Proyecto de Videojuego 2D — JMonkeyEngine + Tiled

## Descripción

Proyecto de videojuego 2D desarrollado con Java y JMonkeyEngine, utilizando Tiled como editor principal de mapas y un enfoque modular basado en datos.

El objetivo del proyecto es construir una base técnica escalable, organizada y fácil de mantener, priorizando al mismo tiempo un flujo de trabajo rápido y eficiente debido a las limitaciones típicas de un proyecto escolar.

El desarrollo está enfocado en:

* Modularidad.
* Reutilización de sistemas.
* Optimización de recursos.
* Bajo acoplamiento.
* Facilidad de integración.
* Producción rápida.
* Pipeline simple y mantenible.

---

# Tecnologías

## Motor

* Java.
* JMonkeyEngine (jME).

## Herramientas

* Tiled (`.tmx` y `.tsx`).
* Libresprite.
* Git + GitHub.

---

# Características Técnicas

## Arquitectura basada en datos

Gran parte del comportamiento del juego se define mediante propiedades externas configuradas directamente en Tiled, reduciendo lógica hardcodeada y facilitando iteración rápida.

## Sistema modular

El proyecto separa claramente:

* Render.
* Física.
* Audio.
* IA.
* UI.
* Input.
* Interacciones.
* Eventos.
* Persistencia.

## Integración con Tiled

Los mapas y tilesets funcionan como núcleo del pipeline técnico:

* Mapas `.tmx`.
* Tilesets `.tsx`.
* Propiedades personalizadas.
* Triggers.
* Colisiones.
* Spawns.
* Eventos.

## Pipeline optimizado

El proyecto prioriza:

* Reutilización de assets.
* Automatización básica.
* Menor trabajo manual posible.
* Estructura clara de carpetas.
* Escalabilidad controlada.

---

# Filosofía del Proyecto

Este proyecto fue diseñado bajo restricciones reales de tiempo y recursos.

Por ello, todas las decisiones técnicas priorizan:

* Simplicidad.
* Rapidez de desarrollo.
* Sistemas reutilizables.
* Bajo costo técnico.
* Fácil mantenimiento.
* Resultados funcionales rápidos.

Se evita deliberadamente:

* Sobreingeniería.
* Sistemas excesivamente complejos.
* Dependencias innecesarias.
* Arquitecturas difíciles de mantener.

---

# Objetivos Técnicos

* Construir una base sólida para videojuegos 2D.
* Aprender arquitectura modular aplicada a videojuegos.
* Implementar integración profesional con Tiled.
* Desarrollar sistemas reutilizables.
* Crear un pipeline eficiente para proyectos pequeños.
* Mantener el proyecto viable dentro del tiempo escolar.

---

# Estructura del Proyecto

```text
/assets
    /tilesets
    /maps
    /sprites
    /audio
    /ui

/src
    /core
    /map
    /entity
    /player
    /enemy
    /interaction
    /physics
    /audio
    /ui
    /events
    /utils
```

---

# Estado del Proyecto

Proyecto en desarrollo activo.

Actualmente enfocado en:

* Base técnica.
* Sistema de mapas.
* Integración Tiled + jME.
* Colisiones.
* Entidades.
* Interacciones.
* Optimización del pipeline.

---

# Objetivo Final

Crear un videojuego 2D funcional, optimizado y técnicamente organizado utilizando herramientas accesibles y un pipeline realista para un entorno escolar, priorizando mantenibilidad, reutilización y rapidez de desarrollo.
