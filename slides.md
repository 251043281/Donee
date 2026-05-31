---
title-slide: false
bibliography: references.bib
csl: vancouver.csl
citeproc: true
theme: serif
background-color: "#ffffff"
transition: slide
navigationMode: linear
hash: true
---

:::: {.columns}
::: {.column width="50%"}

## Sample slides
#### PlaceHolderName
#### Universiti Malaysia Perlis
#### [placeholder@email.com](mailto:placeholder@email.com)

<!-- __AUDIO_INTRO_DO_NOT_TOUCH__ -->

:::

::: {.column width="50%"}
![](media/pics/logo1.png)
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Slide one
**Key Concepts:**
- Energy conservation per @carnot1824.
- $\Delta U = Q - W$
:::

::: {.column width="50%"}
![](media/pics/sample.png)
:::
::::

---

<span class="slide-title" data-title="My Hidden Slide Name"></span>

![](media/pics/wide.jpeg)

---

:::: {.columns}
::: {.column width="50%"}
### The Master Equation
The fundamental relation of thermodynamics:

$$\Delta U = Q - W$$

The work done $W$ is positive when the system expands against an external pressure.
:::

::: {.column width="50%"}
<video data-src="media/videos/sample.mp4" data-autoplay loop muted width="100%"></video>
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Visualizing the Gas Law
**Interactive Model:**

- P, V, and T relationships.
- Use the slider to adjust pressure.
- Observe the phase boundary.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/sample.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::

---

# Process Control: Machine 1

:::::::::::::: {.columns}
::: {.column width="50%"}
### Key Statistics
- **Mean**: 51.046 $\mu$
- **Median**: 51.091 $\mu$
- **Std Dev**: 0.584 $\sigma$

Configuration:
- Temp: 303K
- Pressure: 100kPa
:::

::: {.column width="50%"}
<iframe data-src='media/plots/control_chart_m1.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::::::::::::

---

# Process Capability Analysis

:::::::::::::: {.columns}
::: {.column width="40%"}
### Analysis (Machine 1)
- **Temperature**: 338K
- **Pressure**: 200kPa

This chart visualizes the distribution of part lengths against calculated control limits to determine if the process is capable of meeting specifications.
:::

::: {.column width="60%"}
![](media/plots/capability_m1.png)
:::
::::::::::::::
