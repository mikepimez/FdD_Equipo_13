# Tesis

## Descripción

En esta sección se detallan las tesis de repositorio nacionales e internacionales consultadas como antecedentes metodológicos, metrológicos y de ingeniería para el desarrollo del proyecto **Eco-Vent 13**. Estos trabajos proporcionan las líneas base sobre el comportamiento de variables higrotérmicas y de concentración de gases, convalidando de manera analítica el dimensionamiento del hardware, el diseño modular y la transición hacia una lógica de control activo automatizado.

---

# Tesis 1: Confort térmico a través de las estrategias de ventilación natural de espacios en instituciones educativas en San Antonio

* **Autor:** Huerta Ayn JD.

* **Año / Universidad:** 2021 | *Universidad César Vallejo (Tesis de licenciatura para optar el título profesional de Arquitecto).*

* **Descripción:**
  Investigación cualitativa y descriptiva con diseño fenomenológico que analizó las deficiencias de las estrategias pasivas y de ventilación natural en la infraestructura de las instituciones de enseñanza del distrito de San Antonio. El diagnóstico reveló que el 70% de los establecimientos a nivel nacional requieren de reestructuraciones profundas debido a la mala orientación del asoleamiento, la predominancia de pisos de cemento pulido que acumulan calor y la incapacidad del diseño arquitectónico tradicional para estabilizar la habitabilidad del aire por vías únicamente naturales.

* **Aporte directo al proyecto:**

  * **Justificación de Dispositivo Modular Autónomo:**
    Sustenta el dimensionamiento y la viabilidad de instalación de la carcasa vertical de nuestro prototipo (220 × 220 × 110 mm). Al demostrar que la infraestructura escolar local presenta deficiencias estructurales críticas que anulan la efectividad de la ventilación pasiva, se justifica el desarrollo de un dispositivo activo y autónomo de bajo costo que pueda fijarse directamente en paredes o techos sin requerir modificaciones arquitectónicas complejas ni sistemas HVAC centralizados de alto costo.

---

# Tesis 2: Evaluación del confort térmico en aulas y oficinas de la Facultad de Ingeniería Industrial de la Universidad Nacional Mayor de San Marcos

* **Autor:** Tineo Zamora A.

* **Año / Universidad:** 2021 | *Universidad Nacional Mayor de San Marcos (Trabajo de investigación para optar el grado académico de Bachiller en Ingeniería de Seguridad y Salud en el Trabajo).*

* **Descripción:**
  La investigación evaluó de manera objetiva el confort térmico en ambientes de alta ocupación universitaria durante la estación de verano utilizando el método de Fanger. El estudio determinó de forma cuantitativa que los espacios superan drásticamente el porcentaje estimado de insatisfechos (PPD) debido a que el calor radiante excede los 27 °C, considerado el valor máximo de tolerancia térmica y umbral de estrés térmico en la costa peruana según la escala de ASHRAE.

* **Aporte directo al proyecto:**

  * **Calibración de Umbrales Físicos:**
    Proporciona la justificación científica para el procesamiento lógico de las variables de temperatura en nuestro software. Al demostrar que los entornos universitarios locales sin climatización activa superan con facilidad los 27 °C en temporada cálida generando estrés térmico, valida técnicamente que el microcontrolador central de Eco-Vent deba evaluar de forma síncrona los datos de las variables higrotérmicas para activar la actuación mecánica forzada por demanda cuando se alcance este límite físico exacto.

---

# Tesis 3: Diseño e implementación de un prototipo basado en IoT de un sistema de control para la producción de orégano en invernadero, en el distrito La Yarada Los Palos 2024

* **Autor:** Portugal Cuno EA.

* **Año / Universidad:** 2025 | *Universidad Privada de Tacna (Tesis de pregrado para optar el título de Ingeniero Electrónico).*

* **Descripción:**
  Desarrollo de un prototipo automatizado para la monitorización de variables agrícolas (temperatura, humedad relativa, humedad del suelo, CO₂, pH y nivel de agua) en un entorno cerrado. El sistema emplea una red de comunicación local inalámbrica en estrella con módulos NRF24L01 conectados a nodos esclavos y un nodo central encargado del procesamiento de datos lógicos y su transmisión externa hacia la nube mediante tecnologías celulares.

* **Aporte directo al proyecto:**

  * **Validación de la Lógica Multivariable:**
    Esta investigación convalida de forma analítica e ingenieril el trinomio de monitorización y la especificación de restricciones de nuestro proyecto. Al demostrar que variables críticas como el CO₂ y las fluctuaciones térmicas interactúan dinámicamente influyendo en la calidad biológica del entorno cerrado, justifica que el firmware de un sistema mecatrónico deba leer y procesar de manera simultánea estos parámetros para tomar acciones de control automatizadas.

  * **Optimización de Mensajes y Tránsito de Datos:**
    El estudio provee un análisis matemático del balance y restricción de mensajes mensuales para la comunicación a servidores externos en la nube, demostrando cómo programar transmisiones intermitentes en intervalos discretos para optimizar el consumo de datos y evitar la saturación de los canales de comunicación serial.

---

# Tesis 4: Desarrollo de una cabina de control de variables ambientales para la fructificación y estado de maduración basado en procesamiento de imágenes de hongos macroscópicos comestibles aplicado al Hericium erinaceus

* **Autores:** Zegarra León LM & De La Flor Armas JA.

* **Año / Universidad:** 2025 | *Universidad Peruana de Ciencias Aplicadas (Trabajo de suficiencia profesional para optar el título de Ingeniero Mecatrónico).*

* **Descripción:**
  Diseño y construcción de una cabina automatizada equipada con módulos independientes de control ambiental (temperatura, humedad relativa y CO₂) bajo la lógica de un Arduino Mega 2560. Incorpora un sistema de visión artificial basado en una Raspberry Pi 4 y modelos neuronales YOLOv5 para identificar de forma automatizada las etapas fenológicas y de maduración del cultivo sin contacto físico.

* **Aporte directo al proyecto:**

  * **Justificación de la Unidad de Procesamiento Central:**
    Respalda directamente la viabilidad y robustez de utilizar el microcontrolador central como el cerebro del hardware. Debido a la gran cantidad de pines digitales y entradas analógicas requeridas por los sensores de gases y variables higrométricas, esta investigación demuestra que el procesamiento central proporciona la estabilidad de voltaje e inmunidad al ruido eléctrico necesarias para ejecutar la conmutación de actuadores de potencia sin comprometer la estabilidad del sistema.

  * **Discretización Algorítmica y Lógica de Control:**
    Detalla la implementación en código de controladores discretos y ecuaciones de histéresis asimétrica para la gestión de variables ambientales lentas o de alta inercia. Esto aporta el fundamento matemático para estructurar las rutinas de software, asegurando que las órdenes de encendido y apagado de los extractores mecánicos y ventiladores operen bajo márgenes rígidos de seguridad para prolongar la vida útil del hardware y proteger el circuito eléctrico.
