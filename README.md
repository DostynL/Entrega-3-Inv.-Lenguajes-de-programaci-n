# Entrega 3 – Programa de Ejemplo en Julia
**Jeremhy Dostyn Jesuá López Bautista – 251404**  
CC2016 – Algoritmos y Estructura de Datos  
Universidad del Valle de Guatemala – Semestre I 2026

---

## ¿Qué hace el programa?
Calculadora de estadísticas básicas. El usuario ingresa sus notas y el programa calcula:
- Promedio
- Nota máxima
- Nota mínima
- Desviación estándar
- Clasificación (Excelente, Bueno, Regular, Reprobado)

## Controles de flujo utilizados
- `for` loops para recorrer los datos
- `while` loops para recibir input y validarlo
- `if/elseif/else` para clasificar y comparar valores

## ¿Cómo correrlo?
1. Tener Julia instalado
2. Abrir terminal y escribir `julia`
3. En el REPL escribir `include("estadisticas.jl")`