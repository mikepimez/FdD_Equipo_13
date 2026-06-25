# 📜 Descripción y Aportes de Normas Técnicas — Equipo 13

En esta sección se presentan las normas técnicas y los marcos legales nacionales considerados durante el desarrollo del proyecto **Eco-Vent 13**. Estas normativas proporcionan los lineamientos jurídicos, los criterios de diseño ambiental y los estándares de medición necesarios para asegurar que nuestro sistema mecatrónico responda con rigor a las exigencias de salud pública y control atmosférico bajo la metodología VDI 2206.

<p align="center">
  <a href="https://www.gob.pe/institucion/minam/normas-legales/3670-003-2017-minam" target="_blank">
    <img src="https://img.shields.io/badge/NORMA%201-DS%20003--2017--MINAM%20(ECA)-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" style="margin-right: 5px; margin-bottom: 5px;">
  </a>
  <a href="https://sinia.minam.gob.pe/normas/decreto-supremo-que-aprueba-protocolo-nacional-monitoreo-calidad" target="_blank">
    <img src="https://img.shields.io/badge/NORMA%202-DS%20010--2019--MINAM%20(Monitoreo)-green?style=for-the-badge&logo=read-the-docs&logoColor=white" style="margin-right: 5px; margin-bottom: 5px;">
  </a>
  <a href="https://www.gob.pe/institucion/congreso-de-la-republica/normas-legales/3569-28611" target="_blank">
    <img src="https://img.shields.io/badge/NORMA%203-Ley%2028611%20(Ambiente)-orange?style=for-the-badge&logo=read-the-docs&logoColor=white" style="margin-bottom: 5px;">
  </a>
</p>

---

## Norma Técnica 1: Decreto Supremo N° 003-2017-MINAM — Estándares de Calidad Ambiental (ECA) para Aire

### Descripción
Esta norma legal dictada por el Ministerio del Ambiente del Perú establece las medidas concisas de las concentraciones de elementos, sustancias o parámetros físicos y químicos presentes en el aire en su condición de cuerpo receptor. Su propósito es regular los límites máximos destinados a prevenir y resguardar la salud pública, fijando el umbral diario para el Material Particulado con diámetro menor a 10 micras en 100 microgramos por metro cúbico durante un periodo de 24 horas.

### Aporte al proyecto
* **Sustento de Umbrales Ambientales:** Proporciona el marco de referencia legal para justificar el diseño de los filtros mecánicos del dispositivo. Al contrastar estos límites obligatorios con los reportes históricos de saturación en zonas de alta densidad vehicular e industrial de Lima, se convalida técnicamente la necesidad de implementar un sistema cerrado de inyección y extracción forzada capaz de mitigar la exposición crónica a partículas sólidas gruesas.

---

## Norma Técnica 2: Decreto Supremo N° 010-2019-MINAM — Protocolo Nacional de Monitoreo de la Calidad Ambiental del Aire

### Descripción
Este decreto supremo aprueba las disposiciones técnicas y metodológicas estandarizadas para realizar las operaciones de muestreo, medición analítica y aseguramiento de la calidad de los datos de las variables atmosféricas en el territorio nacional. Regula la representatividad de las muestras, los tiempos mínimos de captura de información y los criterios metrológicos para garantizar la validez de los registros de agentes químicos y físicos.

### Aporte al proyecto
* **Validación Metrológica del Firmware:** Convalida la lógica de programación del bucle de control implementado en el microcontrolador. La norma exige que la captura de datos ambientales siga tiempos estandarizados para evitar lecturas erróneas por fluctuaciones momentáneas, lo que justifica técnicamente que el algoritmo procese de forma síncrona las señales de la terna de sensado en intervalos continuos y discretos de tiempo real, asegurando que las pruebas de verificación en el volumen de control tengan validez de ingeniería.

---

## Norma Técnica 3: Ley N° 28611 — Ley General del Ambiente

### Descripción
Es la norma ordenadora del marco jurídico ambiental en el Perú. Establece los principios rectores que consagran el derecho irrenunciable de toda persona a gozar de un entorno saludable, equilibrado y adecuado para el desarrollo de la vida. Asimismo, determina la obligación de las instituciones y ciudadanos de asegurar de manera preventiva la conservación de los recursos y la protección de la salud humana individual y colectiva frente a riesgos de contaminación.

### Aporte al proyecto
* **Fundamento Ético e Institucional:** Constituye el respaldo legal supremo que justifica el desarrollo del proyecto como una solución de democratización tecnológica. Al establecer que el control de los riesgos atmosféricos interiores es una responsabilidad vinculada a la prevención de la salud pública, eleva nuestra propuesta hacia un Sistema de Gestión Autónoma enfocado en reducir las brechas de vulnerabilidad en espacios cerrados públicos de alta ocupación.
