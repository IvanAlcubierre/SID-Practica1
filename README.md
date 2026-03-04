# SID Práctica 1 - Trabajo en equipo

Repositorio base para desarrollar agentes de la práctica con pyGOMAS.

## 1) Requisitos

- Miniconda instalado
- Entorno `sid` con Python 3.9
- pyGOMAS instalado en editable en ese entorno

## 2) Configuración local (una vez por persona)

```bash
cp .env.example .env
# Edita .env con tus credenciales reales
```

## 3) Arranque rápido

```bash
bash run_local.sh
```

Este script lanza un `pygomas manager` usando los datos de `.env`.

## 4) Flujo recomendado de equipo

- Rama por tarea: `feature/<nombre>`
- Pull Request a `main`
- Nunca subir secretos (`.env` ya está ignorado)

## 5) Estructura

- `agents/`: agentes `.asl`, scripts y recursos de agentes
- `maps/`: mapas personalizados
- `run_local.sh`: comando de arranque local
- `.env.example`: plantilla de variables
