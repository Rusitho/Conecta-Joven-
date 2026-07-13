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

## Cómo publicar (una sola vez)

1. Ve a **Settings → Pages** del repositorio.
2. En **Source** elige **Deploy from a branch**.
3. Selecciona la rama `claude/publish-html-6hsm2m` y la carpeta `/ (root)`.
4. Pulsa **Save**. En 1–2 minutos el sitio queda disponible en la URL de arriba.

A partir de ahí, cada `push` a la rama actualiza el sitio automáticamente.

## Estructura

- `index.html` — Aplicación completa (HTML, CSS con Tailwind y JavaScript en un
  único archivo autónomo).
- `.nojekyll` — Evita el procesamiento Jekyll para un despliegue más rápido.
