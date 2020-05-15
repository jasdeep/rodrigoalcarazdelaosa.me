---
title: Movimientos
subtitle: MRU, MRUV Y MCU
summary: MRU, MRUV y MCU.
tags:
- 4º ESO
- movimiento
categories:
- Física

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Imagen de [**Shutterbug75**](https://pixabay.com/es/users/shutterbug75-2077322/) en [Pixabay](https://pixabay.com/es/)
  focal_point: Smart

links:
- icon_pack: fas
  icon: download
  name: PDF Póster
  url: movimientos-poster.pdf  

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---

{{% toc %}}

## Movimiento rectilíneo uniforme (MRU)
Las **características** del **movimiento rectilíneo uniforme (MRU)** son:

- Trayectoria rectilínea.
- Velocidad $v$ constante (aceleración $a=0$).

La **ecuación principal**[^1] del MRU es:
[^1]: Esta es la llamada **ecuación del movimiento** o **ecuación de la posición**, pues nos da la posición $x$ en función del tiempo $t$.

$$
x(t) = x_0 + v(t-t_0),
$$

donde $x$ es la posición final, $x_0$ la posición inicial, $v$ la velocidad, $t$ el tiempo final y $t_0$ el tiempo inicial.

### Gráficas
{{< figure src="graficas-MRU.png" lightbox="true" >}}

### Ejemplo
{{% alert example %}}
<br>

> Un caracol recorre en línea recta una distancia de $10.8\thinspace\mathrm m$ en $1.5\thinspace\mathrm h$. ¿Qué distancia recorrerá en $5\thinspace\mathrm{min}$?

---

Escribimos la ecuación del movimiento del caracol:
$$
x(t) = x_0 + vt,
$$
donde $x = 10.8\thinspace\mathrm m$, $x_0 = 0$, $v$ es la velocidad del caracol (desconocida) y $t=1.5\thinspace\mathrm h$.

Como nos preguntan la distancia que recorrerá, $\Delta x = x-x_0$, en $5\thinspace\mathrm{min}$, podemos pasar las $1.5\thinspace\mathrm h$ a minutos:

$$
1.5\thinspace\cancel{\mathrm h}\cdot \frac{60\thinspace\mathrm{min}}{1\thinspace\cancel{\mathrm h}} = 90\thinspace\mathrm{min}
$$

y así calcular la velocidad en m/min:
$$
10.8\thinspace\mathrm m = 0 + v\cdot 90\thinspace\mathrm{min} \rightarrow v = 0.12\thinspace\mathrm{m/min}
$$

La distancia recorrida en $5\thinspace\mathrm{min}$ será por tanto:
$$
\Delta x (5\thinspace\mathrm{min}) = x(5\thinspace\mathrm{min}) - x_0 =  0.12\thinspace\mathrm{m/\cancel{min}} \cdot 5\thinspace\cancel{\mathrm{min}} = 0.6\thinspace\mathrm m
$$
{{% /alert %}}

## Movimiento rectilíneo uniformemente variado (MRUV)

Las **características** del **movimiento rectilíneo uniformemente variado (MRUV)** son:

- Trayectoria rectilínea.
- Aceleración $a$ constante (velocidad $v$ variable).

La **ecuaciones principales** del MRUV son:
\begin{align*}
	\label{eq:1}
	\text{Ecuación de la posición: } x(t) &= x_0 +v_0(t-t_0) +\frac{1}{2}a(t-t_0)^2 \tag{1} \\\\
	\label{eq:2}
	\text{Ecuación de la velocidad: } v(t) &= v_0 + a(t-t_0) \tag{2} \\\\
	\label{eq:v2}
	v^2-v_0^2 &= 2a\Delta x \tag{3}
\end{align*}

donde $x$ es la posición final, $x_0$ la posición inicial, $v_0$ la velocidad inicial, $a$ la aceleración, $t$ el tiempo final, $t_0$ el tiempo inicial y $\Delta x = x-x_0$ es la distancia o espacio recorrido.

### Gráficas
{{< figure src="graficas-MRUV.png" lightbox="true" >}}

### Ejemplo
{{% alert example %}}
<br>

> Un coche que circula a $70.2\thinspace\mathrm{km/h}$ disminuye su velocidad a razón de $3\thinspace\mathrm{m/s}$ cada segundo. ¿Qué distancia recorrerá hasta detenerse?

---

Lo primero pasamos la **velocidad inicial** $v_0$ a m/s:
$$
v_0 = 70.2\thinspace\frac{\cancel{\mathrm{km}}}{\cancel{\mathrm{h}}}\cdot \frac{1000\thinspace\mathrm m}{\thinspace\cancel{\mathrm{km}}} \cdot \frac{1\thinspace\cancel{\mathrm h}}{3600\thinspace\mathrm s} = 19.5\thinspace\mathrm{m/s}
$$

La frase "*disminuye su velocidad a razón de $3\thinspace\mathrm{m/s}$ cada segundo*" la tenemos que interpretar como que su **aceleración** $a=-3\thinspace\mathrm{m/s^2}$ (el signo $-$ es porque su velocidad disminuye, y la velocidad la tomamos positiva). Como no me dan información sobre tiempo ni me piden ningún tiempo (sino distancia recorrida $\Delta x$), utilizo la ecuación (3):
$$
v^2-v_0^2 = 2a\Delta x, \tag{3}
$$
de donde despejo la distancia recorrida $\Delta x$:
$$
\Delta x = \frac{v^2-v_0^2}{2a} = \frac{0^2-19.5^2}{2\cdot (-3)} = 63.375\thinspace\mathrm m
$$
{{% /alert %}}

## Caída libre/lanzamiento vertical
La **caída libre** o **lanzamiento vertical** es un caso especial de MRUV en el que la aceleración es igual a la aceleración de la **gravedad**[^2]. En el caso de la Tierra, $a=-g=-9.8\thinspace\mathrm{m/s^2}$ (el signo $-$ indica que la aceleración de la gravedad apunta, siempre, hacia abajo).
[^2]: Valores de la aceleración de la **gravedad** en los astros del Sistema Solar:

	| Astro | $g$ | $\mathrm{m/s^2}$ |
	| --- | :---: | :---: |
	| Sol :sunny: | 28.02 | 274.8 |
	| Júpiter &#9795; | 2.53 | 24.8 |
	| Neptuno &#9798; | 1.14 | 11.2 |
	| Saturno &#9796; | 1.07 | 10.4 |
	| Tierra &#9793; | 1 | 9.8 |
	| Venus &#9792; | 0.90 | 8.9 |
	| Urano &#9797; | 0.89 | 8.7 |	
	| Marte &#9794; | 0.38 | 3.7 |						
	| Mercurio &#9791; | 0.38 | 3.7 |
	| Luna :crescent_moon: | 0.17 | 1.6 |

### Ejemplo
{{% alert example %}}
<br>

> Desde la azotea de un rascacielos de $120\thinspace\mathrm m$ de altura se lanza una piedra con velocidad de $5\thinspace\mathrm{m/s}$, hacia abajo. Calcular: a) Tiempo que tarda en llegar al suelo, b) velocidad con que choca contra el suelo.

