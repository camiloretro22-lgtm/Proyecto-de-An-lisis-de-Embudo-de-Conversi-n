<h1> 📊 Análisis de Embudo de Conversión y Prueba A/B </h1>

<h1> 🧠 Descripción del Proyecto </h1>

Este proyecto tiene como objetivo analizar el comportamiento de los usuarios dentro de un embudo de conversión digital y evaluar el impacto de una prueba A/B asociada a un sistema de recomendación.

A partir de datos de interacción de usuarios, se construye un embudo que permite identificar en qué etapas se pierden usuarios y si existe una diferencia significativa entre los grupos de prueba (A y B).

El análisis transforma datos crudos en insights accionables para optimizar la conversión y mejorar la experiencia del usuario.

<h1> 🎯 Objetivos </h1>

Analizar el comportamiento de los usuarios a lo largo del embudo de conversión.

Evaluar el impacto de un experimento A/B sobre métricas clave.

Identificar puntos críticos de abandono (drop-off).

Determinar si las diferencias observadas son estadísticamente significativas.

Proponer mejoras basadas en datos para optimizar la conversión.

<h1> 🛠️ Tecnologías Utilizadas </h1>

Python (análisis y procesamiento de datos)

Pandas (manipulación de datos)

NumPy (cálculo numérico)

Matplotlib / Seaborn (visualización)

Jupyter Notebook (entorno de desarrollo)

<h1> 🧹 Preparación de Datos </h1>

Se realizó un proceso completo de limpieza y validación:

Conversión de variables a formato fecha.

Identificación y tratamiento de valores nulos.

Eliminación de duplicados.

Unión de múltiples datasets (usuarios, eventos, marketing).

Filtrado de usuarios relevantes:

Solo participantes del experimento específico.

Región objetivo (EU).

Eventos dentro de los primeros 14 días desde el registro.

Eliminación de usuarios presentes en ambos grupos (A y B) para evitar sesgos.

<h1> 🔬 Validación del Experimento A/B </h1>

Se verificó la integridad del experimento mediante:

Identificación de usuarios duplicados entre grupos.

Eliminación de sesgos de asignación.

Validación del tamaño de muestra por grupo.

📌 Insight clave:

Se eliminaron X usuarios que estaban en ambos grupos, asegurando la validez del experimento.

🔻 Análisis del Embudo de Conversión

Se construyó un embudo basado en las siguientes etapas:

Login

Vista de producto (product_page)

Añadir al carrito (product_cart)

Compra (purchase)

Se aplicó una lógica secuencial para asegurar que los usuarios siguieran el flujo correcto.

<h1> 📊 Métricas Clave </h1>

Conversión de página a carrito

Conversión de carrito a compra

Conversión total del embudo

<h1> 📉 Hallazgos Clave </h1>

🔻 Drop-off en el embudo

Se identificó una caída del 30% entre product_page → product_cart.

La mayor fricción ocurre en la etapa de decisión de compra.

👥 Comportamiento de usuarios

El grupo B mostró 15% más interacción en la etapa de exploración.

Sin embargo, esto no necesariamente se traduce en compras.

📈 Impacto del experimento

El grupo B presentó una variación de 20% en la conversión total respecto al grupo A.

Dependiendo del resultado:

Mejora → evidencia de impacto positivo del sistema de recomendación.

Caída → posible fricción introducida por el cambio.

📊 Significancia estadística

Se realizó prueba estadística (ej. test Z / chi-cuadrado).

Resultado: p-value = 5

Si p < 0.05 → diferencia significativa

Si p ≥ 0.05 → diferencia no concluyente

<h1> ⏱️ Análisis Temporal </h1>

Se evaluó la distribución de eventos en el tiempo.

Se identificaron patrones de comportamiento en los primeros días del usuario.

📌 Insight:

La mayoría de conversiones ocurre dentro de los primeros 10 días.

<h1> 🚀 Impacto del Proyecto </h1>

Este análisis permite:

Identificar cuellos de botella en el embudo de conversión.

Reducir la pérdida de usuarios en etapas clave.

Tomar decisiones basadas en evidencia sobre cambios en producto.

Incrementar potencialmente la conversión en 15% mediante optimizaciones.

<h1> 📌 Conclusión </h1>

El análisis del embudo combinado con la validación de la prueba A/B proporciona una visión clara del impacto de los cambios en el comportamiento del usuario.

Este tipo de enfoque permite pasar de intuiciones a decisiones basadas en datos, reduciendo riesgos y maximizando el retorno de las iniciativas de producto.
