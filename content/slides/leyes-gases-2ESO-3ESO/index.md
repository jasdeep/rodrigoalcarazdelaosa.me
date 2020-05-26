---
title: Leyes de los gases
summary: "Ley de Boyle-Mariotte, ley de Charles y ley de Gay-Lussac."
tags:
- 3º ESO
- gases
categories:
- Física
- Química

slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: white
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: tomorrow
---

# Leyes de los gases

[Ley de Boyle-Mariotte](#/1), [ley de Charles](#/2) y [ley de Gay-Lussac](#/3)

[Simulación](#/4)

---

{{% section %}}

## Ley de Boyle-Mariotte

(continúa hacia abajo)

👇

---

<q>A **temperatura constante**, el volumen de una masa fija de gas es inversamente proporcional a la presión que éste ejerce.</q>
  
---

### Matemáticamente

\begin{align*}
	pV &= \text{constante} \\\\
	& \text{o} \\\\
	p_1 V_1 &= p_2 V_2,
\end{align*}

donde:

- $p_1$ es la presión inicial.
- $V_1$ es el volumen inicial.
- $p_2$ es la presión final.
- $V_2$ es el volumen final.

---

### Ejemplo

<q>El volumen del aire en los pulmones de una persona es de $615\thinspace\mathrm{mL}$ aproximadamente, a una presión de $1\thinspace\mathrm{atm}$. La inhalación ocurre cuando la presión de los pulmones desciende a $0.989\thinspace\mathrm{atm}$. ¿A qué volumen se expanden los pulmones?</q>

---

No nos lo dicen explícitamente pero tenemos que suponer que la **temperatura** permanece **constante**, por lo que debemos aplicar la ley de **Boyle-Mariotte**:		
$$
p_1 V_1 = p_2 V_2,
$$
donde $p_1=1\thinspace\mathrm{atm}$, $V_1=615\thinspace\mathrm{mL}$, $p_2=0.989\thinspace\mathrm{atm}$ y $V_2$ es lo que nos piden.

---

Despejamos $V_2$:
$$
V_2 = \frac{p_1 V_1}{p_2} = \frac{1\thinspace\mathrm{atm}\cdot 615\thinspace\mathrm{mL}}{0.989\thinspace\mathrm{atm}} = 621.8\thinspace\mathrm{mL}
$$

{{% /section %}}

---

{{% section %}}

## Ley de Charles

(continúa hacia abajo)

👇

---

<q>Para una cierta cantidad de gas a **presión constante**, su volumen es directamente proporcional a su temperatura.</q>
  
---

### Matemáticamente
\begin{align*}
	\frac{V}{T} &= \text{constante} \\\\
	& \text{o} \\\\
	\frac{V_1}{T_1} &= \frac{V_2}{T_2},
\end{align*}

donde:		

- $V_1$ es el volumen inicial.
- $T_1$ es la temperatura inicial (¡en K!).
- $V_2$ es el volumen final.
- $T_2$ es la temperatura final (¡en K!).

---

### Ejemplo

<q>Si cierta masa de gas, a presión constante, llena un recipiente de $20\thinspace\mathrm{L}$ de capacidad a la temperatura de $124\thinspace\mathrm{^\circ C}$, ¿qué temperatura alcanzará la misma cantidad de gas a presión constante, si el volumen aumenta a $30\thinspace\mathrm{L}$?</q>

---

Nos dicen explícitamente que la **presión** permanece **constante**, por lo que aplicamos la ley de **Charles**:		
$$
\frac{V_1}{T_1} = \frac{V_2}{T_2},
$$

donde $V_1 = 20\thinspace\mathrm{L}$, $T_1 = 124\thinspace\mathrm{^\circ C} = 397\thinspace\mathrm{K}$, $V_2 = 30\thinspace\mathrm{L}$ y $T_2$ es lo que nos piden.

---

Despejamos $T_2$:
$$
T_2 = T_1\cdot \frac{V_2}{V_1} = 397\thinspace\mathrm{K}\cdot \frac{30\thinspace\mathrm{L}}{20\thinspace\mathrm{L}} = 595.5\thinspace\mathrm{K} = 322.5\thinspace\mathrm{^\circ C}
$$

{{% /section %}}

---

{{% section %}}

## Ley de Gay-Lussac

(continúa hacia abajo)

👇

---

<q>La presión que ejerce un **volumen fijo** de gas es directamente proporcional a su temperatura.</q>
  
---

### Matemáticamente
\begin{align*}
	\frac{p}{T} &= \text{constante} \\\\
	& \text{o} \\\\
	\frac{p_1}{T_1} &= \frac{p_2}{T_2},
\end{align*}

donde:		

- $p_1$ es la presión inicial.
- $T_1$ es la temperatura inicial (¡en K!).
- $p_2$ es la presión final.
- $T_2$ es la temperatura final (¡en K!).

---

### Ejemplo

<q>Es peligroso que los envases de aerosoles se expongan al calor. Si una lata de fijador para el cabello a una presión de $4\thinspace\mathrm{atm}$ y a una temperatura ambiente de $27\thinspace\mathrm{^\circ C}$ se arroja al fuego y el envase alcanza los $402\thinspace\mathrm{^\circ C}$, ¿cuál será su nueva presión?</q>

---

Suponemos que el envase mantiene su **volumen fijo**, por lo que aplicamos la ley de **Gay-Lussac**:
$$
\frac{p_1}{T_1} = \frac{p_2}{T_2},
$$

donde $p_1 = 4\thinspace\mathrm{atm}$, $T_1 = 27\thinspace\mathrm{^\circ C} = 300\thinspace\mathrm{K}$, $T_2=402\thinspace\mathrm{^\circ C} = 675\thinspace\mathrm{K}$ y $p_2$ es lo que nos piden.

---

Despejamos $p_2$:
$$
p_2 = T_2\cdot \frac{p_1}{T_1} = 675\thinspace\mathrm{K}\cdot \frac{4\thinspace\mathrm{atm}}{300\thinspace\mathrm{K}} = 9\thinspace\mathrm{atm}
$$

{{% /section %}}

---

{{% section %}}

## Simulación

(continúa hacia abajo)

👇

---

<iframe src="https://phet.colorado.edu/sims/html/gases-intro/latest/gases-intro_es.html" width="800" height="600" scrolling="no" allowfullscreen></iframe>

{{% /section %}}