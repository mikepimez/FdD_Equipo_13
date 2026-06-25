# 🌍 Equipo 13 — Fundamentos de Diseño ✦  ⁺
### Carreras de Ingeniería Ambiental / Informática / Industrial  
**Universidad Peruana Cayetano Heredia**

---

## I. Identidad & Propósito  

### 🧭 Propuesta de Valor — Diseñar para la autonomía

En el contexto urbano actual, la calidad del aire no es una condición garantizada, sino una variable invisible que afecta directamente la salud, el rendimiento cognitivo y la calidad de vida de las personas. En ciudades como Lima Metropolitana, la exposición constante a Material Particulado (PM2.5 y PM10) y a elevadas concentraciones de CO₂ en espacios cerrados configura un escenario donde respirar aire limpio deja de ser un derecho efectivo y se convierte en una condición desigual.

Diversos estudios evidencian que, incluso cuando los valores diarios no superan los estándares nacionales, los promedios anuales de contaminantes sí exceden las recomendaciones internacionales, particularmente las establecidas por la Organización Mundial de la Salud. Esta exposición prolongada incrementa el riesgo de enfermedades respiratorias, deterioro cognitivo y reducción del bienestar general.

Frente a esta realidad, nuestro enfoque no se orienta a soluciones dependientes del usuario o del contexto privilegiado, sino a sistemas capaces de operar de manera autónoma, adaptándose a entornos donde la ventilación natural resulta insuficiente o ineficiente.

Diseñamos para reducir la dependencia del comportamiento humano como factor de control ambiental, trasladando la responsabilidad hacia sistemas inteligentes que garanticen condiciones mínimas de salubridad en espacios de alta densidad.

---

### 🎯 Misión del Equipo  

Como Equipo 13, asumimos el compromiso de desarrollar soluciones de ingeniería que integren tecnología, sostenibilidad y responsabilidad social, orientadas a la protección de la salud pública en entornos urbanos.

Nuestra misión es diseñar sistemas accesibles, funcionales y técnicamente sustentados que permitan mejorar la calidad del aire en espacios cerrados, priorizando la prevención de riesgos sobre la reacción tardía. Buscamos que nuestras propuestas no solo respondan a una necesidad técnica, sino que también sean viables en contextos reales donde los recursos son limitados y las condiciones ambientales adversas.

Entendemos la ingeniería no solo como una disciplina de resolución de problemas, sino como una herramienta para reducir brechas, fortalecer la equidad y contribuir a una mejor calidad de vida.

---

### ⚙️ Enfoque de Ingeniería

Nuestro enfoque se basa en la integración de tres principios fundamentales:

- **Monitoreo en tiempo real:**  
  Evaluación continua de variables críticas como concentración de CO₂, presencia de material particulado y condiciones térmicas, utilizando sensores accesibles y calibrables.

- **Procesamiento autónomo:**  
  Implementación de sistemas de control basados en microcontroladores que permitan la toma de decisiones sin intervención constante del usuario.

- **Actuación eficiente:**  
  Activación de mecanismos de ventilación y filtración que respondan dinámicamente a las condiciones del ambiente, garantizando la renovación del aire en tiempos óptimos.

Este enfoque permite transformar datos ambientales en acciones concretas, asegurando que el sistema no solo informe sobre la calidad del aire, sino que intervenga activamente para mejorarla.

---

### 🌱 Enfoque Social & Ambiental  

El proyecto se alinea con una visión de ingeniería centrada en las personas, donde la tecnología no se desarrolla como un fin en sí mismo, sino como un medio para enfrentar problemáticas reales que afectan a la población.

La calidad del aire en espacios interiores es un problema silencioso pero crítico, especialmente en contextos educativos, transporte público y viviendas urbanas densamente ocupadas. Abordarlo implica reconocer que la salud ambiental y la salud humana están profundamente interconectadas.

Por ello, nuestro trabajo busca generar una solución que no solo sea técnicamente viable, sino también socialmente relevante, promoviendo entornos más seguros, saludables y sostenibles.

---

## II. Diagnóstico Técnico & Contextual del Problema
### 2.1 Contexto Ambiental en Lima Metropolitana

La calidad del aire en Lima Metropolitana constituye un problema estructural persistente, caracterizado por la presencia sostenida de material particulado (PM10 y PM2.5) en concentraciones que exceden los límites recomendados por organismos internacionales.

