# Teoría de los Números Transfinitos — Plan de Curso

**Área:** Lógica Matemática · Teoría de Conjuntos

> *"El infinito es donde las cosas suceden que no suceden en ningún otro lugar."*
> — Georg Cantor

---

## Bloque I — Fundamentos: Lógica y Teoría de Conjuntos
*Clases 1 – 4*

---

### Clase 1 — Lógica de Primer Orden: Sintaxis, Semántica y Deducción

**Temas principales:**
- Lenguaje formal de primer orden ($L_1$): términos, fórmulas, cuantificadores
- Interpretaciones, modelos y satisfacibilidad
- Consecuencia semántica ($\models$) y consecuencia sintáctica ($\vdash$)
- Sistemas de deducción natural
- Teoremas de Completitud y Compacidad de Gödel

**Descripción:**
Se establece el lenguaje formal de primer orden como sustrato de toda la teoría posterior. Se revisan las nociones de fórmula, interpretación y consecuencia —tanto semántica como sintáctica— y se enuncia el Teorema de Completitud de Gödel. Esta sesión garantiza que el estudiante comprenda el marco deductivo en el que opera la teoría de conjuntos.

---

### Clase 2 — Axiomática de Zermelo–Fraenkel con el Axioma de Elección (ZFC)

**Temas principales:**
- Los nueve axiomas de ZF (Extensionalidad, Vacío, Pares, Unión, Potencia, Infinito, Reemplazo, Regularidad, Separación)
- Axioma de Elección (AC) y su formulación
- Lema de Zorn
- Teorema del Buen Orden
- Equivalencias clásicas del AC

**Descripción:**
Se presentan los axiomas de ZF y se añade el Axioma de Elección, examinando sus formulaciones equivalentes más relevantes: el Lema de Zorn y el Teorema del Buen Orden. Se discute por qué ZFC constituye el sistema axiomático estándar para la matemática contemporánea y se anticipa su rol central en la construcción de la jerarquía transfinita.

---

### Clase 3 — Relaciones, Órdenes y Conjuntos Bien Ordenados

**Temas principales:**
- Relaciones binarias: propiedades fundamentales
- Órdenes parciales y totales
- Conjuntos bien ordenados: definición y ejemplos
- Segmentos iniciales e isomorfismos de orden
- Inducción transfinita (introducción preliminar)

**Descripción:**
Se estudian las estructuras de orden que subyacen a la teoría transfinita. Se demuestran los teoremas fundamentales sobre segmentos iniciales y se introduce de forma preliminar el principio de inducción transfinita, preparando el terreno para la definición formal de ordinales en la sesión siguiente.

---

### Clase 4 — Funciones, Equipotencia e Infinitud: Primeros Resultados de Cantor

**Temas principales:**
- Funciones inyectivas, sobreyectivas y biyectivas
- Conjuntos finitos, Dedekind-infinitos e infinitos
- Equipotencia ($A \sim B$) como relación de equivalencia
- Teorema de Cantor–Bernstein–Schröder
- Conjuntos numerables y no numerables; argumento diagonal de Cantor

**Descripción:**
Se formaliza la noción de cardinalidad mediante la equipotencia de conjuntos. Se demuestra el Teorema de Cantor–Bernstein–Schröder y se establece la no numerabilidad de $\mathbb{R}$ mediante el argumento diagonal. Esta sesión marca el inicio conceptual de la teoría transfinita: distintos "tamaños" de infinito coexisten de forma rigurosa.

---

## Bloque II — Números Transfinitos
*Clases 5 – 10*

---

### Clase 5 — Números Ordinales: Definición, Jerarquía y Aritmética Elemental

**Temas principales:**
- Ordinales de von Neumann: $\alpha = \{\beta : \beta < \alpha\}$
- Ordinales sucesor y ordinales límite
- $\omega$ como primer ordinal infinito
- Inducción y recursión transfinita (formulación completa)
- Suma y producto ordinal; no conmutatividad

**Descripción:**
Se define formalmente el número ordinal mediante la representación canónica de von Neumann y se establece la distinción fundamental entre ordinales sucesor y ordinales límite. Se introduce $\omega$ y se desarrolla la aritmética ordinal elemental, destacando las propiedades que la distinguen de la aritmética de los naturales, en particular su falta de conmutatividad.

---

