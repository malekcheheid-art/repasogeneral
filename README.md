# Taller Práctico de Repaso y Consolidación en C++

**Actividad 6 — Programa Integrador Anual (P.I.A.)**

## Datos personales

- **Estudiante:** Malek Cheheid
- **Curso:** 5° Año — 3° "A"
- **Colegio:** E.E.S.T. N.º 1 "Eduardo Ader", Vicente López, Buenos Aires
- **Materia:** Laboratorio de Programación (LPR)
- **Profesor:** Yamil Ganduglia
- **Actividad:** N.º 6 — Entrega 01 de Octubre de 2026

## Objetivos

Consolidar de forma práctica y analítica los tres pilares del bajo nivel
trabajados en la primera mitad del ciclo lectivo: recursividad con pila de
llamadas y caso base, búsqueda secuencial sobre arreglos de memoria contigua con
interrupción de ciclo, y modificación directa de variables mediante punteros.

## Compilación y ejecución

Requiere un compilador **g++** (disponible en VS Code con MSYS2 o MinGW).

```powershell
g++ src/main.cpp -o src/repasogeneral.exe
.\src\repasogeneral.exe
```

Si el equipo no permite compilar localmente, usar **OnlineGDB** y guardar las
capturas correspondientes como evidencia.

## Retos implementados

| Reto | Descripción | Concepto clave |
|---|---|---|
| **1** | Suma recursiva de `1` hasta `n` | Recursividad y caso base |
| **2** | Búsqueda secuencial en arreglo contiguo | `O(n)` optimizado con `break` |
| **3** | Intercambio de valores mediante punteros | Pasaje por dirección y desreferenciación |

## Estructura del proyecto

```
repasogeneral/
├── .gitignore
├── LICENSE
├── README.md
├── docs/
│   ├── InformeEEST1_LPR2026_ACT06_G03_Informe_v1.0.0.pdf
│   ├── manuales/
│   │   ├── manual_programador_v1.0.0.pdf
│   │   └── manual_usuario_v1.0.0.pdf
│   └── CHANGELOG.md
└── src/
    ├── main.cpp
    └── capturas/
        ├── ejecucion_repasogeneral.png
        └── traza_memoria.png
```

## Evidencias

Las capturas de ejecución local y el diagrama de la memoria RAM se almacenan en
`src/capturas/`.

## Enlaces de referencia

- [Recursión en C++ — Conceptos de Recursividad](https://www.geeksforgeeks.org/c-programming/recursion/)
- [GeeksforGeeks — Búsqueda Secuencial (Linear Search)](https://www.geeksforgeeks.org/linear-search/)
- [Tutorial de C++ — Punteros y Dirección de Memoria](https://www.tutorialspoint.com/cplusplus/cpp_pointers.htm)
- [Git Documentation — Git Remote y Dual Push](https://git-scm.com/book/es/v2/Git-Internals-The-Remote)

## Bitácora de versiones

El registro detallado de cambios se mantiene en `docs/CHANGELOG.md` siguiendo el
esquema SemVer / DocVer. La versión actual es `v1.0.0` (baseline aprobado).
