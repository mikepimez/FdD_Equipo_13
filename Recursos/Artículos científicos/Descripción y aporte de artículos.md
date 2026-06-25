# 📑 Descripción y Aportes de Artículos Científicos — Equipo 13

En esta sección se detalla el análisis exhaustivo de los artículos científicos indizados utilizados como la base de conocimiento para el desarrollo de **Eco-Vent 13** bajo la metodología **VDI 2206**. Cada artículo aporta evidencia cuantitativa que convalida el hardware, la programación de la lógica de control en el microcontrolador y el análisis de restricciones del prototipo.

<p align="center">
  <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC3548274/" target="_blank">
    <img src="https://img.shields.io/badge/ARTÍCULO%201-Satish%20(CO2)-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" style="margin-right: 5px; margin-bottom: 5px;">
  </a>
  <a href="https://www.sciencedirect.com/science/article/abs/pii/S0360132311002617" target="_blank">
    <img src="https://img.shields.io/badge/ARTÍCULO%202-Bakó--Biró%20(Ventilación)-green?style=for-the-badge&logo=read-the-docs&logoColor=white" style="margin-right: 5px; margin-bottom: 5px;">
  </a>
  <a href="https://dialnet.unirioja.es/servlet/articulo?codigo=6171218" target="_blank">
    <img src="https://img.shields.io/badge/ARTÍCULO%203-Pacsi%20(PM10)-orange?style=for-the-badge&logo=read-the-docs&logoColor=white" style="margin-right: 5px; margin-bottom: 5px;">
  </a>
  <a href="https://www.mdpi.com/2071-1050/13/8/4139" target="_blank">
    <img src="https://img.shields.io/badge/ARTÍCULO%204-Diaz%20(Clima)-red?style=for-the-badge&logo=read-the-docs&logoColor=white" style="margin-right: 5px; margin-bottom: 5px;">
  </a>
  <a href="https://doi.org/10.1016/j.buildenv.2018.03.040" target="_blank">
    <img src="https://img.shields.io/badge/ARTÍCULO%205-Johnson%20(Modelado)-purple?style=for-the-badge&logo=read-the-docs&logoColor=white" style="margin-bottom: 5px;">
  </a>
</p>

---

## Artículo 1: Is CO₂ an Indoor Pollutant? Direct Effects of Low-to-Moderate CO₂ Concentrations on Human Decision-Making Performance

* **Autores:** Usha Satish, Mark J. Mendell, Krishnamurthy Shekhar, Toshifumi Hotchi, Douglas Sullivan, Siegfried Streufert, and William J. Fisk.
* **Año / Revista:** 2012 | *Environmental Health Perspectives*
* **Descripción:** Estudio experimental controlado en cámara de simulación ambiental que aisló el Dióxido de Carbono (CO₂) como variable independiente pura, evaluando a 22 participantes expuestos de forma síncrona a niveles de 600, 1000 y 2500 ppm mediante pruebas neurocognitivas computarizadas.
* **Aporte directo al proyecto:**
    * **Fundamento de Automatización:** El paper demuestra que al alcanzar las 1000 ppm ocurren decrementos moderados significativos en la toma de decisiones, mientras que a 2500 ppm las reducciones son severas y disfuncionales. Esto convalida que al ser un contaminante invisible que degrada la cognición sin provocar alertas sensoriales inmediatas, los sistemas reactivos manuales fallan, justificando un lazo cerrado autónomo donde el dispositivo sustituya la intervención humana.
    * **Calibración Algorítmica:** Establece con precisión el umbral de activación del software en >= 1000 ppm para el sensor de calidad de aire, y el nivel de alerta crítica en el indicador visual en > 1500 ppm, correspondientes a las zonas de riesgo neurocognitivo validadas en la investigación.
* **Limitaciones del estudio:** La exposición se limitó a periodos fijos de 2.5 horas con inyección de gas ultrapuro, sin considerar mezclas con partículas sólidas en suspensión ni jornadas continuas de 8 horas.

---

## Artículo 2: Ventilation rates in schools and pupils' performance

* **Autores:** Zs. Bakó-Biró, D.J. Clements-Croome, N. Kochhar, H.B. Awbi, M.J. Williams.
* **Año / Revista:** 2011 | *Building and Environment*
* **Descripción:** Investigación experimental de campo con diseño cruzado repetido aplicada a más de 200 alumnos en 16 aulas de educación primaria en Inglaterra, donde se implementó un sistema de ventilación mecánica portátil para elevar el suministro de aire de 1 l/s a 8 l/s por persona.
* **Aporte directo al proyecto:**
    * **Justificación de Ventilación Forzada:** Demuestra de forma empírica que elevar el suministro de aire exterior mitiga los picos históricos de 5000 ppm de CO₂ y acelera de forma significativa la velocidad de respuesta correcta en pruebas de atención, memoria y reconocimiento verbal. Esto convalida el uso de ventilación mecánica controlada sobre el monitoreo pasivo.
    * **Validación Acústica:** Establece la restricción de diseño para proteger el entorno de estudio: el sistema mecánico no debe superar los 35 dB de ruido durante la operación, asegurando que la introducción de los extractores axiales no interfiera con la concentración ni las actividades académicas.
