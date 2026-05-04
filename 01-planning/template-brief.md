# Technical Brief

## 1. Título de la tarea

Nombre claro y específico de la funcionalidad o servicio a implementar.

Ejemplo:
Servicio Desacoplado de Cálculo de Impuestos

---

## 2. Contexto

Describe el problema actual y por qué se necesita esta solución.

Incluye:

- Cómo funciona el sistema actualmente
- Cómo funciona el entorno actualmente (tech stack)
- Qué problema existe (acoplamiento, deuda técnica, escalabilidad, etc.)
- Qué se busca lograr con esta implementación

Ejemplo de estructura:

El sistema actual \***\*\_\_\_\_\*\***.
El entorno actual \***\*\_\_\_\_\*\***.
Esto genera problemas como \***\*\_\_\_\_\*\***.

El objetivo de esta tarea es \***\*\_\_\_\_\*\*** para mejorar \***\*\_\_\_\_\*\***.

---

## 3. Requerimientos técnicos

### Tech Stack

- Lenguaje:
- Versión mínima:
- Framework (si aplica):
- Nube (si aplica):

Ejemplo:

- Python 3.9+
- FastAPI
- PostgreSQL
- Google Cloud / AWS

---

### Arquitectura

Describe patrones o principios a usar.

Ejemplo:

- Clean Architecture
- Strategy Pattern
- Dependency Injection
- Stateless service

---

### Input y Output esperados

Define los datos de entrada y salida.

Ejemplo:

```python
InputObject
- field_1: type
- field_2: type
```

```python
OutputObject
- field_1: type
- field_2: type
```

---

### Comportamiento esperado

Describe el comportamiento esperado.

Ejemplo:

El servicio debe:

- Recibir un objeto `Input`
- Identificar el objetivo
- Seleccionar la estrategia correspondiente
- Retornar un `Output`

## 4. Constraints (Restricciones)

- No usar librerías externas salvo las aprobadas por el equipo.
- Implementar type hints en todo el código.
- Seguir principios SOLID y buenas prácticas del lenguaje.
- Separar claramente el dominio, estrategias y servicios principales.
- ...
- Agregar constraints especificos del problema.
- Agregar constraints especificos del repositorio (eg. linter, tests)

## 5. Definition of Done (DoD)

El trabajo se considera terminado cuando:

- El código pasa linters y convenciones de estilo adoptadas por el equipo (ej: flake8, black).
- La cobertura de tests unitarios es al menos 90%.
- Todas las interfaces y los métodos públicos tienen **docstrings**
- ...
- Agregar criterior especificos del problema.
