# cloud-telemetry
# Guía de ejecución – Prototipo de Nodo de Robot Resiliente

## Descripción

Este repositorio implementa un nodo de robot resiliente utilizando Docker y Docker Compose.

El sistema simula una falla controlada en el primer arranque y demuestra recuperación automática mediante políticas de reinicio.

### Objetivos del prototipo

- Tolerancia a fallos  
- Recuperación automática  
- Consistencia de despliegue  
- Alta disponibilidad básica (HA)  

---

## Requisitos Previos

Antes de ejecutar el repositorio, se debe tener instalado:

- Docker  
- Docker Compose (v2 o superior)  

---

## Instrucciones de Ejecución

1. Abrir una terminal en la carpeta del proyecto.
2. Ejecutar:

```bash
docker compose up --build -d
