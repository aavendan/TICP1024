---
title: Introducción
layout: home
parent: Contenidos
nav_order: 0
---

# Visualización de Datos
## ¿Qué es la visualización y por qué utilizarla?

---

## Definición de visualización

La visualización se define como:

{: .important }
> Sistemas computacionales que generan representaciones visuales de datos diseñadas para ayudar a las personas a realizar tareas de manera más efectiva.
>
> _Computer-based visualization systems provide visual representations of datasets designed to help people carry out tasks more effectively._ (Munzner, T.)

<details markdown="block">
  <summary>
    🧠 Elementos clave
  </summary>

1. Personas y Datos
2. Tareas
3. Representación visual
</details>

---

## El rol del ser humano (Human-in-the-loop)

<div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 20px;">
  <div>
    <h4>❌ ¿Cuándo NO es necesaria la visualización?</h4>
    No se necesita visualización cuando existe una <b>solución completamente automática confiable</b>.
  </div>
  <div>
    <h4>✔️ ¿En qué casos SÍ es útil la visualización?</h4>
    - Para usuarios finales que analizan datos continuamente, p.e.: EDAs científicos<br>
    - Para comunicar hallazgos ya identificados, p.e.: <a href="https://www.nytimes.com/international/section/upshot">The New York Times – Upshot</a><br>
    - Comprensión del problema y en la definición de los requerimientos (Paso previo al desarrollo de modelos).<br>
    - Refinamiento de los algoritmos, ajuste parámetros y validación del comportamiento del modelo.<br>
    - Evaluación de los resultados, detección errores y validación de sistemas automáticos.
  </div>
  <div>
    <h4>❓ Problemas de análisis mal definidos</h4>
    Muchos problemas de análisis de datos mal especificados, lo que significa que:<br>
    - No se conocen exactamente las preguntas desde el inicio<br>
    - Existen múltiples posibles direcciones de análisis<br>
    - Se requiere exploración y adaptación continua<br>
  </div>
</div>

{: .highlight }
> La visualización no reemplaza a los sistemas automáticos, sino que los complementa, especialmente cuando hay incertidumbre, exploración o necesidad de interpretación.

---

## Representaciones visual: Cognición vs Percepción

La visualización permite:

- Reducir carga cognitiva
- Transformar tareas *cognitivas* en **perceptuales**

### 📊 Leer tablas → requiere memoria

| ID | Valor A | Valor B | Valor C |
|----|--------|--------|--------|
| 1  | 12     | 45     | 78     |
| 2  | 15     | 50     | 82     |
| 3  | 11     | 47     | 80     |
| 4  | 18     | 52     | 85     |
| 5  | 14     | 49     | 79     |

### 🎨 Ver visualización → permite detectar patrones rápidamente

| ID | Valor A | Valor B | Valor C |
|----|--------|--------|--------|
| 1  | 🟢     | 🟡     | 🔴     |
| 2  | 🟢     | 🟡     | 🔴     |
| 3  | 🟢     | 🟡     | 🔴     |
| 4  | 🟢     | 🔴     | 🔴     |
| 5  | 🟢     | 🟡     | 🔴     |

**Leyenda:**
- 🟢 Bajo  
- 🟡 Medio  
- 🔴 Alto  

{: .highlight }
> La visualización transforma tareas cognitivas (leer, recordar, comparar) en tareas perceptuales (ver, reconocer, identificar).


---

## ¿Por qué la visión?

<img src="../files/images/senses.png" alt="¿Por qué la visión?" width="75%">