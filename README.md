# Experimento de Selección Léxica

Implementación web del experimento de selección léxica adaptado de Schmitt et al. (2001), diseñado para estudiar la activación de lemas y la distinción entre las etapas de conceptualización y activación sintáctica durante la producción del lenguaje.

---

## Descripción

Este experimento es una adaptación del paradigma *Go/No Go* de decisión dual propuesto por Schmitt et al. (2001). Se basa en el **Modelo del acceso léxico para la producción de Levelt, Roelofs, & Meyer (1999)**, que distingue dos etapas de selección léxica: la conceptualización y la activación de lemas con sus propiedades sintácticas.

El experimento presenta a los participantes imágenes de objetos cotidianos en dos condiciones experimentales:

- **Condición Conceptual (Fase 1):** el participante debe responder *1* si el objeto tiene un peso menor a 500 gr *y* su nombre es femenino; de lo contrario responde *0*. Esta condición activa primero la representación conceptual (el peso).
- **Condición Sintaxis (Fase 2):** el participante debe responder *1* si el nombre del objeto es femenino *y* pesa menos de 500 gr; de lo contrario responde *0*. Esta condición activa primero la información sintáctica del lema (el género gramatical).

Se registran el **tiempo de respuesta** y la **tasa de aciertos** en cada condición. Según Schmitt et al. (2001), los participantes tardan en promedio unos 30 ms más en la condición sintáctica que en la conceptual, lo que proporciona evidencia a favor de la independencia de ambas etapas de acceso léxico.

---

## Estructura del repositorio

```
seleccion-lexica/
├── index.html          # Experimento completo (autocontenido, imágenes embebidas)
├── README.md           # Este archivo
├── EXPERIMENT.md       # Documentación científica detallada
└── LICENSE             # Licencia de uso
```

> **Nota:** `index.html` es un archivo autocontenido (~38 MB). Todas las imágenes de los estímulos están embebidas en Base64 y no se necesitan archivos externos para ejecutarlo.

---

## Cómo usar

### Opción 1: Directamente en el navegador

1. Descarga `index.html`.
2. Ábrelo con cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
3. No requiere servidor ni conexión a internet.

### Opción 2: GitHub Pages

1. Haz un *fork* de este repositorio.
2. Ve a **Settings → Pages**.
3. Selecciona la rama `main` y la carpeta raíz `/`.
4. El experimento estará disponible en `https://<tu-usuario>.github.io/<nombre-del-repo>/`.

---

## Flujo del experimento

```
Bienvenida
    │
    ▼
Instrucciones práctica — Fase 1
    │
    ▼
Ensayos de práctica Fase 1  (4 ensayos, con indicador de progreso)
    │
    ▼
Instrucciones Fase 1
    │
    ▼
Fase 1 — Condición Conceptual  (20 ensayos)
    │
    ▼
Instrucciones práctica — Fase 2
    │
    ▼
Ensayos de práctica Fase 2  (4 ensayos, con indicador de progreso)
    │
    ▼
Instrucciones Fase 2
    │
    ▼
Fase 2 — Condición Sintaxis  (20 ensayos)
    │
    ▼
Resultados (TR promedio, aciertos, gráficas)
```

Cada ensayo sigue la secuencia: **cruz de fijación (500 ms) → imagen del estímulo → respuesta del participante**.

---

## Teclas de respuesta

| Tecla | Significado |
|-------|-------------|
| `1`   | Sí (cumple ambos criterios) |
| `0`   | No |

---

## Resultados mostrados

Al finalizar, el experimento muestra:

- Tiempo de respuesta promedio en la condición Conceptual (ms)
- Tiempo de respuesta promedio en la condición Sintaxis (ms)
- Número de aciertos en la condición Conceptual (sobre 20)
- Número de aciertos en la condición Sintaxis (sobre 20)
- Gráfica de barras del tiempo de respuesta promedio por condición
- Gráfica de barras del número de aciertos por condición

---

## Requisitos técnicos

- Navegador web moderno con soporte para JavaScript ES6+
- No requiere instalación, servidor web ni conexión a internet
- Compatible con Windows, macOS y Linux
- Resolución de pantalla recomendada: 1024 × 768 o superior

---

## Base teórica

El experimento replica el paradigma de Schmitt et al. (2001) para poner a prueba las predicciones del modelo de producción léxica de **Levelt, Roelofs, & Meyer (1999)**. Consulta [`EXPERIMENT.md`](EXPERIMENT.md) para una descripción científica completa del marco teórico, las hipótesis y el diseño experimental.

---

## Referencias

Levelt, W. J., Roelofs, A., & Meyer, A. S. (1999). A theory of lexical access in speech production. *Behavioral and Brain Sciences, 22*(1), 1–38.

Schmitt, B. M., Schiltz, K., Zaake, W., Kutas, M., & Münte, T. F. (2001). An electrophysiological analysis of the time course of conceptual and syntactic encoding during tacit picture naming. *Journal of Cognitive Neuroscience, 13*(4), 510–522.

---

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo [`LICENSE`](LICENSE) para más información.
