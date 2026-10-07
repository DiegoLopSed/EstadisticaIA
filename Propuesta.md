## Propuesta de experimento estadístico (UVP)

**Tema:** ¿Qué herramientas de IA usan y conocen las y los estudiantes de la Universidad del Valle de Puebla (UVP) y con qué frecuencia las utilizan?

### 1) Objetivo

Estimar y comparar el **nivel de conocimiento** y la **frecuencia de uso** de herramientas de IA (p. ej., ChatGPT, Gemini, Copilot, Canva IA, etc.) en estudiantes de UVP, e identificar si hay diferencias por **área/carrera** y **semestre**.

---

## 2) Población, muestra y tipo de muestreo

### Población

Estudiantes inscritos en la UVP.

### Tamaño de muestra

**n ≈ 50 estudiantes**.

### Tipo de muestreo

**Muestreo aleatorio simple** (de tipo práctico: “interceptación aleatoria” en campus), aplicando el cuestionario mediante un **código QR** en un día de clases.

**Proceso propuesto:**

1. Elegir un día de clases “normal” y 2–3 puntos de contacto dentro del campus (p. ej., entrada, pasillo principal, cafetería o afuera de salones).
2. Preparar el QR que dirige al formulario y llevarlo impreso o en el celular.

---

## 3) Diseño del estudio

- **Tipo:** cuantitativo
- **Instrumento:** cuestionario breve (5–10 min), Fromspree.
- **Variables principales:**
    1. **Conocimiento de herramientas de IA** (cuántas conoce).
    2. **Uso de herramientas de IA** (frecuencia).
    3. **Herramientas específicas** (cuáles usa/conoce).
    4. **Finalidad de uso** (tareas, estudio, programación, diseño, investigación, etc.).

---

## 4) Datos a recolectar

### Sección A. Perfil

- Carrera (categórica)
- Semestre (numérica o categórica)
- Edad (numérica, opcional)

### Sección B. Conocimiento y uso

- “Marca las herramientas de IA que **conoces**” (lista).
    - Variable derivada: `n_conocidas` (conteo)
- “Marca las herramientas de IA que **usas** actualmente” (lista).
    - Variable derivada: `n_usadas` (conteo)
- Frecuencia de uso (ordinal):
    - 0 = nunca
    - 1 = 1–2 veces al mes
    - 2 = 1 vez por semana
    - 3 = 2–3 veces por semana
    - 4 = diario
    - Variable: `freq_uso`
- “Uso IA para tareas académicas” (Likert 1–5)
    - Variable: `uso_academico`

## 5) Hipótesis

### Hipótesis

**Pregunta:** ¿El conocimiento de herramientas de IA es alto en estudiantes de la UVP?

- **H0 (nula):** la media de herramientas de IA conocidas es **≤ 3**.
- **H1 (alternativa):** la media de herramientas de IA conocidas es **> 3**.

**Variable:** `n_conocidas`.

**Prueba sugerida:** t de una muestra (o alternativa no paramétrica si la distribución es muy asimétrica).

---

## 6) Procedimiento (paso a paso)

1. Diseñar el formulario (15–20 preguntas máximo).
2. Definir estratos y/o cuotas para alcanzar n≈50.
3. Aplicar el cuestionario (1–2 días).
4. Depurar datos (duplicados, faltantes).
5. Analizar:
    - Descriptivos: promedio de `n_conocidas`, top de herramientas usadas, distribución de `freq_uso`
    - Comparaciones por carrera/semestre (si aplica)
6. Concluir: herramientas dominantes, usos principales y diferencias por grupo.

---

## 7) Herramientas de IA (lista sugerida)

### Asistentes de texto / estudio

- ChatGPT
- Google Gemini
- Claude
- Perplexity
- Notion AI

### Programación

- GitHub Copilot
- Codeium
- ChatGPT (para código)

### Diseño e imagen

- Canva IA
- DALL·E / Midjourney

### Escritura y corrección

- Grammarly
- LanguageTool
- QuillBot

### Presentaciones

- Gamma
- Canva (presentaciones con IA)