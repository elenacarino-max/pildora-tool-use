# Píldora IA — Tool Use

## Uso de herramientas externas e integraciones de software mediante código ejecutable

Este proyecto forma parte de una píldora formativa sobre **Tool Use en sistemas de Inteligencia Artificial**.

El objetivo es entender cómo un modelo de lenguaje puede utilizar herramientas externas —funciones, APIs, bases de datos o servicios— para obtener información o realizar acciones que no puede ejecutar por sí solo.

La idea principal de toda la píldora es:

> **El LLM decide qué herramienta necesita. El software valida y ejecuta la herramienta.**

---

## Contenido del proyecto

El proyecto está dividido en tres partes principales:

### 1. Presentación interactiva

La página principal explica de forma progresiva:

- qué problema resuelve Tool Use;
- qué es una herramienta;
- cómo funciona una Tool Call;
- qué papel tiene el orquestador;
- cómo se ejecuta una función desde código;
- qué es Function Calling;
- tipos de herramientas que puede utilizar un LLM;
- diferencias entre Tool Use, RAG, agentes y ReAct;
- validación, permisos y seguridad;
- ejemplo completo de principio a fin.

La presentación incluye además una **demo simulada paso a paso** para visualizar el flujo:

```text
Usuario
   ↓
LLM
   ↓
Tool Call
   ↓
Aplicación / Orquestador
   ↓
Herramienta
   ↓
Resultado
   ↓
LLM
   ↓
Respuesta final
```

---

### 2. Murdoku Tool Use

Al finalizar la presentación se puede acceder a un pequeño reto lógico.

El objetivo es reconstruir cuatro ejecuciones de un sistema con herramientas externas relacionando:

- agentes;
- herramientas;
- resultados;
- errores de validación o permisos.

El ejercicio permite repasar conceptos como:

- herramienta autorizada;
- argumento inválido;
- permisos insuficientes;
- acciones sensibles;
- validación previa a la ejecución.

No requiere conocimientos adicionales de programación.

---

### 3. Práctica guiada en Google Colab

El proyecto incluye un notebook práctico para realizar después de la píldora.

Está diseñado como una actividad **muy guiada**.

Cada ejercicio contiene:

1. explicación del concepto;
2. pequeño fragmento de código;
3. uno o varios huecos para completar;
4. pista;
5. comprobación automática;
6. explicación de lo que acaba de ocurrir.

El objetivo no es escribir un sistema completo desde cero, sino comprender cada
