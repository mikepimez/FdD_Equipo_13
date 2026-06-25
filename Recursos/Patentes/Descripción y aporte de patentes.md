# Patentes

## Descripción

En esta sección se detallan las patentes internacionales analizadas como la base de conocimiento técnico para el desarrollo de **Eco-Vent 13** bajo la metodología **VDI 2206**. El análisis cuantitativo de estos antecedentes mecánicos, electrónicos y de software convalidan el dimensionamiento de nuestro hardware y justifican el valor innovador de nuestro prototipo frente al estado de la técnica.

<p align="center">
  <a href="https://worldwide.espacenet.com/publicationDetails/biblio?FT=D&CC=US&NR=2023107402A1" target="_blank">
    <img src="https://img.shields.io/badge/Patente%201-US2023107402A1%20(Decaimiento)-blue?style=for-the-badge&logo=spacemacs&logoColor=white" style="margin-right: 5px; margin-bottom: 5px;">
  </a>
  <a href="https://worldwide.espacenet.com/publicationDetails/biblio?FT=D&CC=CN&NR=120336783A" target="_blank">
    <img src="https://img.shields.io/badge/Patente%202-CN120336783A%20(FNN)-green?style=for-the-badge&logo=spacemacs&logoColor=white" style="margin-right: 5px; margin-bottom: 5px;">
  </a>
  <a href="https://worldwide.espacenet.com/publicationDetails/biblio?FT=D&CC=WO&NR=2025141592A1" target="_blank">
    <img src="https://img.shields.io/badge/Patente%203-WO2025141592A1%20(SAHU)-orange?style=for-the-badge&logo=spacemacs&logoColor=white" style="margin-bottom: 5px;">
  </a>
</p>

---

# Patente 1

### Título
**US2023107402A1: Systems, devices, and methods for monitoring indoor air**
*Sistemas, dispositivos y métodos para el monitoreo del aire interior*

### Descripción
Patente internacional enfocada en la monitorización de espacios interiores mediante sensores de Dióxido de Carbono (CO₂) o partículas suspendidas conectados a un procesador y a una interfaz de comunicación. El sistema recibe datos continuos durante periodos extendidos (ocupados y desocupados), identifica regiones de interés con tasas constantes de decaimiento y calcula de forma automática la tasa de renovación de aire (ACH) y el riesgo de infección por aerosoles en tiempo real.

### Aporte directo al proyecto
* **Convalidación del Lazo de Control Lógico:** Valida de forma directa nuestro modelo de procesamiento matemático. La patente demuestra que analizar las curvas de decaimiento de gases cuando el ambiente se desocupa es el método metrológico idóneo para calcular la tasa de renovación de aire forzada, sirviendo como fundamento para el desarrollo de nuestros diagramas de flujo lógicos de control autónomo.

---

# Patente 2

### Título
**CN120336783A: 一种基于改进FNN的智能家居空气检测识别方法、系统、设备及存储介质**
*Método, sistema, dispositivo y medio de almacenamiento de detección e identificación de aire en el hogar inteligente basado en una red neuronal artificial (FNN) mejorada*

### Descripción
Patente orientada a la domótica que integra una plataforma de hardware empotrada basada en un microcontrolador STM32, un módulo de presión barométrica BMP280, un módulo de comunicación inalámbrica ESP8266 y una terna de sensores de gas (TGS2600, TGS2602, TGS2610 y TGS2620). El sistema realiza una extracción multicanal de 128 vectores de características (稳态特征 / 动态特征) y entrena una red neuronal prealimentada (FNN) optimizada con el algoritmo Adam y funciones de pérdida por entropía cruzada para clasificar contaminantes químicos con una precisión superior al 95%.

### Aporte directo al proyecto
* **Sustento de la Arquitectura de Hardware:** Valida la estructura electrónica integrada de Eco-Vent 13. Conconcluye que la recolección síncrona de variables termohigrométricas y químicas mediante sensores analógicos/digitales acoplados a un microcontrolador y un módulo Wi-Fi (ESP8266) es una arquitectura viable para identificar patrones de contaminación en tiempo real.
* **Criterio de Interfaz Local:** Respalda nuestro diseño de interfaz de usuario local al demostrar que el procesamiento directo en el hardware de bajo costo permite desplegar alertas inmediatas en una pantalla OLED local sin generar latencia ni depender de servidores externos en la etapa crítica de detección.

---

# Patente 3

### Título
**WO2025141592A1: A system and method for air quality management**
*Un sistema y método para la gestión de la calidad del aire*

### Descripción
Patente global que describe un sistema de purificación y acondicionamiento ambiental por demanda para edificaciones complejas. Implementa una red de arreglos de sensores de calidad de aire distribuidos en múltiples zonas (interiores y exteriores) conectados mediante IoT a un dispositivo de control central con un módulo de Inteligencia Artificial (AI/ML). El sistema procesa los datos mecánicos, térmicos y de contaminación para generar señales de comando que modulan de forma aislada las unidades de tratamiento de aire (Smart Air Handling Units - SAHU), optimizando el consumo energético del edificio ante episodios de contaminación aguda o variaciones del entorno.

### Aporte directo al proyecto
* **Justificación de la Actuación por Demanda:** Fundamenta la ventaja de ingeniería de Eco-Vent 13. Demuestra que para mitigar la recirculación de aire viciado es técnicamente necesario un sistema de actuación que module la inyección y extracción mecánica forzada de forma automatizada basándose en rangos preestablecidos, en lugar de mantener extractores fijos de alto consumo.
* **Diseño del Banco de Conmutación:** Respalda la inclusión electrónica de nuestro banco de relés independientes. La patente establece que cada zona o extractor axial requiere una gestión aislada de señales de potencia para equilibrar las presiones neumáticas y estabilizar las corrientes eléctricas del circuito, evitando paralelismos de corriente que afecten el microcontrolador central.
