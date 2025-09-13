# Proyecto CI/CD con GitHub Actions - DevOps ITLA

## Descripción

Este es un proyecto simple que demuestra la integración continua usando GitHub Actions. Cada vez que se sube código a la rama `main`, se ejecuta automáticamente y envía una notificación a `ntfy.sh/devops-itla`.

## Características

- ✅ Programa "Hola Mundo" en JavaScript
- 🚀 CI/CD automatizado con GitHub Actions
- 📱 Notificaciones push via ntfy.sh
- 🔔 Alertas tanto para éxito como para fallos

## Estructura del proyecto

```
├── .github/
│   └── workflows/
│       └── alerta.yml      # Configuración de GitHub Actions
├── index.js                # Programa principal
└── README.md              # Este archivo
```

## Cómo funciona

1. Al hacer `git push` a la rama `main`
2. GitHub Actions ejecuta el workflow automáticamente
3. Ejecuta el programa JavaScript
4. Envía notificación de éxito o fallo a ntfy.sh/devops-itla

## Para recibir notificaciones

Ve a [ntfy.sh/devops-itla](https://ntfy.sh/devops-itla) o suscríbete al canal `devops-itla` en la app de ntfy.

## Autor

Proyecto creado para la práctica de DevOps - ITLA
