# Changelog

Todos los cambios relevantes del proyecto se registran en este archivo.

El formato sigue el esquema SemVer / DocVer:

- **MAJOR**: cambios incompatibles o cambios de alcance de la actividad.
- **MINOR**: funcionalidad nueva o ampliaciÃ³n del proyecto.
- **PATCH**: correcciones y ajustes menores que no alteran la funcionalidad.

---

## [v1.0.1] — Ajustes de estructura y documentación

**Fecha:** 2026-10-16
**Estado:** Actualización menor

### Agregado
- Carpeta `capturas/` en la raíz con `ejecucion_repasogeneral.png` y `traza_memoria.png`.
- `docs/InformeEEST1_LPR2026_ACT06_G03_Informe_v1.0.0.pdf` con formato APA v7.
- Evidencia de ejecución, memoria RAM y configuración dual-remote en el informe.

### Modificado
- `README.md`: se corrigió la ubicación de la carpeta `capturas/`.
- Se movió el PDF del enunciado de la actividad a `docs/`.
- Changelog reorganizado para mantener SemVer/DocVer.

---

## [v1.0.0] â€” Baseline aprobado

**Fecha:** 2026-10-15
**Estado:** Baseline Aprobado

### Agregado

- Estructura base del repositorio `repasogeneral` en GitHub.
- `README.md` con datos del estudiante, colegio, materia, curso y profesor.
- `LICENSE` bajo licencia MIT de uso escolar.
- `.gitignore` para excluir ejecutables, carpetas del editor y archivos del sistema.
- `src/main.cpp` con la suite unificada de los tres retos del taller:
  - Reto 1: suma recursiva con caso base garantizado.
  - Reto 2: bÃºsqueda secuencial en arreglo contiguo con interrupciÃ³n por `break`.
  - Reto 3: intercambio de valores mediante pasaje por direcciÃ³n y desreferenciaciÃ³n.
- CompilaciÃ³n verificada con `g++` (TDM-GCC 10.3.0) y ejecuciÃ³n exitosa.
