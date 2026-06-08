# Guía de Contribución

¡Bienvenido! Aliento Tech Studios valora la calidad, la seguridad y la legibilidad.

## Flujo de trabajo
1. **Branching:** Para dev crea una rama desde `dev` con el formato `tipo/nombre-corto`. Para prdo, merge con `main`
2. **Commits:** Obligatorio seguir [Conventional Commits](https://www.conventionalcommits.org/).
   - `feat:` (funcionalidad nueva)
   - `fix:` (corrección de error)
   - `chore:` (tareas de mantenimiento/docker)
   - `refactor:` (cambios que no alteran comportamiento)
3. **Pull Requests:** Abre un PR dirigido a `main`. El CI/CD debe pasar el 100% de los tests antes de solicitar revisión.

## Estándares de código
- **Stack:** Next.js (TypeScript) / Python (Django).
- **Formato:** Usa Prettier/Black.
- **Seguridad:** Prohibido subir secretos. Usa variables de entorno (`.env.example`).
