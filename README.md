# MEXT Prep — Matemáticas e Inglés

App interactiva para practicar matemáticas e inglés para el examen MEXT de beca Japón.

## Cómo subir a GitHub Pages

### Paso 1 — Subir el archivo
1. Ve a tu repositorio en GitHub (ej. `LuisMartinezProg/dj` o crea uno nuevo)
2. Haz clic en **Add file → Upload files**
3. Sube `index.html` (o nómbralo `mext-prep.html` si no quieres reemplazar nada)
4. Haz clic en **Commit changes**

### Paso 2 — Agregar tu API key
El archivo `index.html` necesita tu API key de Anthropic para generar preguntas.

Abre el archivo en GitHub, haz clic en el ícono de editar (lápiz), y busca esta línea:

```js
var API_KEY = window.ANTHROPIC_KEY || '';
```

Cámbiala por:

```js
var API_KEY = 'sk-ant-TUKEY';
```

Reemplaza `sk-ant-TUKEY` con tu API key real de https://console.anthropic.com

### Paso 3 — Acceder a la app
La URL será:
- Si el archivo se llama `index.html` en una carpeta `mext-prep/`:  
  `https://tuusuario.github.io/turepositorio/mext-prep/`
- Si se llama `mext-prep.html`:  
  `https://tuusuario.github.io/turepositorio/mext-prep.html`

## Temas cubiertos

### Matemáticas (10% del examen MEXT)
- **Fase 1:** Álgebra · Funciones lineales y cuadráticas · Geometría básica · Estadística
- **Fase 2:** Ecuaciones cuadráticas · Trigonometría · Geometría analítica · Probabilidad · Progresiones
- **Fase 3:** Funciones avanzadas · Vectores · Combinatoria · Logaritmos · Distribuciones estadísticas

### Inglés (25% del examen MEXT)
- **Fase 1:** 12 tiempos verbales · Gramática B1 · Vocabulario básico · Corrección de oraciones
- **Fase 2:** Gramática B2 · Phrasal verbs · Vocabulario académico · Comprensión lectora
- **Fase 3:** Vocabulario C1 · Textos académicos · Gramática avanzada · Comprensión inferencial

## Modos de práctica
- **Opción múltiple** — 5 preguntas, 4 opciones, explicación inmediata
- **Completar espacio** — Escribe la respuesta correcta
- **Simulacro** — 10 preguntas con temporizador de 90 segundos

---
Barranquilla → Japón 🎌 · MEXT 2025