* **Limitaciones del estudio:** El sistema portátil empleado requería una potencia de calefacción por ducto de 3 kW, restricción que el proyecto optimiza mediante un diseño de bajo consumo (menor a 3 W) apto para realidades con limitaciones energéticas.

---

## Artículo 3: Análisis temporal y espacial de la calidad del aire determinado por material particulado PM10 y PM2.5 en Lima Metropolitana

* **Autor:** Sergio A. Pacsi Valdivia.
* **Año / Revista:** 2016 | *Anales Científicos (UNALM)*
* **Descripción:** Estudio empírico multianual (2001-2014) que procesa las bases de datos de las redes de monitoreo automático y semiautomático de DIGESA y SENAMHI distribuidas en Lima Metropolitana y el Callao.
* **Aporte directo al proyecto:**
    * **Dimensionamiento del Problema Local:** El artículo evidencia que los promedios anuales de material particulado superan de forma sostenida los Estándares de Calidad Ambiental (ENCA) del Perú y las guías de la OMS, señalando explícitamente a las zonas Sur, Este y Norte de Lima con las mayores concentraciones (superiores a 100 ug/m³). Esto fundamenta la urgencia de implementar el dispositivo en distritos de alta vulnerabilidad industrial y del transporte, como Villa María del Triunfo.
    * **Inclusión de Filtración Mecánica:** Detalla que la resuspensión de polvo debido a calles sin pavimentar eleva el PM10 grueso de forma crítica. Esto valida mecánicamente que el diseño del chasis vertical (220x220x110 mm) incorpore un ducto con filtración mecánica granular acoplado a la inyección, protegiendo los espacios interiores del ingreso de contaminantes externos.
* **Limitaciones del estudio:** Los datos provienen de macroestaciones fijas instaladas en techos de edificios públicos, lo que genera un punto ciego respecto a la concentración real a nivel de respiración dentro de un microentorno cerrado.

---

## Artículo 4: Effects of Climatic Conditions, Season and Environmental Factors on CO₂ Concentrations in Naturally Ventilated Primary Schools in Chile

* **Autores:** Muriel Diaz, Mario Cools, Maureen Trebilcock, Beatriz Piderit-Moreno, Shady Attia.
* **Año / Revista:** 2021 | *Sustainability*
* **Descripción:** Análisis transversal basado en el monitoreo físico continuo de CO₂, temperatura y humedad relativa (intervalos de 5 minutos) en 8 escuelas de educación primaria libres de ventilación mecánica, aplicando Regresión Logística Binaria (BLR) para determinar la probabilidad de éxito en el control ambiental.
* **Aporte directo al proyecto:**
    * **Convalidación de la Lógica de Control:** El modelo demuestra una dependencia crítica entre la acumulación de gases y la temperatura interior (p-value < 0.05). En temporadas frías, la necesidad de conservar el calor anula la disposición a abrir ventanas, relegando la calidad del aire y provocando picos continuos de 5000 ppm de CO₂. Esto justifica la integración síncrona en el firmware de la terna de sensado (gases y temperatura): el sistema procesará simultáneamente las variables térmicas y químicas para ejecutar la renovación neumática de forma aislada, protegiendo la salud sin destruir el confort térmico.
    * **Especificación de Restricciones:** Avala que la ventilación pasiva es termodinámicamente incapaz de estabilizar el aire interior en ambientes de alta densidad escolar (densidades de 1.1 a 1.9 m²/alumno), validando la selección de un sistema mecatrónico autónomo.
* **Limitaciones del estudio:** La investigación careció de instrumentación automatizada para el registro exacto de las aperturas de ventanas, dependiendo de aproximaciones indirectas de temperatura de bulbo seco.

---

## Artículo 5: Indoor air quality in classrooms: Environmental measures and effective ventilation rate modeling in urban elementary schools

* **Autores:** David L. Johnson, Robert A. Lynch, Evan L. Floyd, Jun Wang, Jacob N. Bartels.
* **Año / Revista:** 2018 | *Building and Environment*
* **Descripción:** Evaluación de la calidad del aire interior en aulas de 12 escuelas urbanas midiendo contaminantes químicos y físicos durante periodos de 24 horas por estación, modelando las tasas de ventilación fresca efectiva mediante un enfoque matemático de balance de masa transitorio.
* **Aporte directo al proyecto:**
    * **Arquitectura del Flujo Lógico:** El estudio demuestra que las concentraciones de CO₂ en aulas rara vez alcanzan condiciones de equilibrio dinámico (estado estable), validando que el modelado lógico de Eco-Vent debe estructurarse analizando los flujos en intervalos discretos de acumulación y decaimiento. Esto justifica el uso de un banco de relés independientes para gestionar cada ventilador de forma aislada, asegurando el control de los flujos físicos sin caídas de tensión.
    * **Modelado del Volumen de Control:** Proporciona el marco matemático transitorio para verificar experimentalmente que la tasa de renovación de aire real de la arquitectura Push-Pull (4 ventiladores axiales) mitiga eficazmente los contaminantes dentro del volumen de control nominal establecido de 30 m³.
* **Limitaciones del estudio:** El modelo matemático asume una mezcla instantánea y uniforme del aire en todo el volumen, una condición idealizada que en la práctica se ve afectada por la fricción geométrica y la ubicación física del dispositivo dentro del habitáculo.