El estudio de Valdivia (2016) evidencia que, si bien los promedios diarios de PM10 pueden mantenerse dentro de los Estándares Nacionales de Calidad Ambiental (ENCA), los promedios anuales de PM10 y PM2.5 superan de manera significativa tanto los estándares nacionales como las guías de la Organización Mundial de la Salud (OMS). Esto genera una falsa percepción de seguridad normativa, ocultando que es la exposición crónica la que representa el verdadero riesgo para la salud

Asimismo, investigaciones basadas en información satelital (Oropeza & Díez, 2022) indican que Lima presenta concentraciones promedio de PM2.5 cercanas a 28 µg/m³, posicionándola entre las ciudades con mayor contaminación en Latinoamérica. Este fenómeno se ve agravado por factores meteorológicos que influyen en la dispersión de contaminantes, como la velocidad del viento y la humedad relativa (Rojas et al., 2022).

Adicionalmente, informes del Organismo de Evaluación y Fiscalización Ambiental (OEFA) han demostrado que el material particulado puede desplazarse desde fuentes industriales hacia zonas urbanas, alcanzando concentraciones superiores a 100 µg/m³ en áreas pobladas, lo que evidencia la limitada capacidad de control del entorno frente a la contaminación atmosférica.

---

### 2.2 Limitaciones de la Ventilación Natural

En entornos educativos y laborales, la ventilación natural continúa siendo la estrategia predominante para la renovación del aire. Sin embargo, su efectividad depende de variables externas como condiciones climáticas, diseño arquitectónico y comportamiento del usuario.

Estudios en contextos similares al latinoamericano (Díaz et al., 2021) demuestran que en aulas con ventilación natural, las concentraciones de CO₂ superan frecuentemente los 1400 ppm, alcanzando picos de hasta 5000 ppm en condiciones de alta ocupación. Estos valores exceden ampliamente el umbral recomendado de 1000 ppm establecido por estándares internacionales como ASHRAE.

Por otro lado, investigaciones realizadas en instituciones educativas peruanas (Huerta, 2018) evidencian que un alto porcentaje de infraestructura presenta deficiencias en estrategias pasivas de ventilación, requiriendo intervenciones adicionales para alcanzar condiciones aceptables de confort térmico.

Asimismo, evaluaciones de confort térmico en aulas universitarias (Alexander & Rivera, 2022) muestran que más del 70% de los usuarios presentan insatisfacción en ambientes sin ventilación activa, con temperaturas que superan los 27°C, lo cual afecta directamente el bienestar de los ocupantes.

Estos resultados confirman que la ventilación natural, por sí sola, no garantiza condiciones adecuadas de calidad de aire ni de confort térmico en entornos de alta ocupación.

---

### 2.3 Impacto en la Salud & Rendimiento Cognitivo

La calidad del aire interior tiene un impacto directo en la salud y en el desempeño cognitivo de los usuarios. El estudio de Satish et al. (2012) demuestra que concentraciones de CO₂ de 1000 ppm generan deterioros significativos en la toma de decisiones, mientras que niveles de 2500 ppm producen reducciones severas en múltiples indicadores cognitivos.

De manera complementaria, investigaciones en entornos escolares (Bakó-Biró et al., 2012) evidencian que el aumento en las tasas de ventilación mejora significativamente la memoria, la velocidad de respuesta y la capacidad de atención de los estudiantes.

Asimismo, estudios como el de Coley et al. (2007) indican que altos niveles de CO₂ reducen la capacidad de concentración, afectando el rendimiento académico. En conjunto, esta evidencia posiciona la calidad del aire interior como un factor crítico tanto para la salud como para el desempeño humano.

---

### 2.4 Brecha entre Normativa & Realidad Operativa

El marco normativo peruano, representado por la Ley N° 29783, establece la obligación de garantizar ambientes seguros y saludables, incluyendo la protección frente a agentes físicos como contaminantes del aire. Sin embargo, en la práctica existe una brecha significativa entre la normativa y su cumplimiento. La dependencia de sistemas pasivos, la falta de automatización y la ausencia de monitoreo continuo limitan la capacidad de controlar efectivamente la calidad del aire en espacios cerrados.

Además, la carencia de registros sistemáticos dificulta la evaluación y prevención de riesgos a largo plazo, lo que reduce la efectividad de las estrategias actuales de control ambiental.

---

