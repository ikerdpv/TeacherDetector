# Huella de IA

Webapp para comprobar si una tarea, unos apuntes o un examen que ha subido un profesor tiene señales de haberse hecho con IA.

- Pega el texto o sube un PDF, un Word (.docx) o un .txt.
- El análisis se hace en tu navegador: marca frases típicas de chatbot, restos de chat copiados, formato Markdown, emojis, rayas largas y ritmo uniforme, y da una puntuación de 0 a 100.
- Si se detecta IA en un PDF, puedes descargarlo con una marca de agua «IA generated» en cada página.
- Segunda opinión de Claude: pega tu propia API key de Anthropic en la página. La clave se queda en tu navegador (solo se guarda si marcas «Recordarla») y solo se envía a `api.anthropic.com`. Cada consulta se cobra en tu cuenta de Anthropic.

Ningún detector de IA es fiable al 100%: úsalo como pista, no como prueba.

Todo es un único archivo, `index.html`, sin servidor ni compilación.