### Clase 6 — Aritmética Ordinal Avanzada y la Jerarquía de Ordinales Infinitos

**Temas principales:**
- Potenciación ordinal
- Teorema de la Forma Normal de Cantor
- El ordinal $\varepsilon_0$ y la jerarquía de ordinales épsilon
- Puntos fijos de $\alpha \mapsto \omega^\alpha$
- Cofinalidad de un ordinal (introducción)

**Descripción:**
Se completa la aritmética ordinal con la potenciación y se demuestra el Teorema de la Forma Normal de Cantor. Se estudia el ordinal $\varepsilon_0$ —primer punto fijo de $\alpha \mapsto \omega^\alpha$— y se introduce la noción de cofinalidad, esencial para clasificar ordinales límite. Se exploran las propiedades estructurales de la jerarquía ordinal transfinita en toda su extensión.

---

### Clase 7 — Números Cardinales Transfinitos: Alephs y Teorema de Cantor

**Temas principales:**
- Cardinales como ordinales iniciales
- Sucesión de alephs: $\aleph_0, \aleph_1, \aleph_2, \ldots, \aleph_\omega, \ldots$
- Teorema de Cantor: $|A| < |\mathcal{P}(A)|$ para todo conjunto $A$
- Beth numbers: $\beth_0, \beth_1, \beth_2, \ldots$
- Noción introductoria de cardinales inaccesibles

**Descripción:**
Se define el cardinal de un conjunto como el ordinal inicial de su clase de equipotencia y se construye la jerarquía aleph. Se demuestra el Teorema de Cantor en su forma general, estableciendo que no existe un conjunto de todos los cardinales. Se introduce la secuencia de beth numbers y se contrasta con la secuencia aleph, anticipando la Hipótesis del Continuo.

---

### Clase 8 — Aritmética Cardinal Transfinita

**Temas principales:**
- Suma y producto de cardinales infinitos
- Potenciación cardinal: $\kappa^\lambda$
- Teorema de König (generalización transfinita)
- Cofinalidad y cardinales regulares
- Cardinales singulares: definición y ejemplos

**Descripción:**
Se desarrolla la aritmética de cardinales infinitos destacando simplificaciones sin análogo finito (e.g., $\kappa + \kappa = \kappa$ para $\kappa$ infinito). Se demuestra el Teorema de König y se profundiza en la noción de cofinalidad para clasificar los cardinales en regulares y singulares, categoría crucial en el estudio de la aritmética de cardinales grandes.

---

### Clase 9 — La Hipótesis del Continuo: Enunciado, Historia e Independencia

**Temas principales:**
- Hipótesis del Continuo (HC): $2^{\aleph_0} = \aleph_1$
- Hipótesis Generalizada del Continuo (HCG): $2^{\aleph_\alpha} = \aleph_{\alpha+1}$
- Universo constructible de Gödel ($L$) y consistencia de HC con ZFC
- Método de forcing de Cohen (introducción conceptual)
- Independencia de HC respecto de ZFC

**Descripción:**
Se enuncia la Hipótesis del Continuo —primer problema de Hilbert en 1900— y su generalización. Se expone el resultado de Gödel (1940): HC es consistente con ZFC mediante el universo constructible $L$. Se introduce conceptualmente el forcing de Paul Cohen (1963), con el que se probó que $\neg\text{HC}$ también es consistente con ZFC, estableciendo su independencia completa del sistema axiomático estándar.

---

### Clase 10 — Horizontes: Cardinales Grandes, Determinismo y Límites de ZFC

**Temas principales:**
- Cardinales inaccesibles y cardinales de Mahlo
- Cardinales medibles y la jerarquía de cardinales grandes
- Jerarquía de consistencia entre extensiones de ZFC
- Axioma de Determinismo (AD) e incompatibilidad con AC
- Preguntas abiertas en teoría de conjuntos contemporánea

**Descripción:**
La sesión de cierre sitúa los números transfinitos en el panorama de la investigación actual. Se introducen los cardinales grandes como extensiones axiomáticas de ZFC que ordenan una jerarquía de consistencia. Se discute el Axioma de Determinismo y su incompatibilidad con el Axioma de Elección ($\text{AD} \not\Leftrightarrow \text{AC}$). Se concluye reflexionando sobre los límites epistemológicos del formalismo conjuntista y las líneas de investigación abiertas en teoría de conjuntos.

---