### 2.5 Definición del Problema de Ingeniería

A partir del análisis contextual, ambiental y científico, se identifica el siguiente problema central:

> Se identifica una brecha crítica en el control ambiental de espacios de alta ocupación en Lima evidencia una brecha crítica en los sistemas de control ambiental. Actualmente, la ventilación pasiva y la intervención manual constante resultan insuficientes para estabilizar los niveles de CO₂ y material particulado dentro de los rangos normativos, lo que exige una transición hacia mecanismos de control más efectivos y automatizados.

Esta problemática se ve intensificada por:

* Limitaciones económicas en infraestructura
* Falta de automatización en sistemas de ventilación
* Ausencia de soluciones accesibles adaptadas al contexto local.

---

### 2.6 Justificación de la Solución & Propuesta frente a Alternativas

A partir del diagnóstico realizado, se evaluaron distintas estrategias comúnmente utilizadas para el control de la calidad del aire en espacios cerrados:

- **Ventilación natural:**
  Dependiente de condiciones externas como, por ejemplo, viento, temperatura, apertura de ventanas, demostrando ser inconsistente e insuficiente en entornos urbanos densos.
  
- **Sistemas HVAC convencionales:**
  Requieren infraestructura compleja, alto costo de instalación y mantenimiento, lo que limita su implementación en instituciones públicas y entornos de bajos recursos.
  
- **Purificadores de aire comerciales:**
  Principalmente enfocados en filtración, pero sin garantizar renovación efectiva del aire ni control de CO₂.
  
- **Sistemas inteligentes basados en IA/IoT:**
  Tecnológicamente avanzados, pero económicamente inaccesibles y sobredimensionados para el contexto de aplicación del proyecto.

Frente a estas limitaciones, se justifica el desarrollo de un sistema basado en **ventilación mecánica autónoma de bajo costo**, capaz de ejecutar la renovación activa del aire, operar sin intervención del usuario, adaptarse a distintos entornos sin requerir infraestructura especializada y mantener coherencia con el contexto socioeconómico local.

---

### 2.7 Delimitación del Alcance del Prototipo

Considerando la complejidad del problema y las restricciones del contexto, el presente proyecto se enfoca en el desarrollo de un prototipo funcional base, orientado a validar la capacidad de renovación de aire de manera autónoma.

Componentes como:

* Almacenamiento de datos a largo plazo
* Interfaces digitales
* Optimización mediante algoritmos inteligentes

son reconocidos como líneas de desarrollo futuras, pero no forman parte del núcleo funcional requerido para la validación inicial del sistema.
Esta decisión responde a un criterio de ingeniería que prioriza la validación de la función crítica del sistema antes de su expansión.

---

## III. Alineación con los Objetivos de Desarrollo Sostenible (ODS)

El desarrollo del sistema **Eco-Vent** se fundamenta en los principios de la Agenda 2030 de la Organización de las Naciones Unidas. Integramos un enfoque de ingeniería orientado a la salud, la sostenibilidad y la equidad, estableciendo una relación directa entre nuestra solución técnica y las metas globales de desarrollo.

### 🏥 ODS 3 — Salud y Bienestar
> **Meta 3.9:** Reducir sustancialmente el número de muertes y enfermedades producidas por productos químicos peligrosos y la contaminación del aire, el agua y el suelo.

El proyecto contribuye directamente a esta meta mediante la mitigación de riesgos asociados a la exposición crónica a contaminantes críticos como el **Material Particulado (PM10)** y concentraciones elevadas de **CO₂**. Al automatizar la renovación del aire en espacios cerrados, Eco-Vent reduce la prevalencia de afecciones respiratorias y previene el deterioro cognitivo identificado en entornos de alta saturación.

### 🏙️ ODS 11 — Ciudades y Comunidades Sostenibles
> **Meta 11.6:** Reducir el impacto ambiental negativo per cápita de las ciudades, prestando especial atención a la calidad del aire y la gestión de los desechos.

Eco-Vent aborda la problemática de la habitabilidad en micro-entornos urbanos densamente poblados como, por ejemplo, aulas, transporte masivo y viviendas cerca de focos industriales, etcétera. Nuestra solución democratiza el acceso a aire seguro mediante un sistema de **bajo costo y fácil implementación**, fortaleciendo la resiliencia de la infraestructura urbana en contextos donde los sistemas HVAC convencionales son técnica o económicamente inviables.

