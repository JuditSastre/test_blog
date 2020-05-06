---
title: "Testeando los cuadros de texto posibles"
tags:
  - Text box
author_profile: true
header-includes:
    - \usepackage[most]{tcolorbox}
    - \definecolor{light-yellow}{rgb}{1, 0.95, 0.7}
    - \newtcolorbox{myquote}{colback=light-yellow,grow to right by=-10mm,grow to left by=-10mm, boxrule=0pt,boxsep=0pt,breakable}
    - \newcommand{\todo}[1]{\begin{myquote} \textbf{TODO:} \emph{#1} \end{myquote}}
---

Estos son los cuadros de texto que sé hacer:
1. Pone el texto entre líneas

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
2. A esto le llaman blockquote

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
3. Latex-based table


blah blah

\todo{something}

blah

&nbsp;  
&nbsp;
4. multiple line table with one row and no header
----------------------- ------------------------------------
![Tip](images/tip.png)\ Table multiline text bla bla bla bla
                        bla bla bla bla bla bla bla ... the
                        blank line below is important 

----------------------------------------------------------------
