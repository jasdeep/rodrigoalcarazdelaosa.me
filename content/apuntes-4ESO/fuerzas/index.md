---
title: Fuerzas
subtitle: Leyes de Newton y fuerzas de especial interés
summary: "Leyes de Newton y fuerzas de especial interés."
tags:
- 4º ESO
- fuerzas
- movimiento
categories:
- Física

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Foto de [**Andrea Piacquadio**](https://www.pexels.com/es-es/@olly) en [Pexels](https://www.pexels.com/es-es/)
  focal_point: Smart

links:
- icon_pack: fas
  icon: download
  name: PDF Póster
  url: fuerzas-poster.pdf
---

{{% toc %}}

## Naturaleza vectorial de las fuerzas

Las **fuerzas** son **magnitudes vectoriales**, lo que significa que quedan definidas por un **vector**, del cual hay que definir su:

Módulo
: Longitud del segmento.

Dirección
: Recta que lo contiene.

Sentido
: Dado por la punta de la flecha.

{{< figure src="vector.png" title="En dos dimensiones, un vector se puede escribir como $\newcommand{\ihat}{\hat{\imath}}\newcommand{\jhat}{\hat{\jmath}}\vec a = a_x \ihat + a_y \jhat$, donde $\ihat$ y $\jhat$ son vectores unitarios ($\text{módulo} = 1$) a lo largo de los ejes $x$ e $y$. El módulo de $\vec a$, $|\vec a|$, se calcula como (teorema de Pitágoras) $|\vec a| = \sqrt{a_x^2+a_y^2}$." lightbox="true" >}}

### Suma o resta de vectores
Gráficamente, dibujando un vector a continuación del otro y uniendo el origen con el punto final:

{{< figure src="suma-vectores.png" lightbox="true" >}}

O analíticamente, componente a componente:
$$
\vec a + \vec b = (a_x+b_x)\ihat + (a_y+b_y)\jhat
$$

## Leyes de Newton

### 1ª ley (ley de la inercia)
> Todo cuerpo preserva su estado de reposo o movimiento rectilíneo uniforme salvo que actúe una fuerza sobre él.

### 2ª ley (ley fundamental de la Dinámica)
> El cambio de movimiento es proporcional a la fuerza ejercida y se hace en la dirección de la línea recta en que se ejerce la fuerza.

Matemáticamente, se escribe como
$$
\sum\vec F = m\vec a\quad \text{(la aceleración es proporcional a la fuerza neta)}
$$

En el SI la fuerza se mide en Newton (N): $1\thinspace\mathrm N = 1\thinspace \mathrm{kg\thinspace m\thinspace s^{-2}}$.

### 3ª ley (ley de la acción-reacción)
> Para toda acción siempre hay una reacción igual y opuesta.

Si un cuerpo A ejerce una fuerza sobre otro cuerpo B, éste ejercerá sobre A una fuerza igual y de sentido contrario ($\vec F_\text{AB} = -\vec F_\text{BA}$).

## Fuerzas de especial interés

### Peso
El **peso** es la fuerza con la que la Tierra atrae a un objeto. Se calcula como:
$$
\vec P = m\vec g,
$$
donde $m$ es la masa del objeto y $\vec g$ es la aceleración de la gravedad. Siempre se dirige hacia el centro de la Tierra (hacia abajo en la mayoría de los casos).

### Normal
También llamada fuerza de **reacción**, se define como la fuerza que ejerce una superficie sobre un cuerpo apoyado sobre ella. Esta es de igual magnitud y dirección, pero de sentido contrario a la fuerza ejercida por el cuerpo sobre la superficie.

{{< figure src="normal.png" title="Fuerza normal en a) una superficie horizontal, b) un plano inclinado y c) una superficie vertical." lightbox="true" >}}

### Rozamiento $\vec f_\mathrm r$
La **fuerza de rozamiento** es la fuerza que existe entre dos superficies en contacto, oponiéndose siempre al movimiento relativo entre ambas superficies. La fuerza de rozamiento es proporcional a la normal $N$:
$$
f_\mathrm r = \mu N,
$$
donde $\mu$ es el coeficiente de rozamiento.

{{< figure src="rozamiento.png" title="Fuerza de rozamiento en a) una superficie horizontal, b) un plano inclinado y c) una superficie vertical." lightbox="true" >}}

### Centrípeta
Se llama **fuerza centrípeta** a la fuerza o a la componente de la fuerza que actúa sobre un objeto en movimiento sobre una trayectoria curvilínea y que está dirigida hacia el centro de curvatura de la trayectoria. Su módulo se calcula a partir de la **aceleración centrípeta**, haciendo uso de la **2ª ley de Newton**:
$$
f_\mathrm c = m a_\mathrm c = m\cdot \frac{v^2}{R} = \frac{mv^2}{R}
$$

## Ejemplo
{{% alert example %}}
<br>

> Un cuerpo baja por un plano inclinado $30^\circ$ con un coeficiente de rozamiento $\mu=0.2$. Calcula la velocidad que llevará y el espacio recorrido al cabo de $5\thinspace\mathrm s$, si inicialmente estaba en reposo.

---


{{% /alert %}}