### 🌿 ODS 13 — Acción por el Clima
> **Meta 13.3:** Mejorar la educación, la sensibilización y la capacidad humana e institucional respecto de la mitigación del cambio climático y la adaptación a él.

El sistema incorpora monitoreo ambiental en tiempo real, promoviendo indirectamente la conciencia sobre la calidad del aire y fomentando el uso de soluciones tecnológicas de bajo consumo energético para el control ambiental. Al utilizar ventilación mecánica controlada por demanda, optimizamos el uso de recursos y promovemos una respuesta eficiente frente a la variabilidad térmica y química del entorno, fomentando el uso de tecnologías sostenibles para el control ambiental.

---

## IV. Requerimientos e Ingeniería (Metodología VDI 2206)

En esta sección, el problema identificado se traduce en criterios concretos de diseño siguiendo la metodología VDI 2206. Se establecen las funciones del sistema, los requerimientos asociados y los parámetros medibles que permitirán validar su desempeño.

Este enfoque asegura que el desarrollo del sistema se base en lo que debe hacer antes de definir cómo se implementa.

---

### 4.1 Funciones del Sistema

El sistema Eco-Vent se define a partir de una función principal y un conjunto de funciones secundarias que estructuran su comportamiento.

**Función principal:**
- Mantener condiciones adecuadas de calidad del aire interior mediante ventilación mecánica controlada.

**Funciones secundarias:**
- Detectar variables ambientales (CO₂, temperatura y humedad).
- Evaluar la calidad del aire en tiempo real en función de umbrales definidos.
- Tomar decisiones de control de manera autónoma sin intervención del usuario.
- Ejecutar la renovación activa del aire mediante actuadores.
- Comunicar el estado del sistema a través de indicadores visuales.

Estas funciones definen el comportamiento esperado del sistema y constituyen la base para el establecimiento de requerimientos.

---

### 4.2 Lista de Exigencias del Sistema

A partir de las funciones definidas, se establecen los requerimientos que el sistema debe cumplir. Estos se clasifican en requerimientos de usuario, técnicos y restricciones.

#### Requerimientos de Usuario

- Operar de forma autónoma durante al menos 8 horas continuas sin intervención del usuario.
- Mantener condiciones de aire saludable en espacios cerrados (CO₂ < 1000 ppm).
- Proporcionar información clara e inmediata sobre la calidad del aire mediante indicadores visuales.
- Ser accesible económicamente para su implementación en entornos reales.

---

#### Requerimientos Técnicos

- Medir concentración de CO₂ en un rango mínimo de 400 a 5000 ppm.
- Medir temperatura y humedad relativa del entorno.
- Procesar datos en tiempo real con un tiempo de respuesta ≤ 5 minutos ante condiciones críticas.
- Activar automáticamente el sistema de ventilación al superar los umbrales establecidos.
- Mantener un consumo energético ≤ 15 W durante operación continua.
- Garantizar funcionamiento continuo durante periodos prolongados (≥ 8 horas).
- Integrar un sistema de señalización visual con tres estados (normal, moderado, tóxico).
- Permitir el registro básico de datos para evaluación del desempeño del sistema.

---

#### Restricciones del Sistema

- Costo total del prototipo ≤ 150 USD.
- Uso de componentes disponibles en el mercado local.
- Adaptabilidad a distintos tipos de espacios, por ejemplo, aulas u oficinas.
- Diseño compacto y de fácil instalación.
- Mantenimiento simple sin requerir personal altamente especializado.

---

### 4.3 Criterios Cuantitativos de Diseño

Para validar el desempeño del sistema, se establecen indicadores medibles que permiten verificar el cumplimiento de su función principal:

- Concentración de CO₂ objetivo: < 1000 ppm.
- Umbral de activación del sistema: ≥ 1000 ppm.
- Tiempo máximo de respuesta del sistema: ≤ 5 minutos.
- Autonomía mínima de operación: ≥ 8 horas continuas.
- Consumo energético máximo: ≤ 15 W.
- Capacidad de renovación de aire definida en función del volumen del espacio, sea la tasa de renovación de aire por hora, ACH.

Estos criterios permiten evaluar objetivamente el funcionamiento del sistema durante la fase de validación experimental.

---

### 4.4 Vigilancia Tecnológica y Análisis de Patentes

