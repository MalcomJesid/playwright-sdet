# Playwright SDET

Proyecto práctico para evolucionar de QA Automation Engineer a SDET mediante entregas verificables con TypeScript y Playwright.

## Modelo de trabajo

GitHub registra la ejecución:

1. Un Issue representa un ticket de la empresa.
2. Cada ticket define contexto, valor y criterios de aceptación.
3. La implementación se realiza en una rama asociada al ticket.
4. Un Pull Request presenta la solución y su análisis.
5. El PR se revisa contra los criterios.
6. Solo una entrega aprobada se integra en `main`.

Notion funciona como base de conocimiento: conceptos, decisiones, errores, causa raíz y ejercicios de refuerzo. Ambos sistemas se conectan mediante el identificador del ticket, por ejemplo `PW-001`.

## Convenciones

- Ticket: `PW-001`
- Rama: `ticket/PW-001-locators-assertions`
- Commit: `test(playwright): automate todo workflow`
- PR: `[PW-001] Automate basic todo workflow`

## Definición de terminado

- Cumple todos los criterios de aceptación.
- Incluye pruebas y evidencia reproducible.
- Pasa las ejecuciones de estabilidad solicitadas.
- Explica al menos una decisión técnica.
- Declara riesgos, limitaciones o cobertura faltante.
- Registra en Notion el aprendizaje y el siguiente refuerzo.

## Ruta activa

1. TypeScript fundamental.
2. Playwright Web.
3. Diseño y arquitectura de pruebas.
4. API y datos cuando aporten al proyecto.
5. GitHub Actions y CI/CD.

Java y Spring Boot quedan fuera del roadmap activo.
