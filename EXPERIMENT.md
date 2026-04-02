# Documentación científica del experimento

## Índice

1. [Marco teórico](#1-marco-teórico)
2. [El experimento de Schmitt et al. (2001)](#2-el-experimento-de-schmitt-et-al-2001)
3. [Diseño experimental](#3-diseño-experimental)
4. [Variables](#4-variables)
5. [Hipótesis](#5-hipótesis)
6. [Procedimiento](#6-procedimiento)
7. [Interpretación de los resultados](#7-interpretación-de-los-resultados)
8. [Referencias](#8-referencias)

---

## 1. Marco teórico

### El modelo de acceso léxico de Levelt, Roelofs, & Meyer (1999)

El Modelo del acceso léxico para la producción de Levelt, Roelofs, & Meyer (1999) describe el proceso mediante el cual los hablantes seleccionan y articulan palabras. El modelo distingue varias etapas secuenciales que van desde la intención comunicativa hasta la articulación fonética.

#### 1.1 Selección léxica

La selección léxica comprende dos etapas diferenciadas:

**Conceptualización**
Al intentar denominar una imagen observada, el sistema cognitivo elabora un mensaje pre-verbal. En esta etapa se activa el *concepto léxico* correspondiente al objeto percibido: una representación semántica y conceptual que incluye propiedades como la categoría del objeto, su función, su tamaño o su peso. El hablante selecciona el concepto léxico más apropiado para expresar su intención comunicativa.

**Activación de lemas**
A partir del concepto léxico activado, el sistema accede al *lema*, que es la representación abstracta de la palabra que incluye su significado y sus propiedades sintácticas, como el género gramatical, el número o la categoría gramatical (nombre, verbo, adjetivo, etc.). El modelo predice que la información conceptual se activa antes que la información sintáctica, y que generalmente solo se selecciona un lema de entre todos los que se activan en paralelo.

#### 1.2 Codificación morfológica y fonológica

Tras la selección léxica, ocurre la codificación morfológica, con tres subfases:

- **Recuperación de códigos morfológicos:** se accede a la forma fonológica de las palabras y se seleccionan los morfemas que componen la palabra.
- **Codificación fonológica y silabificación:** los morfemas se ensamblan en segmentos fonológicos ordenados y se estructura la sílaba.
- **Codificación fonética:** se generan instrucciones motoras basadas en el plan silábico para ejecutar la articulación.

#### 1.3 Predicción clave del modelo

El modelo de Levelt et al. (1999) predice que la información **conceptual** (propiedades semánticas como el peso o la forma) se activa **antes** que la información **sintáctica** (propiedades gramaticales como el género). Esta predicción es directamente comprobable mediante tareas que disocian ambos tipos de información, como el paradigma utilizado por Schmitt et al. (2001).

---

## 2. El experimento de Schmitt et al. (2001)

Schmitt, Schiltz, Zaake, Kutas, & Münte (2001) diseñaron un experimento electrofisiológico de denominación silenciosa de imágenes (*tacit picture naming*) para estudiar el curso temporal de la codificación conceptual y sintáctica durante la producción léxica.

### 2.1 Paradigma Go/No Go de decisión dual

El paradigma consiste en presentar imágenes de objetos cotidianos y pedir a los participantes que respondan en función de **dos criterios combinados**: uno de naturaleza conceptual (el peso del objeto) y otro de naturaleza sintáctica (el género gramatical de su nombre en español).

La clave del diseño es el **orden de activación de los criterios**:

- En la condición **conceptual**, el criterio que debe evaluarse en primer lugar es el peso (información semántico-conceptual), y solo si este criterio se cumple, el participante evalúa el género gramatical.
- En la condición **sintáctica**, el criterio que debe evaluarse en primer lugar es el género (información sintáctica del lema), y solo si este criterio se cumple, el participante evalúa el peso.

Si el modelo de Levelt et al. (1999) es correcto y la información conceptual se activa antes que la sintáctica, entonces la condición conceptual debería resultar en tiempos de respuesta más cortos, ya que el criterio evaluado primero (el peso) coincide con el orden de activación natural del sistema.

### 2.2 Resultados originales

Schmitt et al. (2001) encontraron que, en promedio, los participantes tardaban **aproximadamente 30 milisegundos más** en la condición sintáctica que en la condición conceptual. Este resultado es consistente con la predicción del modelo de Levelt et al. (1999): acceder primero a información sintáctica (género) antes que a la conceptual (peso) conlleva un coste temporal, porque el sistema de producción léxica activa la información conceptual de forma anterior a la sintáctica.

---

## 3. Diseño experimental

### 3.1 Tipo de diseño

Diseño intrasujeto (medidas repetidas) con dos condiciones experimentales:

| Condición | Nombre | Criterio de evaluación |
|-----------|--------|------------------------|
| Condición 1 | Conceptual | Peso primero → Género |
| Condición 2 | Sintaxis | Género primero → Peso |

Todos los participantes completan ambas condiciones. El orden de las condiciones es fijo: primero la condición conceptual (Fase 1) y después la condición sintáctica (Fase 2).

### 3.2 Estímulos

Se emplean **20 imágenes de objetos cotidianos por condición** (40 ensayos experimentales en total), precedidos por **4 ensayos de práctica por condición** (8 ensayos de práctica en total).

Los estímulos están distribuidos de la siguiente manera:

| Condición | Estímulos correctos (respuesta = 1) | Estímulos incorrectos (respuesta = 0) |
|-----------|--------------------------------------|----------------------------------------|
| Conceptual | 5 imágenes | 15 imágenes |
| Sintaxis | 5 imágenes | 15 imágenes |

### 3.3 Secuencia de un ensayo

Cada ensayo sigue esta secuencia temporal:

```
[Cruz de fijación: 500 ms] → [Imagen del estímulo] → [Respuesta del participante]
```

Tras la respuesta, el siguiente ensayo comienza después de un intervalo de 250 ms.

---

## 4. Variables

### 4.1 Variable independiente

**Condición experimental** (variable intrasujeto, 2 niveles):
- Condición Conceptual: el peso es el criterio primario; el género, el secundario.
- Condición Sintaxis: el género es el criterio primario; el peso, el secundario.

### 4.2 Variables dependientes

- **Tiempo de respuesta (TR):** tiempo en milisegundos transcurrido desde la aparición del estímulo hasta la pulsación de la tecla de respuesta. Se calcula el promedio de todos los ensayos válidos (con respuesta) de cada condición.
- **Tasa de aciertos:** número de respuestas correctas sobre el total de ensayos de cada condición (máximo 20 por condición).

### 4.3 Variables extrañas

Las siguientes variables no están controladas en esta adaptación y podrían afectar los resultados:

- **Orden de las condiciones:** todas las condiciones se presentan en el mismo orden (Conceptual antes que Sintaxis). Un posible efecto de orden o fatiga no puede descartarse.
- **Familiaridad con los objetos:** los objetos representados en las imágenes pueden ser más o menos familiares según la experiencia personal del participante.
- **Frecuencia léxica:** la frecuencia de uso de los nombres de los objetos puede influir en la velocidad de acceso léxico.
- **Ambigüedad de género:** algunos participantes pueden no tener completamente afianzado el género gramatical de ciertos nombres.
- **Estrategias individuales:** los participantes podrían adoptar distintas estrategias de respuesta (priorizar velocidad vs. precisión).
- **Efectos de práctica:** los ensayos de práctica preceden a cada fase experimental, pero el aprendizaje puede continuar a lo largo de los ensayos experimentales.

---

## 5. Hipótesis

### Hipótesis nula (H₀)

No existen diferencias significativas en el tiempo de respuesta promedio entre la condición conceptual y la condición sintáctica. Cualquier diferencia observada se debe al azar.

> H₀: TR(Conceptual) = TR(Sintaxis)

### Hipótesis alternativa (H₁)

El tiempo de respuesta promedio es significativamente mayor en la condición sintáctica que en la condición conceptual, como consecuencia de que el sistema de producción léxica activa la información conceptual con anterioridad a la información sintáctica.

> H₁: TR(Sintaxis) > TR(Conceptual)

Esta hipótesis es consistente con las predicciones del modelo de Levelt, Roelofs, & Meyer (1999) y con los resultados de Schmitt et al. (2001).

---

## 6. Procedimiento

### 6.1 Instrucciones generales

Al iniciar el experimento, los participantes reciben una pantalla de bienvenida que explica la estructura general (dos fases con práctica previa). No se menciona la variable de interés (conceptual vs. sintaxis) para no sesgar las respuestas.

### 6.2 Ensayos de práctica

Antes de cada fase experimental, el participante realiza **4 ensayos de práctica** con las siguientes características:
- Se muestran el contador de ensayos y las teclas de respuesta disponibles (0 y 1).
- El objetivo es familiarizar al participante con la tarea antes de los ensayos experimentales.
- Los datos de práctica no se registran ni se incluyen en los resultados.

### 6.3 Ensayos experimentales

Durante las fases experimentales (Fase 1 y Fase 2):
- La pantalla solo muestra la **cruz de fijación** (500 ms) seguida de la **imagen del estímulo**.
- No aparecen indicaciones de progreso ni recordatorio de teclas, para minimizar posibles interferencias.
- El participante responde con las teclas `1` (sí, cumple ambos criterios) o `0` (no).
- Los **tiempos de respuesta** se registran con precisión de milisegundos mediante `performance.now()`.

### 6.4 Presentación de resultados

Al finalizar el experimento, se presentan automáticamente:
- Una tabla con el TR promedio y el número de aciertos por condición.
- Una gráfica de barras del tiempo de respuesta promedio por condición.
- Una gráfica de barras del número de aciertos por condición.

---

## 7. Interpretación de los resultados

### 7.1 Resultado esperado

Si los datos son consistentes con el modelo de Levelt et al. (1999) y los hallazgos de Schmitt et al. (2001), se esperan los siguientes patrones:

- **TR(Sintaxis) > TR(Conceptual):** acceder al género gramatical antes que al peso del objeto supone un coste temporal, porque el sistema de producción léxica accede antes a la información conceptual que a la sintáctica.
- Las diferencias de precisión (aciertos) entre condiciones pueden ser pequeñas o inexistentes si el participante comprende bien la tarea.

### 7.2 Resultado nulo o inverso

Si no se observa diferencia, o si el TR es mayor en la condición conceptual, puede deberse a:

- Tamaño de muestra insuficiente (un único participante tiene alta variabilidad).
- Estrategias individuales que compensen el coste de acceder al género primero.
- Efectos de orden o fatiga si la Fase 2 se realiza con el participante más cansado.
- Baja familiaridad con algunos objetos o sus nombres.

### 7.3 Comparación con el experimento original

La adaptación aquí implementada difiere del experimento original de Schmitt et al. (2001) en varios aspectos relevantes:

| Aspecto | Schmitt et al. (2001) | Esta adaptación |
|---------|----------------------|-----------------|
| Respuesta | Pedal derecho/izquierdo | Tecla 1 / tecla 0 |
| Registro | EEG + tiempo de respuesta | Solo tiempo de respuesta |
| Participantes | Grupo de participantes | Un participante |
| Idioma | Alemán | Español |
| Análisis estadístico | Inferencial (t de Student) | Descriptivo |

---

## 8. Referencias

Levelt, W. J., Roelofs, A., & Meyer, A. S. (1999). A theory of lexical access in speech production. *Behavioral and Brain Sciences, 22*(1), 1–38. https://doi.org/10.1017/S0140525X99001776

Schmitt, B. M., Schiltz, K., Zaake, W., Kutas, M., & Münte, T. F. (2001). An electrophysiological analysis of the time course of conceptual and syntactic encoding during tacit picture naming. *Journal of Cognitive Neuroscience, 13*(4), 510–522. https://doi.org/10.1162/08989290152001925