---

Escribimos la **ecuación del movimiento** (1) de la piedra:
$$
y(t) = y_0 + v_0 t + \frac{1}{2}at^2, \tag{1}
$$
donde $y_0 = 120\thinspace\mathrm m$, $v_0 = -5\thinspace\mathrm{m/s}$ (hacia abajo) y $a=-g=-9.8\thinspace\mathrm{m/s^2}$, de forma que la ecuación particularizada queda:
$$
y(t) = 120 - 5t + \frac{1}{2}\cdot (-9.8)\cdot t^2 = 120-5t-4.9t^2
$$

a) De la ecuación (1) podemos despejar el tiempo que tarda en llegar al suelo, sabiendo que cuando llega al suelo, $y=0$:
\begin{gather*}
	0 = 120 - 5t -4.9t^2 \\\\
	4.9t^2+5t-120=0 \\\\
	t = \frac{-5\pm \sqrt{5^2-4\cdot 4.9\cdot (-120)}}{2\cdot 4.9} = \frac{-5\pm \sqrt{2377}}{9.8} =  \begin{cases}
4.5\thinspace\mathrm s \\\\
\xcancel{-5.5\thinspace\mathrm s}
\end{cases}
\end{gather*}

	\item Para calcular la velocidad con que choca contra el suelo podemos utilizar la ecuación \eqref{eq:2} o la \eqref{eq:v2}:
	\begin{description}
		\item[Utilizando la ecuación \eqref{eq:2}] Sustituyendo el tiempo por el tiempo de llegada al suelo:
		\[
		v(t) = v_0 + at = -5-9.8t = -5-9.8\cdot 4.5 = \SI{-48.8}{\m/\s}
		\]
		\item[Utilizando la ecuación \eqref{eq:v2}] Teniendo cuidado al calcular $\Delta x = x-x_0 = 0-120 = \SI{-120}{\m}$ e imponiendo el signo $-$ al despejar $v$:
		\begin{gather*}
			v^2-v_0^2 = 2a\Delta x \tag{3} \\
			v = - \sqrt{v_0^2 + 2a\Delta x} = - \sqrt{(-5)^2 + 2\cdot (-9.8)\cdot (0-250)} = - \SI{48.8}{\m/\s}
		\end{gather*}
	\end{description}
\end{enumerate}
{{% /alert %}}