Como parte del proceso de diseño, se realizó una revisión de soluciones existentes para identificar tendencias tecnológicas y oportunidades de diferenciación. El análisis evidencia que las soluciones actuales presentan las siguientes características:

- Enfoque predominante en el monitoreo de variables como CO₂ y temperatura.
- Uso de tecnologías avanzadas basadas en inteligencia artificial e IoT.
- Integración en infraestructuras complejas de edificios inteligentes.

A partir de ello, se identifican los siguientes vacíos:

- **Limitado enfoque en material particulado (PM2.5 / PM10):**  
  Las soluciones priorizan gases, sin considerar contaminantes sólidos relevantes en el contexto local.

- **Predominio del monitoreo sobre la acción:**  
  Muchos sistemas informan, pero no intervienen directamente sobre el ambiente.

- **Alta complejidad y costo:**  
  Las soluciones existentes dificultan su implementación en entornos de bajos recursos.

---

### 4.5 Posicionamiento de la Solución

Frente a estas limitaciones, el sistema Eco-Vent se define por:

- Acción directa sobre el ambiente mediante ventilación mecánica controlada.
- Automatización sin dependencia de sistemas complejos de inteligencia artificial.
- Diseño accesible, adaptable y de bajo costo.
- Enfoque en contexto real, priorizando funcionalidad sobre complejidad tecnológica.

Este enfoque establece una propuesta coherente con el problema identificado y orientada a su implementación en escenarios reales.

---

## V. Propuesta de Solución — Sistema Eco-Vent

### 5.1 Concepto General del Sistema

El sistema **Eco-Vent** se define como un dispositivo de ventilación mecánica autónoma de bajo costo, diseñado para mejorar la calidad del aire en espacios cerrados mediante la integración de monitoreo ambiental, procesamiento de datos y actuación automática.

A diferencia de soluciones basadas únicamente en monitoreo, Eco-Vent incorpora un enfoque activo de control ambiental, en el cual el sistema no solo detecta condiciones desfavorables, sino que interviene directamente sobre el entorno mediante la renovación del aire.

El sistema está orientado a operar de manera continua y sin intervención del usuario, adaptándose dinámicamente a las condiciones del ambiente interior.

---

### 5.2 Arquitectura General del Sistema

Eco-Vent se estructura como un sistema mecatrónico compuesto por tres bloques funcionales principales:

#### 1. Módulo de Sensado

Encargado de la adquisición de variables ambientales relevantes para la evaluación de la calidad del aire. Incluye sensores para:

* Temperatura y humedad relativa
* Escalabilidad en concentración de CO₂ y material particulado

Este módulo transforma variables físicas del entorno en señales eléctricas que pueden ser procesadas por el sistema.

---

#### 2. Módulo de Procesamiento y Control

Implementado mediante un microcontrolador, este módulo constituye el núcleo de decisión del sistema. Sus funciones principales son:

* Recepción y procesamiento de datos ambientales
* Evaluación de condiciones en función de umbrales predefinidos
* Ejecución de lógica de control autónoma

El sistema compara continuamente las variables medidas con valores de referencia, permitiendo determinar el estado del ambiente en tiempo real.

---

#### 3. Módulo de Actuación

Encargado de ejecutar la respuesta del sistema frente a condiciones desfavorables. Incluye:

* Activación de ventiladores para la renovación del aire
* Generación de flujo de aire hacia el exterior o hacia zonas de intercambio

Este módulo convierte la decisión del sistema en una acción física sobre el entorno.

---

#### 4. Módulo de Interfaz

Permite la comunicación del estado del sistema hacia el usuario mediante:

* Indicadores visuales (LEDs)
* Señales de alerta según el nivel de calidad del aire

Su función es proporcionar información clara sin requerir interacción activa.

---

### 5.3 Lógica de Funcionamiento del Sistema

El funcionamiento de Eco-Vent se basa en un ciclo continuo de cuatro etapas:

1. **Adquisición de datos:**
   El sistema mide variables ambientales del entorno en tiempo real.

2. **Evaluación de condiciones:**
   Los datos son comparados con umbrales establecidos (por ejemplo, CO₂ ≥ 1000 ppm o condiciones térmicas desfavorables).

3. **Toma de decisión:**
   El sistema determina si es necesario activar la ventilación.

4. **Actuación:**
   Se activa el sistema de ventilación mecánica hasta restablecer condiciones aceptables.

