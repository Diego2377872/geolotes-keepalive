# geolotes-keepalive

Ping cada ~5 minutos a `https://geolotes.onrender.com/api/health` para que el servicio gratuito de Render no entre en reposo (se duerme tras 15 min sin tráfico).

- Repositorio público a propósito: los minutos de GitHub Actions son ilimitados en repos públicos (en el repo privado el cron consumiría más que los 2.000 min/mes gratuitos). Solo contiene este flujo; no hay código ni datos de la plataforma.
- Cambiar la URL: variable de repositorio `TARGET_URL`.
- Pausar: Actions → «Mantener GeoLotes activo» → Disable workflow.
