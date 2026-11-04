# Convenciones de desarrollo (el agente las lee siempre)

## Stack fijo
- Frontend: React + Vite + Tailwind CSS
- Alojamiento: Cloudflare Pages, Vercel o Netlify (capa gratuita)
- Repositorio: GitHub, ramas por cambio (feature/nombre)
- Pruebas automáticas: GitHub Actions

## Flujo obligatorio
1. Pedido en lenguaje natural.
2. El agente propone un plan y espera aprobación.
3. Código en una rama nueva, con pruebas.
4. Kevin revisa el diff.
5. Vista previa.
6. Producción solo con aprobación de Kevin.

## Reglas de código
- Componentes pequeños y con nombres claros
- Sin claves ni secretos en el código (usar variables de entorno)
- Accesibilidad básica: textos alternativos, contraste, navegación con teclado
- Comentarios solo donde aporten
- Si algo no está claro, preguntar antes de asumir
