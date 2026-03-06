# Proyecto-final-ConnectaTel-Sprint7
Proyecto de análisis de datos de ConnectaTel para comprender el uso de servicios móviles (llamadas y mensajes) en clientes de México y Colombia. Busca identificar patrones de consumo, detectar comportamientos atípicos y reconocer segmentos de usuarios, con el fin de optimizar la oferta comercial y mejorar la experiencia del cliente.

**Objetivo del Proyecto**:Explorar, limpiar y analizar estas bases de datos para construir una visión clara, confiable y accionable sobre el comportamiento de uso de los clientes y cómo varía entre diferentes grupos de usuarios.

**Datasets Utilizados:**
- plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).


**Etapas del Análisis**

1. Carga y exploración de datos
- Carga y exploración de los 3 datasets: plans, users_latam, usage
- Visión clara de la estructura y tipos de columnas
  
2. Identificación de problemas de calidad
- Conteo de valores nulos, detección de sentinels, revisión de fechas fuera de rango
- Identificación de problemas que podrían sesgar las decisiones del negocio
  
3. Limpieza básica
- Reemplazo sentinels, conversión de fechas, imputación o NA según reglas
- Preparación de datos consistentes para análisis estadístico
  
4. Summary statistics
- Revisión de medidas clave en variables categóricas y numéricas
- Obtención de medidas como media, mediana, percentiles
  
5. Visualización & outliers
- Creación de histogramas y boxplots
- Visualización de sesgos, patrones de usuarios y datos atípicos
  
6. Segmentación
- Segmentaciones basadas en reglas claras (como la función de edad y tipo de uso)
- Visualización de proporciones con countplots
  
7. Reporte ejecutivo
- Redacción de conclusiones 
- Redacción de recomendaciones comerciales concretas y estratégicas basadas en los hallazgos obtenidos.
  

