# Taller Práctico de Repaso y Consolidación en C++

**Actividad 6 — Programa Integrador de arrears (P.I.A.)**
Laboratorio de Programación (LPR) — 5° Año, 3° "A"

---

## 📋 Datos de identificación

| Campo | Detalle |
|---|---|
| **Autor** | Malek Cheheid |
| **Grupo** | 3° "A" |
| **Profesor** | Yamil Ganduglia |
| **Materia** | Laboratorio de Programación (LPR) |
| **Actividad** | N.º 6 — Taller Práctico de Repaso y Consolidación en C++ |
| **Fecha de entrega** | 01 de Octubre de 2026 |

---

## 🎯 Objetivos de la actividad

Consolidar de forma práctica, analítica y sin fricción teórica los tres pilares
fundamentales del bajo nivel trabajados durante la primera mitad del ciclo lectivo:

1. **Recursividad** — Comprensión de la pila de llamadas (Stack), flujo de llamadas
   autorreferenciales y la condición de corte obligatoria (*caso base*) para
   prevenir el colapso de memoria (Stack Overflow).
2. **Búsqueda secuencial** — Recorrido indexado celda por celda en arreglos de
   memoria contigua RAM, optimizando el tiempo de ejecución de complejidad `O(n)`
   mediante interrupciones de ciclo (`break`).
3. **Punteros e intercambio físico** — Modificación directa de variables originales
   alojadas en la memoria mediante pasaje por dirección (`&`) y
   desreferenciación (`*`).

---

## 🚀 Compilación y ejecución

Requiere un compilador **g++** (probable en VS Code con MSYS2 o MinGW).

```powershell
# 1. Compilar
g++ src/main.cpp -o src/repasogeneral.exe

# 2. Ejecutar
.\src\repasogeneral.exe
```

Si el equipo no permite compilar localmente, utilizar **OnlineGDB** y guardar las
capturas correspondientes como evidencia.

---

## 🧩 Retos implementados

| Reto | Descripción | Concepto clave |
|---|---|---|
| **Reto 1** | Suma recursiva de `1` hasta `n` | Recursividad y caso base |
| **Reto 2** | Búsqueda secuencial en arreglo contiguo | `O(n)` optimizado con `break` |
| **Reto 3** | Intercambio de valores mediante punteros | Pasaje por dirección (`&`) y desreferenciación (`*`) |

---

## 📁 Estructura del proyecto

```
repasogeneral/
├── .gitignore              # Reglas de exclusión (.exe, .vscode/, *.out)
├── LICENSE                 # Licencia MIT de uso escolar
├── README.md               # Este documento
├── docs/
│   ├── InformeEEST1_LPR2026_ACT06_G03_Informe_v1.0.0.pdf   # Informe APA v7
│   ├── manuales/
│   │   ├── manual_programador_v1.0.0.pdf
│   │   └── manual_usuario_v1.0.0.pdf
│   └── CHANGELOG.md        # Registro de cambios (SemVer / DocVer)
└── src/
    ├── main.cpp            # Suite unificada de los retos del taller
    └── capturas/
        ├── ejecucion_repasogeneral.png
        └── traza_memoria.png
```

---

## 📸 Evidencias

Las capturas de ejecución local y el diagrama de bloques de la memoria RAM se
almacenan en `src/capturas/`.

---

## 🔗 Enlaces técnicos de referencia

- [Recursión en C++ — Conceptos de Recursividad](https://www.geeksforgeeks.org/c-programming/recursion/)
- [Documentación de Microsoft C++ — Arrays y Arreglos](https://learn.microsoft.com/es-es/cpp/cpp-data-members)
- [GeeksforGeeks — Algoritmo de Búsqueda Secuencial (Linear Search)](https://www.geeksforgeeks.org/linear-search/)
- [Tutorial de C++ — Punteros y Dirección de Memoria](https://www.tutorialspoint.com/cplusplus/cpp_pointers.htm)
- [Git Documentation — Git Remote & Dual Push Configurations](https://git-scm.com/book/es/v2/Git-Internals-The-Remote)

---

## 📝 Bitácora de versiones

El registro detallado de cambios se mantiene en
[`docs/CHANGELOG.md`](docs/CHANGELOG.md) siguiendo el esquema SemVer / DocVer.

| Versión | Estado | Descripción |
|---|---|---|
| `v1.0.0` | Baseline Aprobado | Versión inicial de la actividad 6 |