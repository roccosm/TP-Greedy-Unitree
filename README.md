# TP Greedy - Unitree G1

Trabajo práctico grupal realizado en la materia Programación III de la Licenciatura en Gestión de Tecnología de la Información (UADE).

## Objetivo

Desarrollar un algoritmo Greedy en Python para planificar rutas de un robot Unitree G1 sobre diferentes mapas, utilizando la distancia Manhattan como criterio de selección de movimientos.

## Funcionalidades

- Lectura de mapas mediante archivos JSON.
- Generación y selección de movimientos factibles.
- Identificación de obstáculos y zonas restringidas.
- Registro de posiciones visitadas.
- Generación de instrucciones de orientación, giro y desplazamiento.
- Ejecución en el simulador MuJoCo.

## Tecnologías utilizadas

- Python.
- JSON.
- MuJoCo.
- Git y GitHub.

## Resultados

Se evaluó el comportamiento del algoritmo en tres escenarios:

| Mapa | Resultado | Movimientos |
|---|---|---:|
| Mapa 1 | Ruta óptima | 8 |
| Mapa 2 | Ruta subóptima | 20 |
| Mapa 3 | Bloqueo | 12 |

Las pruebas permitieron analizar las ventajas y limitaciones de la estrategia Greedy, demostrando que las decisiones localmente óptimas no siempre garantizan una solución global óptima.

La simulación se realizó utilizando la API de control del robot proporcionada por la cátedra.
