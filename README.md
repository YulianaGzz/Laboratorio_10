# Laboratorio 10 — Programación Concurrente en Java

## Objetivo
Aplicar el tema de **programación concurrente en Java** creando hilos con `Runnable` y `Thread`, comprender el ciclo de vida de un hilo, usar `synchronized` para proteger recursos compartidos y simular un torneo RPG con combates que ocurren de manera simultánea. Además, demostrar el problema de las *race conditions* y cómo resolverlo mediante sincronización.

## 📖 Desarrollo
En este laboratorio se introdujeron conceptos nuevos y fundamentales:
- **Programación concurrente**: ejecución de múltiples procesos en paralelo mediante hilos.  
- **Interfaz `Runnable` vs clase `Thread`**: dos formas de crear hilos; `Runnable` ofrece mayor flexibilidad y separación de lógica.  
- **Ciclo de vida de un hilo**: estados `NEW`, `RUNNABLE`, `RUNNING`, `WAITING/BLOCKED`, `TERMINATED`.  
- **Método `synchronized`**: asegura acceso exclusivo a recursos compartidos, evitando inconsistencias.  
- **Race condition**: error que ocurre cuando varios hilos modifican un recurso al mismo tiempo sin control.  
- **Método `join()`**: permite esperar a que un hilo termine antes de continuar la ejecución.  
- **Uso de `Thread.sleep()`**: simula pausas en la ejecución de un hilo sin bloquear a los demás.  

## Ejecución
Compilar todas las clases:
```bash
javac *.java
