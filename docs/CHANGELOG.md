# Changelog

Todos los cambios relevantes del proyecto se registran en este archivo.

El formato sigue el esquema SemVer / DocVer:

- **MAJOR**: cambios incompatibles o cambios de alcance de la actividad.
- **MINOR**: funcionalidad nueva o ampliación del proyecto.
- **PATCH**: correcciones y ajustes menores que no alteran la funcionalidad.

---

## [v1.0.0] — Baseline aprobado

**Fecha:** 2026-10-15
**Estado:** Baseline Aprobado

### Agregado

- Estructura base del repositorio `repasogeneral` en GitHub.
- `README.md` con datos del estudiante, colegio, materia, curso y profesor.
- `LICENSE` bajo licencia MIT de uso escolar.
- `.gitignore` para excluir ejecutables, carpetas del editor y archivos del sistema.
- `src/main.cpp` con la suite unificada de los tres retos del taller:
  - Reto 1: suma recursiva con caso base garantizado.
  - Reto 2: búsqueda secuencial en arreglo contiguo con interrupción por `break`.
  - Reto 3: intercambio de valores mediante pasaje por dirección y desreferenciación.
- Compilación verificada con `g++` (TDM-GCC 10.3.0) y ejecución exitosa.
