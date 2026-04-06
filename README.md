# 🧠 DSM Quiz — Aprende Jugando

> Un juego de preguntas interactivo para estudiar los criterios diagnósticos del DSM (Manual Diagnóstico y Estadístico de los Trastornos Mentales).

---

## 📋 ¿Qué hace esta aplicación?

Tú pegas un texto del DSM → la app lo analiza → genera preguntas de opción múltiple → juegas y te puntúa. Todo en tu navegador, sin instalar nada ni necesitar internet (excepto la primera vez para cargar las fuentes).

---

## 🚀 CÓMO USAR — PASO A PASO

### PASO 1 — Descargar el archivo

1. Ve al repositorio en GitHub
2. Haz clic en el archivo `dsm-juego.html`
3. Haz clic en el botón **"Download raw file"** (ícono de descarga ↓)
4. Guárdalo en cualquier carpeta de tu computador (por ejemplo, el Escritorio)

> ✅ Solo necesitas ese **un archivo**. No hay más archivos, no hay instalaciones.

---

### PASO 2 — Abrir la aplicación

1. Navega a la carpeta donde guardaste `dsm-juego.html`
2. Haz **doble clic** en el archivo
3. Se abrirá automáticamente en tu navegador (Chrome, Firefox, Safari, Edge — todos funcionan)

> ⚠️ Si el archivo se abre como texto plano, haz clic derecho → "Abrir con" → elige tu navegador.

---

### PASO 3 — Pegar tu texto DSM

Verás un cuadro de texto grande con el mensaje *"Pega aquí el texto del DSM..."*.

**Opción A — Texto propio:**
1. Abre tu libro o apunte del DSM
2. Copia el fragmento que quieres estudiar (Ctrl+C / Cmd+C)
3. Haz clic dentro del cuadro de texto en la app
4. Pégalo (Ctrl+V / Cmd+V)

**Opción B — Texto de ejemplo (para probar):**
1. Haz clic en el botón **"📄 Cargar texto de ejemplo completo"**
2. El cuadro se llenará automáticamente con un texto sobre trastornos de tics del DSM-5

**Opción C — Palabras clave sueltas:**
- Haz clic en cualquiera de las etiquetas de colores moradas (`CRITERIO_A`, `1 año`, etc.)
- Cada clic agrega esa palabra clave al texto
- Puedes combinar varias

---

### PASO 4 — Generar las preguntas

1. Con el texto ya en el cuadro, haz clic en el botón verde **"▶ Generar preguntas"**
2. La app analiza el texto buscando palabras clave clínicas
3. Desaparece el cuadro de texto y aparece la primera pregunta

> 📌 **¿Qué detecta la app?**
> | Palabra clave en el texto | Pregunta que genera |
> |---|---|
> | `CRITERIO_A` | ¿Qué describe el Criterio A? |
> | `1 año` | ¿Duración mínima para diagnóstico crónico? |
> | `DIAGNOSTICOS_DIFERENCIALES` | ¿Diagnóstico diferencial clave? |
> | `TRATAMIENTO_PSICOLOGICO` | ¿Tratamiento psicológico recomendado? |
> | Otras siglas en mayúsculas | Pregunta de reconocimiento de término |

---

### PASO 5 — Responder las preguntas

1. Lees la pregunta en pantalla
2. Ves 3 opciones con letras **A**, **B**, **C**
3. Haces clic en la que crees que es correcta
4. La app inmediatamente te muestra:
   - ✅ **Verde** si acertaste
   - ❌ **Rojo** si fallaste (y resalta en verde cuál era la correcta)
5. Después de 1.2 segundos, pasa automáticamente a la siguiente pregunta
6. Arriba ves la **barra de progreso** y tu **puntaje actual**

---

### PASO 6 — Ver los resultados finales

Al terminar todas las preguntas aparece:

- Un **porcentaje** grande (ej: 75%)
- Cuántas preguntas respondiste correctamente
- Un mensaje de retroalimentación
- Un **resumen de todas tus respuestas** abajo, donde puedes ver:
  - Qué respondiste en cada pregunta
  - Cuál era la respuesta correcta (cuando fallaste)

---

### PASO 7 — Opciones al terminar

Tienes dos botones:

| Botón | Qué hace |
|---|---|
| **← Nuevo texto** | Vuelve al inicio para pegar otro texto DSM |
| **↺ Repetir** | Juega otra vez con las mismas preguntas (tu puntaje se reinicia) |

---

## 💾 Guardado automático

La app guarda tu progreso automáticamente en el navegador. Esto significa:

- Si cierras la pestaña a mitad del juego, al volver a abrir `dsm-juego.html` **continúa donde lo dejaste**
- El guardado es por navegador y dispositivo (no se sincroniza con otros equipos)

---

## 🔄 Cómo reiniciar desde cero

- Haz clic en el botón **"↺ Reiniciar"** en la pantalla inicial
- O en el botón **"← Nuevo texto"** al final del juego
- Confirma el diálogo que aparece

---

## 🌐 Cómo publicar en GitHub Pages (opcional)

Si quieres que otras personas puedan acceder al juego desde internet:

1. Crea una cuenta en [github.com](https://github.com) si no tienes una
2. Haz clic en **"New repository"** (botón verde)
3. Ponle un nombre (ej: `dsm-quiz`)
4. Marca la opción **"Public"**
5. Haz clic en **"Create repository"**
6. En la página del repositorio, haz clic en **"Add file"** → **"Upload files"**
7. Arrastra el archivo `dsm-juego.html` a la zona de carga
8. **MUY IMPORTANTE:** renombra el archivo a `index.html` antes de subir, o después edita el nombre en GitHub
9. Haz clic en **"Commit changes"**
10. Ve a **Settings** → **Pages** (en el menú lateral izquierdo)
11. En "Source", selecciona **"Deploy from a branch"**
12. En "Branch", selecciona **"main"** y carpeta **"/ (root)"**
13. Haz clic en **"Save"**
14. Espera 1-2 minutos y tu juego estará en: `https://TU_USUARIO.github.io/dsm-quiz/`

---

## ❓ Preguntas frecuentes

**¿Necesito internet para usar el juego?**
Solo la primera vez (para cargar las fuentes tipográficas de Google). Después funciona offline.

**¿El texto que pego se envía a algún servidor?**
No. Todo el procesamiento ocurre en tu navegador, localmente. Ningún dato sale de tu dispositivo.

**¿Puedo usarlo en el celular?**
Sí, está adaptado para pantallas pequeñas.

**¿Qué pasa si pego texto que no tiene ninguna palabra clave?**
La app te avisará con un mensaje y te sugerirá usar el texto de ejemplo.

**¿Puedo agregar mis propias preguntas?**
Por ahora las preguntas se generan automáticamente desde el texto. Para personalizar las preguntas es necesario editar el archivo HTML (sección `generarPreguntas()` en el código JavaScript).

---

## 🛠️ Tecnologías usadas

- HTML5, CSS3, JavaScript puro (vanilla)
- `localStorage` para guardar el progreso
- Google Fonts: Syne + DM Sans
- Sin dependencias externas ni frameworks

---

*Desarrollado como herramienta de estudio para ciencias de la salud mental.*
