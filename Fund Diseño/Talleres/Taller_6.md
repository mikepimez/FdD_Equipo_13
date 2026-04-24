# Taller 6: Desk Research

## 1. Definición del Problema Técnico
¿Cómo diseñar e implementar un sistema de gestión atmosférica autónomo, de bajo costo y alta eficiencia, que purifique y renueve el aire en entornos saturados, garantizando niveles óptimos de CO2 y Material Particulado (PM10) según los estándares de la OMS y la Ley N° 29783, integrando una base de datos estadística para la prevención de riesgos?

---

## 2. Matriz de Desk Research

| N° | Fuente | Autor / Institución | Año | Referencia | Estado de tecnología encontrado | Exigencia o requisito identificado | Restricción o limitación | Función principal | Aplicación al proyecto |
|:--:|:---|:---|:---:|:---|:---|:---|:---|:---|:---|
| 1 | Informe OEFA N° 00180-2023 | OEFA | 2023 | [Informe Técnico OEFA 2023](https://repositorio.oefa.gob.pe/items/8f5525af-dd99-4b53-bb9c-635a1b3a9b2c) | Monitoreo de dispersión de PM10 hacia zonas pobladas. | Activación mecánica ante > 100 µg/m³ de PM10. | Necesidad de pre-filtrado físico para aire exterior. | Evaluar la dispersión de partículas contaminantes en el aire. | Define umbral de seguridad y justifica el uso de ductos. |
| 2 | Ventilation rates in schools | Bakó-Biró et al. | 2012 | [Artículo Científico (2012)](https://www.sciencedirect.com/science/article/pii/S0360132311002617) | Relación CO2 (5000 ppm) y reducción de memoria (15%). | Flujo mínimo de 8 L/s por persona (CO2 < 1000 ppm). | El sistema debe ser autónomo para evitar fatiga sensorial. | Optimizar el rendimiento cognitivo mediante la renovación de aire. | Establece la lógica de control y Set Point de CO2. |
| 3 | Confort Térmico UNMSM | Alexander & Poma | 2022 | [Tesis UNMSM (2022)](https://industrial.unmsm.edu.pe/investigacionfii/wp-content/uploads/2021/07/07.-TI-EPISST-TINEO-ZAMORA.pdf) | Evaluación de sensación térmica (Metodología Fanger). | Temperatura operativa máxima de 27°C (Costa peruana). | 76% de insatisfacción en ambientes sin ventilación activa. | Determinar el nivel de bienestar térmico en espacios cerrados. | Justifica el uso de sensor DHT11 para estrés térmico. |
| 4 | Ley N° 29783 | Congreso Perú | 2011 | [Plataforma El Peruano](https://diariooficial.elperuano.pe/Normas/obtenerDocumento?idNorma=38) | Marco legal de Seguridad y Salud en el Trabajo. | Garantizar ambientes libres de agentes físicos nocivos. | El dispositivo debe generar registros para auditorías. | Establecer normas de protección para la salud de los usuarios. | Define la función de base de datos y reporte estadístico. |
| 5 | Is CO2 an Indoor Pollutant? | Satish, U. et al. | 2012 | [Publicación EHP (2012)](https://pmc.ncbi.nlm.nih.gov/articles/PMC3548274/) | Impacto de CO2 en toma de decisiones (1000 ppm). | El sensor debe detectar variaciones de 400 ppm. | Renovación de aire en < 5 min tras detección de riesgo. | Analizar el efecto de gases de ocupación en la toma de decisiones. | Valida la elección de MQ-135 y procesamiento Arduino. |

---

## 3. Lista de Exigencias

| Tipo | Exigencia | Descripción |
|:---:|:---|:---|
| **D** | Automatización | El sistema debe actuar sin intervención humana (Autónomo). |
| **E** | Filtración | Debe contar con una etapa de purificación mecánica (Filtro). |
| **E** | Normativa | Cumplir con CO2 < 1000 ppm y PM10 < 100 µg/m³. |
| **D** | Bajo Costo | Materiales accesibles para instituciones públicas. |
| **E** | Portabilidad | Diseño compacto para instalación en ductos de aulas o buses. |

---

## 4. Estructura Funcional

### A. Caja Negra
* **Entradas:** Aire viciado (CO2/PM10), Energía (5V/Powerbank), Datos de sensores.
* **Procesamiento:** Sistema Eco-Vent 13 (Lógica de control + Filtración).
* **Salidas:** Aire renovado/purificado, Registro estadístico de calidad, Alerta visual.

### B. Funciones Principales
1.  **Captar contaminante:** Censar niveles de CO2 y PM10 en tiempo real.
2.  **Filtrar aire:** Retener partículas sólidas del flujo de entrada.
3.  **Renovar flujo:** Activar la extracción mecánica de aire viciado.
4.  **Registrar datos:** Almacenar estadísticas para prevención de riesgos.

---

## 5. Reformulación de la Oportunidad de Diseño
¿Cómo podríamos diseñar un sistema ambiental eficiente, sostenible y normativamente compatible (Ley N° 29783) que automatice la renovación y purificación del aire para proteger la capacidad cognitiva y la salud respiratoria en espacios de alta densidad?

---

## 6. Conclusión
Los hallazgos del Desk Research confirman que la ventilación natural en Lima es insuficiente frente a la carga de PM10 y CO2. La fase de concepción de la solución debe priorizar un sistema **"In-Out"** (Entrada filtrada / Salida forzada) que sea autónomo, eliminando la dependencia del factor humano para garantizar un ambiente seguro.
