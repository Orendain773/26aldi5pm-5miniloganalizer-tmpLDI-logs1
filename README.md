# Mini Cloud Log Analyzer

Práctica 4.2 — ARM64 Assembly

---

## Alumno

DIEGO ALEJANDRO ORENDAIN CAMACHO

## Institución

Instituto Tecnológico de Tijuana

## Materia

Arquitectura de Computadoras / Ensamblador ARM64

## Fecha

Abril 2026

---

## Descripción

Este proyecto consiste en el desarrollo de un analizador de logs estilo cloud, implementado completamente en lenguaje ensamblador ARM64. El programa procesa códigos de estado HTTP desde la entrada estándar y determina el código más frecuente.

---

## Tecnologías utilizadas

* ARM64 Assembly (GNU Assembler)
* GNU Make
* Bash
* Linux (AWS EC2 ARM64)

---

## Ejecución

```bash
make
cat data/logs_B.txt | ./analyzer
```

---

## Resultado esperado

El programa imprime el código HTTP más frecuente:

```bash
200
```

---

## Estructura del proyecto

```
cloud-log-analyzer/
├── analyzer.s
├── Makefile
├── data/
│   └── logs_B.txt
├── tests/
└── run.sh
```

---

## Objetivo

Comprender cómo un problema de procesamiento de datos puede ser implementado a bajo nivel utilizando instrucciones ARM64, incluyendo el manejo de memoria, control de flujo y uso de syscalls en Linux.
