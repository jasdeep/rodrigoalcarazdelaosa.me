---
title: Fluidos
summary: Concepto de presión, principios de la hidrostática y física de la atmósfera.

slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: white
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: tomorrow
---

# Fluidos

- [Concepto de presión](#/1)
- [Principios de la hidrostática](#/2)
- [Física de la atmósfera](#/3)

Descarga estas diapositivas en formato PDF[{{< icon name="download" pack="fas" >}}](fluidos-diapositivas.pdf)

---

{{% section %}}

## Concepto de presión

La **presión**, $p$, es una magnitud escalar que relaciona la fuerza $F$ (ejercida perpendicularmente) con la superficie $A$ sobre la que actúa:
$$
p = \frac{F}{A}
$$

(continúa hacia abajo)

👇

---

### Unidades
En el SI la presión se mide en $\mathrm{N/m^2}$, que recibe el nombre de **pascal** ($1\thinspace\mathrm{Pa} = 1\thinspace\mathrm{N/m^2}$). La siguiente tabla muestra otras unidades de presión y su equivalencia entre ellas:

[https://en.wikipedia.org/wiki/Template:Pressure_Units](https://en.wikipedia.org/wiki/Template:Pressure_Units)

{{% /section %}}

---

{{% section %}}

## Principios de la hidrostática

- [Principio de Pascal](#/2/1)
- [Principio fundamental de la hidrostática](#/2/1)
- [Principio de Arquímedes](#/2/1)

(continúa hacia abajo)

👇

---

### Principio de Pascal
> Todo cambio de presión en un punto de un fluido incompresible encerrado en un recipiente de paredes indeformables se transmite con igual intensidad en todas las direcciones y en todos los puntos del fluido.

---

{{< youtube iPQ3WORwUYQ >}}

---

#### Elevador hidráulico

{{< figure library="true" src="fluidos-4ESO/elevador-hidraulico.png" lightbox="false" >}}

$$
p_1 = p_2 \Rightarrow \frac{F_1}{A_1} = \frac{F_2}{A_2} \Rightarrow F_1A_2 = F_2A_1
$$

---

Lo primero que tenemos que hacer es _**homogeneizar**_ las unidades. Podemos convertir el volumen, $0.5\thinspace\mathrm L$, en $\mathrm{cm^3}$:
$$
0.5\thinspace\mathrm L\cdot \frac{1\thinspace\mathrm{dm^3}}{1\thinspace\mathrm L}\cdot \frac{10^3\thinspace\mathrm{cm^3}}{1\thinspace\mathrm{dm^3}} = 500\thinspace\mathrm{cm^3}
$$

---

A partir de la expresión de la densidad, podemos **despejar** la **masa** $m$:
$$
d = \frac{m}{V}\rightarrow m = V\cdot d = 500\thinspace\mathrm{cm^3} \cdot 0.79\thinspace\mathrm{g/cm^3} = 395\thinspace\mathrm{g} = 0.395\thinspace\mathrm{kg}
$$

---

<q>Calcula el volumen que ocupan $390\thinspace\mathrm g$ de una sustancia cuya densidad es de $2390\thinspace\mathrm{kg/m^3}$.</q>

---

Ya que la densidad nos la dan en unidades del SI, pasamos la masa, $m=390\thinspace\mathrm g$, a kg:
$$
m = 390\thinspace\mathrm g \cdot \frac{1\thinspace\mathrm{kg}}{10^3\thinspace\mathrm g} = 0.390\thinspace\mathrm{kg}
$$

---

A partir de la expresión de la densidad, despejamos el volumen $V$:

$$
d = \frac{m}{V}\rightarrow V = \frac{m}{d} = \frac{0.390\thinspace\mathrm{kg}}{2390\thinspace\mathrm{kg/m^3}} = 1.632\times 10^{-4}\thinspace\mathrm{m^3} = 163.2\thinspace\mathrm{cm^3}
$$

{{% /section %}}

---

{{% section %}}

## Estados de agregación

- [Sólido](#/3/2)
- [Líquido](#/3/3)
- [Gaseoso](#/3/4)
- [Cambios de estado](#/3/5)

(continúa hacia abajo)

👇

---

Los tres principales **estados de agregación** en los que podemos encontrar a la materia son:

---

### Sólido
- Volumen y forma fijos.
- No se pueden comprimir.
- No fluyen por sí mismos.

---

### Líquido
- Volumen fijo, forma variable.
- Poco compresibles.
- Pueden fluir.

---

### Gaseoso
- Volumen y forma variables.
- Se comprimen.
- Fluyen fácilmente.

---

### Cambios de estado
La materia puede **cambiar** de **estado** al **variar** la **presión** o **temperatura**, permaneciendo su masa constante mientras que su volumen varía.

---

{{< figure library="true" src="materia-2ESO-3ESO/cambios-estado.png" lightbox="false" >}}

---

Además, **durante** un **cambio** de **estado** la **temperatura** permance **constante**, como se muestra en la siguiente curva de calentamiento de una sustancia pura:

---

{{< figure library="true" src="materia-2ESO-3ESO/grafica-calentamiento.png" lightbox="false" >}}

---

Las **temperaturas** (o puntos) de **fusión** y **ebullición** (ambas aumentan con la presión) son, al igual que la densidad, **propiedades características** de la materia.

{{% /section %}}

---

{{% section %}}

## Modelo cinético-molecular

- [Postulados](#/4/1)
- [Explicación de los estados de agregación](#/4/2)
- [Simulación](#/4/6)

(continúa hacia abajo)

👇

---

### Postulados

<ul>
	{{% fragment %}} <li>La <strong>materia</strong> está <strong>formada</strong> por <strong>partículas</strong> muy pequeñas, entre las que no existe nada (vacío).</li> {{% /fragment %}}
	{{% fragment %}} <li>Existen <strong>fuerzas</strong> de <strong>atracción</strong> que mantienen unidas a las partículas.</li> {{% /fragment %}}
	{{% fragment %}} <li>Las partículas están en <strong>continuo movimiento</strong>, siendo la <strong>temperatura</strong> una medida de la velocidad media a la que se mueven (a mayor temperatura mayor velocidad).</li> {{% /fragment %}}
</ul>

---

### Explicación de los estados de agregación

---

#### Sólido

{{< figure library="true" src="materia-2ESO-3ESO/solido.png" title="En un **sólido** la **interacción** entre las partículas es muy **fuerte**, y éstas están **vibrando**." lightbox="false" width="55%" >}}

---

#### Líquido

{{< figure library="true" src="materia-2ESO-3ESO/liquido.png" title="En un **líquido** la **interacción** entre las partículas es **intermedia**, y éstas además de **vibrar** pueden **rotar** y **moverse** ligeramente." lightbox="false" width="55%" >}}

---

#### Gas

{{< figure library="true" src="materia-2ESO-3ESO/gas.png" title="En un **gas** las partículas **apenas interactúan** entre sí y éstas se **mueven aleatoriamente** en todas las direcciones." lightbox="false" width="55%" >}}

---

### Simulación

---

<iframe src="https://phet.colorado.edu/sims/html/states-of-matter-basics/latest/states-of-matter-basics_es.html" width="720" height="600" scrolling="no" allowfullscreen></iframe>

{{% /section %}}

---

{{% section %}}

## Mezclas

- [Tipos](#/5/2)
- [Disoluciones](#/5/3)
- [Métodos de separación](#/5/11)

(continúa hacia abajo)

👇

---

Al mezclarse dos o más sustancias distintas, no se obtiene una nueva sustancia, ya que las sustancias que forman la mezcla **conservan** sus **propiedades** y **pueden separarse** mediante procedimientos físico-químicos.

---

### Tipos
<h4>{{% fragment %}} Homogéneas {{% /fragment %}}</h4>
{{% fragment %}} Aquellas en las que **no** es posible distinguir sus componentes a simple vista. {{% /fragment %}}

<h4>{{% fragment %}} Heterogéneas {{% /fragment %}}</h4>
{{% fragment %}} Aquellas en las que **sí** es posible distinguir sus componentes a simple vista. {{% /fragment %}}

---

### Disoluciones
Son un buen ejemplo de **mezclas homogéneas**, cuyos componentes pueden ser tanto sólidos, líquidos o gases. En una **disolución** distinguimos dos **componentes**:

---

<h4>{{% fragment %}} Soluto {{% /fragment %}}</h4>
{{% fragment %}} El componente que está en menor proporción. {{% /fragment %}}

<h4>{{% fragment %}} Disolvente {{% /fragment %}}</h4>
{{% fragment %}} El componente que está en mayor proporción. {{% /fragment %}}

---

#### Concentración
Podemos expresar la **concentración** de una disolución de varias formas distintas, entre ellas:

---

##### g/L
Expresa el número de gramos de soluto por cada litro de disolución:
$$
c\thinspace(\mathrm{g/L}) = \frac{m_\text{soluto}\thinspace (\mathrm{g})}{V_\text{disolución}\thinspace (\mathrm{L})}
$$

---
	
##### % en masa
Expresa el número de gramos de soluto por cada $100\thinspace\mathrm g$ de disolución:
$$
c\thinspace(\\%\thinspace m) = \frac{m_\text{soluto}}{m_\text{soluto}+m_\text{disolución}}\times 100
$$

---
	
##### % en volumen
Expresa el número de litros de soluto por cada $100\thinspace\mathrm L$ de disolución:
$$
c\thinspace(\\%\thinspace V) = \frac{V_\text{soluto}}{V_\text{soluto}+V_\text{disolución}}\times 100
$$

---

##### Simulación
Puedes aprender más con esta **simulación**, donde se expresa la concentración en mol/L, es decir, cuántos moles de soluto hay por cada litro de disolución:

---

<iframe src="https://phet.colorado.edu/sims/html/concentration/latest/concentration_es.html" width="720" height="600" scrolling="no" allowfullscreen></iframe>

---

### Métodos de separación

---

#### Decantación
Método **físico** para separar mezclas **heterogéneas** de líquidos y sólidos no solubles (suspendidos) o de líquidos no miscibles de **diferente densidad** (con un embudo de decantación).

---

#### Filtración
Método **físico** para separar mezclas **heterogéneas** de líquidos y sólidos no solubles a través de un medio poroso, llamado tamiz, criba, cedazo o **filtro**.

---

#### Destilación
Método **físico** para separar mezclas de líquidos con **distinto punto de ebullición**.

{{< figure library="true" src="materia-2ESO-3ESO/destilacion.png" title="Imagen de [OpenClipart-Vectors](https://pixabay.com/es/users/openclipart-vectors-30363/) en [Pixabay](https://pixabay.com/es/)." lightbox="false" width=65% >}}

---

#### Cristalización
Método **químico** para separar mezclas **homogéneas**, como sólidos disueltos en líquidos.

{{% /section %}}