Este ciclo se ejecuta de forma autónoma, garantizando una respuesta dinámica ante cambios en el ambiente.

---

### 5.4 Alcance del Prototipo de Validación

El prototipo desarrollado en esta etapa tiene como objetivo validar el principio de funcionamiento del sistema, más no su implementación completa. Por ahora, la validación se centra en:

* Adquisición de variables ambientales básicas (temperatura y humedad)
* Procesamiento de datos mediante microcontrolador
* Ejecución de lógica de control basada en umbrales
* Activación de un actuador (ventilador o señal visual)

Este enfoque permite demostrar la viabilidad del sistema en términos de:

* Sensado
* Procesamiento
* Decisión
* Actuación

Componentes como sensores de CO₂, medición de material particulado, almacenamiento de datos y optimización avanzada se consideran extensiones futuras del sistema.

---

### 5.5 Justificación de la Arquitectura Propuesta

La arquitectura de Eco-Vent responde directamente a las limitaciones identificadas en el análisis del problema:

* Reduce la dependencia del usuario mediante automatización
* Evita la complejidad de sistemas HVAC tradicionales
* Mantiene un costo accesible mediante el uso de microcontroladores
* Permite escalabilidad hacia sistemas más complejos

Este diseño equilibra funcionalidad, costo y viabilidad, asegurando coherencia con el contexto de aplicación del proyecto.

---

### 5.6 Proyección de Desarrollo (Roadmap)

El desarrollo del sistema se plantea en etapas progresivas:

**Fase 1 — Validación funcional (actual):**

* Implementación de prototipo básico
* Verificación de lógica de control
* Activación de actuadores simples

**Fase 2 — Integración de sensores avanzados:**

* Incorporación de sensores de CO₂
* Medición de material particulado (PM2.5 / PM10)

**Fase 3 — Optimización del sistema:**

* Mejora en eficiencia energética
* Ajuste dinámico de umbrales

**Fase 4 — Expansión del sistema:**

* Integración de registro de datos
* Conectividad y monitoreo remoto
* Interfaces digitales avanzadas

Este enfoque permite evolucionar desde un prototipo funcional hacia una solución completa y escalable.

# ✦  ⁺

## 📸 Fotografía del Equipo

<p align="center">
  <img src="Recursos/Imágenes/Fotos del Grupo/Equipo.png" width="700" alt="Fotografía del Equipo 13">
  <br>
  <em>Figura 1. Integrantes del equipo 13 en sesión de trabajo</em>
</p>

---

## 👥 Integrantes

| Foto | Apellidos y Nombres | Carrera | Correo |
| :--- | :--- | :--- | :--- |
| <img src="https://raw.githubusercontent.com/mikepimez/FdD_Equipo_13/main/Recursos/Im%C3%A1genes/Fotos del Grupo/Elmer Bravo.jpeg" alt="Elmer Bravo" width="200"> | **Bravo Tumbay**, Elmer David | Ing. Informática | elmer.bravo@upch.pe |
| <img src="https://raw.githubusercontent.com/mikepimez/FdD_Equipo_13/main/Recursos/Im%C3%A1genes/Fotos del Grupo/Isabel Padilla.jpg" alt="Isabel Padilla" width="200"> | **Padilla Romero**, Isabel Antonella | Ing. Informática | isabel.padilla@upch.pe |
| <img src="https://raw.githubusercontent.com/mikepimez/FdD_Equipo_13/main/Recursos/Im%C3%A1genes/Fotos del Grupo/Milagros Romero.jpeg" alt="Milagros Romero" width="200"> | **Romero Yllaconza**, Milagros Lucero | Ing. Industrial | milagros.romero@upch.pe |
| <img src="https://raw.githubusercontent.com/mikepimez/FdD_Equipo_13/main/Recursos/Im%C3%A1genes/Fotos del Grupo/Aldair Silvera.jpeg" alt="Aldair Silvera" width="200"> | **Silvera Huaman**, Aldair | Ing. Ambiental | aldair.silvera@upch.pe |
| <img src="https://raw.githubusercontent.com/mikepimez/FdD_Equipo_13/main/Recursos/Im%C3%A1genes/Fotos del Grupo/Minoru Tapia.jpeg" alt="Minoru Tapia" width="200"> | **Tapia Gómez**, Minoru Takeshi | Ing. Informática | minoru.tapia@upch.pe |

