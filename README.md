# Conecta Joven

Plataforma de empleabilidad juvenil de impacto — prototipo interactivo alineado
al **ODS 8: Trabajo Decente**, diseñado como respuesta a la informalidad laboral
juvenil en Perú.

## 🌐 Sitio publicado

Una vez ejecutado el flujo de despliegue, el sitio queda disponible en:

**https://rusitho.github.io/Conecta-Joven-/**

## ¿Qué incluye?

- **Simulador móvil interactivo** de la app Conecta Joven (onboarding, dashboard,
  detalle de empleo, red de mentores y ruta de aprendizaje).
- **Inspector del storyboard** de 10 pasos metodológicos, sincronizado en tiempo
  real con el simulador.
- Dos perfiles de demostración: *Lucía* (Villa El Salvador) y *Mateo* (Sistemas).
- Diagnósticos técnicos gamificados, agendamiento de mentorías y auditoría de
  bienestar laboral.

## Publicación

El sitio se despliega automáticamente con **GitHub Actions**
(`.github/workflows/deploy-pages.yml`) en cada `push` a la rama principal.
El flujo activa GitHub Pages por sí solo, por lo que no requiere configuración
manual adicional.

## Estructura

- `index.html` — Aplicación completa (HTML, CSS con Tailwind y JavaScript en un
  único archivo autónomo).
- `.github/workflows/deploy-pages.yml` — Despliegue automático a GitHub Pages.
- `.nojekyll` — Evita el procesamiento Jekyll para un despliegue más rápido.
