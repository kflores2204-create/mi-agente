# mi-agente: tu asistente personal (kit de inicio)

Este repositorio es el "cerebro" de tu agente. Todo lo que el agente sabe de ti vive aquí en archivos de texto que tú puedes leer, corregir y borrar.

## Regla principal
El agente propone, tú apruebas. Nunca postula, paga ni publica sin tu visto bueno.

## Estructura
- agente/        Instrucciones del agente (SYSTEM_PROMPT.md)
- perfil/        Quién eres: perfil, experiencia, estilo y reglas
- memoria/       Diario y aprendizajes (lo que va aprendiendo de ti)
- empleo/        Seguimiento de postulaciones y prompt para analizar ofertas
- estudio/       Preparación para CCNA, ITIL 4, NSE 4 y PMP/CAPM
- portafolio/    Brief y convenciones del primer proyecto web

## Orden de ejecución (checklist)
### Día 1: cuentas y seguridad
- [ ] Crear cuenta en GitHub y activar verificación en dos pasos
- [ ] Crear repositorio PRIVADO "mi-agente" y subir esta carpeta
- [ ] Crear cuenta en Google AI Studio y generar una API key de Gemini
- [ ] Crear cuenta en Groq (respaldo) y en Supabase
- [ ] Guardar todas las claves en un gestor de contraseñas. Nunca en el repositorio (usa .env, que está en .gitignore)

### Día 2: completar tu perfil
- [ ] Revisar y corregir perfil/perfil.md y perfil/experiencia.md (las cifras marcadas con [VERIFICAR])
- [ ] Pegar 3 textos tuyos en perfil/estilo.md
- [ ] Ajustar perfil/reglas.md (roles, zona, modalidad, descartes)

### Día 3: conectar el cerebro
- [ ] Probar el agente en el chat de Google AI Studio pegando agente/SYSTEM_PROMPT.md + tus archivos de perfil/
- [ ] Hacerle 10 preguntas sobre ti y anotar cada error en memoria/aprendizajes.md

### Día 4: Telegram + n8n
- [ ] Crear bot con BotFather (Telegram)
- [ ] Levantar n8n (instancia gratuita en la nube) y conectar Telegram + Gemini
- [ ] Comando /recuerda: guarda texto con fecha en memoria/diario.md

### Día 5: estudio
- [ ] Confirmar qué certificación es "SNE4" (¿Fortinet NSE 4?)
- [ ] Descargar los temarios OFICIALES y pegarlos en estudio/<cert>.md
- [ ] Empezar con la certificación que tenga cursos oficiales gratuitos

### Día 6-7: portafolio
- [ ] Completar portafolio/BRIEF.md
- [ ] Ejecutar el flujo: pedido, plan, código en rama, pruebas, tu revisión, vista previa, producción

## Seguridad
- No guardes DNI, contraseñas, datos bancarios ni nada que no compartirías con un tercero.
- Las capas gratuitas de las APIs pueden usar tus datos para mejorar sus productos: revisa sus términos.
- Haz respaldo del repositorio (es tu memoria).
