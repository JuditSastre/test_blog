---
title: "Testeando los cuadros de texto posibles"
tags:
  - Text box
author_profile: true
---

Estos son los cuadros de texto que sé hacer:
Pone el texto entre líneas

 ---
**Glosario**


* **Nanopartícula**: Cualquier partícula cuyo tamaño esté en el orden del nanómetro. En el caso de los virus, suelen medir entre 20 y 
250 nanómetros, es decir, entre 0’000000002 y 0’00000025 metros.
* **Material genético**: nos referimos a las moléculas que guardan la información genética. Estas moléculas pueden ser el ADN 
(ácido desoxirribonucleico) o el ARN (ácido ribonucleico). 
* **Proteína**: esta seguro que no coge de nuevas a nadie. Solemos pensar en ellas como algo que encontramos en la carne, pero 
son mucho más que eso (preguntadle a un bioquímico, si no). Las proteínas son moléculas, muy grandes, formadas por secuencias de 
aminoácidos. En una célula, se encargan de casi todos los procesos que os podáis imaginar.
* **Interacción débil**: llamamos interacción débil a todas aquellas interacciones entre moléculas que no impliquen enlace químico. 
Algunas de las más conocidas son los puentes de hidrógeno, las interacciones electroestáticas, las fuerzas de Van der Waals y, de 
las que hemos hablado hoy, las interacciones hidrofóbicas. 
* **Miscible**: se dice de un líquido que es capaz de mezclarse con otro en cualquier proporción. 

---
&nbsp;  
&nbsp;  
A esto le llaman blockquote

> **Glosario**
> 
> 
> * **Nanopartícula**: Cualquier partícula cuyo tamaño esté en el orden del nanómetro. En el caso de los virus, suelen medir entre 20 y 
> 250 nanómetros, es decir, entre 0’000000002 y 0’00000025 metros.
> * **Material genético**: nos referimos a las moléculas que guardan la información genética. Estas moléculas pueden ser el ADN 
> (ácido desoxirribonucleico) o el ARN (ácido ribonucleico). 
> * **Proteína**: esta seguro que no coge de nuevas a nadie. Solemos pensar en ellas como algo que encontramos en la carne, pero 
> son mucho más que eso (preguntadle a un bioquímico, si no). Las proteínas son moléculas, muy grandes, formadas por secuencias de 
> aminoácidos. En una célula, se encargan de casi todos los procesos que os podáis imaginar.
> * **Interacción débil**: llamamos interacción débil a todas aquellas interacciones entre moléculas que no impliquen enlace químico. 
> Algunas de las más conocidas son los puentes de hidrógeno, las interacciones electroestáticas, las fuerzas de Van der Waals y, de 
> las que hemos hablado hoy, las interacciones hidrofóbicas. 
> * **Miscible**: se dice de un líquido que es capaz de mezclarse con otro en cualquier proporción.

&nbsp;  
&nbsp; 

To format code or text into its own distinct block, use triple backticks \`

```
**Glosario**


* **Nanopartícula**: Cualquier partícula cuyo tamaño esté en el orden del nanómetro. En el caso de los virus, suelen medir entre 20 y 
250 nanómetros, es decir, entre 0’000000002 y 0’00000025 metros.
* **Material genético**: nos referimos a las moléculas que guardan la información genética. Estas moléculas pueden ser el ADN 
(ácido desoxirribonucleico) o el ARN (ácido ribonucleico). 
* **Proteína**: esta seguro que no coge de nuevas a nadie. Solemos pensar en ellas como algo que encontramos en la carne, pero 
son mucho más que eso (preguntadle a un bioquímico, si no). Las proteínas son moléculas, muy grandes, formadas por secuencias de 
aminoácidos. En una célula, se encargan de casi todos los procesos que os podáis imaginar.
* **Interacción débil**: llamamos interacción débil a todas aquellas interacciones entre moléculas que no impliquen enlace químico. 
Algunas de las más conocidas son los puentes de hidrógeno, las interacciones electroestáticas, las fuerzas de Van der Waals y, de 
las que hemos hablado hoy, las interacciones hidrofóbicas. 
* **Miscible**: se dice de un líquido que es capaz de mezclarse con otro en cualquier proporción. 

```

Este es una mierda.
&nbsp;  
&nbsp;

Creando una tabla

| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |


| **Glosario** |          |
| **Nanopartícula**: Cualquier partícula cuyo tamaño esté en el orden del nanómetro. En el caso de los virus, suelen medir entre 20 y 250 nanómetros, es decir, entre 0’000000002 y 0’00000025 metros. |  |
| etc. |    |

También podría ser así:

| **Glosario** |          |
| **Nanopartícula** | Cualquier partícula cuyo tamaño esté en el orden del nanómetro. En el caso de los virus, suelen medir entre 20 y 250 nanómetros, es decir, entre 0’000000002 y 0’00000025 metros. |
| **etc.** |  muchas etc's  |

O muy a pelo, con html de la muerte:

<p style="border: 3px; border-style:solid; border-color:#FF0000; padding: 1em;"><b> Glosario</b><br><b> Nanopartícula</b> Cualquier partícula cuyo tamaño esté en el orden del nanómetro. En el caso de los virus, suelen medir entre 20 y 250 nanómetros, es decir, entre 0’000000002 y 0’00000025 metros.<br><b>Otras definiciones</b> Significa esto y lo otro. </p>

Tiene esta pinta:

```
<p style="border: 3px; border-style:solid; border-color:#FF0000; padding: 1em;"><b> Glosario</b><br><b> Nanopartícula</b> Cualquier partícula cuyo tamaño esté en el orden del nanómetro. En el caso de los virus, suelen medir entre 20 y 250 nanómetros, es decir, entre 0’000000002 y 0’00000025 metros.<br><b>Otras definiciones</b> Significa esto y lo otro. </p>

```
