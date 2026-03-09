# Práctica IA (RA4 · d+e) — Sectores con implantación relevante y lenguajes de programación en IA

## 1) Introducción
- Objetivo de la práctica:
Identificar los sectores productivos donde la IA tiene una implantación significativa y relacionarlos con los lenguajes de programación más utilizados en su desarrollo, evidenciando la conexión entre tecnología, aplicaciones reales y contexto profesional.

- Relación con DAW/DAM:
Permite comprender cómo integrar soluciones de IA en aplicaciones, servicios o productos digitales, relacionando desarrollo de software con análisis de datos y automatización de tareas.

## 2) Sectores con implantación relevante de IA

### Sector 1
- Nombre del sector:
Sanidad

- Tipo de empresa/servicio:
Hospitales, clínicas, laboratorios y servicios de diagnóstico médico.

- Aplicación de IA:
Análisis de imágenes médicas mediante modelos de visión por computador para detección temprana de enfermedades (radiografías, resonancias, tomografías).

- Qué tarea mejora o automatiza:
Automatiza la detección de anomalías y ayuda al diagnóstico, reduciendo errores humanos y agilizando el proceso.

- Por qué la IA tiene implantación relevante en este sector:
La gran cantidad de datos médicos, la necesidad de diagnósticos precisos y la presión por mejorar la eficiencia hacen que la IA sea indispensable.

- Beneficios que aporta:
Mejora la precisión diagnóstica, reduce tiempos de espera, optimiza recursos médicos y permite medicina personalizada.

### Sector 2
- Nombre del sector:
Banca

- Tipo de empresa/servicio:
Bancos, fintechs, aseguradoras y servicios financieros.

- Aplicación de IA:
Detección de fraude en transacciones y scoring de riesgo crediticio mediante modelos predictivos.

- Qué tarea mejora o automatiza:
Identifica patrones sospechosos en transacciones y evalúa la solvencia de clientes automáticamente.

- Por qué la IA tiene implantación relevante en este sector:
La banca genera enormes volúmenes de datos transaccionales que requieren análisis rápido y preciso.

- Beneficios que aporta:
Reduce fraudes, mejora la toma de decisiones crediticias, optimiza procesos y protege a clientes y entidades.

### Sector 3
- Nombre del sector:
Comercio electrónico

- Tipo de empresa/servicio:
Plataformas de venta online, marketplaces y tiendas digitales.

- Aplicación de IA:
Sistemas de recomendación de productos personalizados.

- Qué tarea mejora o automatiza:
Analiza el comportamiento de los usuarios para ofrecer productos relevantes, aumentando ventas y fidelización.

- Por qué la IA tiene implantación relevante en este sector:
La competencia digital obliga a personalizar la experiencia de compra y optimizar conversiones.

- Beneficios que aporta:
Incrementa ingresos, mejora la experiencia de usuario y permite campañas de marketing más efectivas.

## 3) Lenguajes de programación en IA

### Lenguaje 1
- Nombre:
Python

- Uso principal en IA:
Desarrollo de modelos de machine learning y deep learning, análisis de datos y automatización.

- Ventajas:
Amplio ecosistema de librerías (TensorFlow, PyTorch, scikit-learn), sintaxis sencilla, comunidad extensa y soporte multiplataforma.

- Ejemplos de uso:
Modelos de recomendación en comercio electrónico, análisis de imágenes médicas, detección de fraude bancario.

### Lenguaje 2
- Nombre:
Java

- Uso principal en IA:
Desarrollo de aplicaciones robustas de IA, integración en sistemas empresariales y aplicaciones móviles.

- Ventajas:
Portabilidad, estabilidad y facilidad para integrarse con sistemas existentes en grandes empresas.

- Ejemplos de uso:
Sistemas de scoring crediticio en banca, motores de recomendación integrados en plataformas Java, chatbots.

### Lenguaje 3
- Nombre:
R
- Uso principal en IA:
Análisis estadístico avanzado, minería de datos y visualización.

- Ventajas:
Potente para análisis estadístico y exploración de datos, gran cantidad de paquetes especializados (caret, randomForest).

- Ejemplos de uso:
Modelos predictivos en banca, análisis de tendencias de consumo, estudios epidemiológicos en sanidad.

### Lenguaje 4
- Nombre:
C++

- Uso principal en IA:
Optimización de rendimiento en aplicaciones de IA que requieren alta velocidad, como visión por computador y simulaciones.

- Ventajas:
Alto rendimiento y control sobre memoria y recursos, adecuado para algoritmos complejos en tiempo real.

- Ejemplos de uso:
Procesamiento de imágenes médicas, simulaciones de logística o transporte, IA en videojuegos.


## 4) Relación entre sectores, tipo de IA y lenguaje
| Sector | Aplicación de IA | Tipo de IA/técnica | Lenguaje recomendado | Justificación |
|--------|------------------|--------------------|----------------------|---------------|
|Sanidad |Análisis de imágenes médicas|Deep Learning / Visión por computador|Python|Amplio soporte de librerías de visión y deep learning, rápido prototipado y fácil integración con sistemas clínicos
|Banca|Detección de fraude y scoring|Machine Learning / Modelos predictivos|R / Python|R para análisis estadístico, Python para modelos escalables y despliegue en producción|
|Comercio electrónico|Recomendadores de productos|Machine Learning / Sistemas de recomendación|Python / Java|Python para prototipado y algoritmos, Java para integración en plataformas web y apps|

## 5) Diagrama (ASCII o Mermaid)
graph LR
A[Sanidad] --> B[Análisis de imágenes médicas]
B --> C[Python]
D[Banca] --> E[Detección de fraude]
E --> F[R / Python]
G[Comercio electrónico] --> H[Recomendadores de productos]
H --> I[Python / Java]

## 6) Riesgos y mitigación
- Riesgo 1:
Dependencia tecnológica de proveedores de IA y librerías externas.
- Mitigación 1:
Revisiones periódicas de código, uso de librerías open source y formación interna.

- Riesgo 2:
Sesgos en los datos que generan decisiones injustas o ineficaces.
- Mitigación 2:
Validación del modelo con datos diversos, auditorías periódicas y pruebas antes de desplegar.

## 7) Conclusión
- Qué sectores destacan más:
Sanidad, banca y comercio electrónico por la alta generación de datos y necesidad de decisiones automatizadas.

- Qué lenguajes aparecen con más frecuencia:
Python y R por su flexibilidad, ecosistema y facilidad de integración.

- Qué importancia tiene esto para DAW/DAM:
Permite desarrollar soluciones inteligentes, optimizar procesos y ofrecer servicios digitales más eficientes y personalizados.

## 8) Fuentes oficiales (mín. 2)
- Fuente 1 (sectores / aplicación IA):
[OECD AI in Society 2022](https://chatgpt.com/c/69aea835-69b8-8327-bee9-06738f53dc26#:~:text=OECD%20AI%20in%20Society%202022)

- Fuente 2 (lenguajes / ecosistema técnico):
Python AI Ecosystem – Python.org
[https://www.python.org/](https://www.python.org/)
