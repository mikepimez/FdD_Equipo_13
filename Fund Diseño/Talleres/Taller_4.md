# Taller 4: Búsqueda del Patentes

## 1. Introducción
En esta sesión se realizó la vigilancia tecnológica para identificar soluciones existentes en el monitoreo y gestión de la calidad del aire interior. Nuestro objetivo es asegurar que nuestra propuesta aporte un valor agregado y no duplique tecnologías ya patentadas.

## 2. Registro de Patentes Encontradas
### Patente 1 ⎯ Monitoreo de Renovación de Aire
- **Título:** Sistemas, dispositivos y métodos para el monitoreo del aire interior.
- **N° de Publicación:** US2023107402A1
- **Fecha de Publicación:** 06/04/2023
- **Solicitante / Inventor:** GOOD ROBOT MONITORING INC [CA]
- **Resumen:** Sistema que utiliza sensores de CO2 y partículas para determinar la tasa de renovación del aire y el riesgo de infección por vía aérea basándose en la ocupación en tiempo real.
- **Enlace:** [Espacenet - US2023107402A1](https://worldwide.espacenet.com/publicationDetails/biblio?FT=D&CC=US&NR=2023107402A1)
<div align="center">
  <img src="../recursos/imagenes/Patente1.png" alt="Diagrama de la Patente 1" width="500px">
  <p><i>Figura 1:</i></p>
</div>

### Patente 2 ⎯ Detección por Redes Neuronales
- **Título:** Método, sistema y dispositivo inteligente para la detección e identificación de la calidad del aire en el hogar, basado en una red neuronal artificial mejorada.
- **N° de Publicación:** CN120336783A
- **Fecha de Publicación:** 18/07/2025
- **Solicitante / Inventor:** Instituto de Tecnología de Nanjing.
- **Resumen:** Dispositivo basado en la plataforma STM32 e IoT que utiliza algoritmos de redes neuronales (FNN) para clasificar y reconocer contaminantes, temperatura y presión en hogares inteligentes.
- **Enlace:** [Espacenet - CN120336783A](https://worldwide.espacenet.com/publicationDetails/biblio?FT=D&CC=CN&NR=120336783A)
<div align="center">
  <img src="../recursos/imagenes/Patente2.png" alt="Diagrama de la Patente 2" width="500px">
  <p><i>Figura 2</i></p>
</div>

### Patente 3 ⎯ Gestión de Aire con IA/ML
- **Título:** Un sistema y método para la gestión de la calidad del aire.
- **N° de Publicación:** WO2025141592A1
- **Fecha de Publicación:** 03/07/2025
- **Solicitante / Inventor:** HAMID YOUSUF HUSAINY [EN]
- **Resumen:** Sistema de gestión para edificios que utiliza IoT y módulos de Inteligencia Artificial/Machine Learning para predecir la calidad del aire y optimizar el consumo de energía en unidades de tratamiento de aire.
- **Enlace:** [Espacenet - WO2025141592A1](https://worldwide.espacenet.com/publicationDetails/biblio?FT=D&CC=WO&NR=2025141592A1)
<div align="center">
  <img src="../recursos/imagenes/Patente3.png" alt="Diagrama de la Patente 3" width="500px">
  <p><i>Figura 3</i></p>
</div>

## 3. Análisis de Innovación
Tras el análisis de las patentes US2023107402A1, CN120336783A y WO2025141592A1,hemos identificado los siguientes vacíos críticos y tecnológicos que nuestra propuesta planea cubrir

1. **Gestión Mixta**
   - Mientras las patentes internacionales se centran casi exclusivamente en el CO2 y la temperatura, nuestra propuesta reconoce que en el contexto peruano, el "aire pesado" incluye una carga significativa de **material particulado**. Nuestro sistema no solo busca mover aire viciado, sino gestionar flujos en entornos donde la ventilación pasiva es insuficiente para remover contaminantes densos.

2. **Acción Mecánica Directa de Bajo Consumo:**
   - Detectamos un vacío en la transición de la "lectura" a la "acción". Las soluciones existentes, como en las Patentes 1 y 2, suelen ser sistemas de monitoreo pasivo. Nuestro prototipo radica en la **acción inmediata** con el uso de actuadores de bajo consumo que ejecutan la ventilación de manera autónoma. Esto es vital en entornos donde el usuario sufre fatiga o saturación sensorial y no puede gestionar la ventilación de forma manual.

3. **Democratización Tecnológica y Sostenibilidad:**
   - A diferencia de la Patente 3, que requiere infraestructuras complejas de edificios inteligentes y módulos de IA/ML de alto costo, nuestro diseño bajo la metodología **VDI 2206** prioriza la accesibilidad. Al ser un sistema de bajo nivel, permite su implementación en nichos desatendidos como aulas de instituciones públicas, unidades de transporte, entornos laborales; garantizando el cumplimiento de las normas de seguridad y salud en los distintos ámbitos de aplicación.
