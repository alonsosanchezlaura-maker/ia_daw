# Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

## 1) Caso y objetivo de negocio
- Empresa/sector (real o ficticia):
Netflix (plataforma de streaming digital)

- Problema a resolver:
Recomendar contenido relevante a cada usuario para aumentar el tiempo de visualización y reducir la cancelación de suscripciones.

- Objetivo de negocio (rentabilidad):
Aumentar retención de usuarios y visualizaciones para mejorar ingresos por suscripción.

## 2) Big Data: recogida masiva de datos
Describe por qué es Big Data (volumen, velocidad, variedad).
Netflix utiliza Big Data porque maneja enormes cantidades de datos generados continuamente por millones de usuarios.
- Fuente 1:
Historial de visualización de usuarios (series y películas vistas).
- Fuente 2:
Interacciones de usuario (búsquedas, clics, valoraciones, pausas, abandonos).
- Fuente 3:
Metadatos del contenido (género, actores, duración, idioma, año).

- Volumen/velocidad (estimación):
Volumen: millones de usuarios generan datos cada segundo.
Velocidad: los datos se producen continuamente mientras los usuarios usan la plataforma.
Variedad: incluye datos de comportamiento, texto, metadatos de contenido y eventos de uso.
Volumen/velocidad (estimación): millones de eventos de usuario diarios.

- Formatos (texto, eventos, series temporales, imágenes, etc.):
eventos de usuario
registros de actividad
texto y metadatos
series temporales de uso

## 3) Tratamiento/análisis: pipeline de datos
Explica el flujo de forma ordenada:

- Ingesta (captura/eventos):
Los datos se recopilan automáticamente cuando el usuario interactúa con la plataforma (clics, visualizaciones, búsquedas).

- Limpieza/normalización:
Se eliminan datos duplicados o incompletos y se normalizan los formatos para que puedan ser analizados correctamente.

- Almacenamiento (data lake/warehouse):
Los datos se almacenan en grandes repositorios de datos (data lakes o data warehouses).
- Preparación de variables (features):
Se crean variables como:
géneros preferidos
tiempo medio de visualización
frecuencia de uso
contenido abandonado

- Análisis/BI (opcional):
Los analistas utilizan herramientas de análisis para detectar patrones de comportamiento de usuarios.

## 4) IA aplicada: modelo y decisión
- Tipo de IA/técnica (clasificación, predicción, recomendación, anomalías, NLP...):
Sistemas de recomendación basados en machine learning (recomendación y predicción).

- Entrada del modelo (qué datos usa):
historial de visualización
preferencias del usuario
comportamiento de usuarios similares
características del contenido

- Salida del modelo (qué produce):
Lista personalizada de contenidos recomendados.

- Decisión que habilita (qué hace la empresa con esa salida):
Mostrar recomendaciones personalizadas en la página principal del usuario.

Esto aumenta la probabilidad de que el usuario continúe viendo contenido.

## 5) Rentabilidad: KPIs antes/después (mínimo 3)
KPI 1 (ingresos/coste/eficiencia):
- Antes: 80% de usuarios mantienen la suscripción
- Después: 90% de usuarios mantienen la suscripción
- Por qué mejora la rentabilidad: Menos cancelaciones significa ingresos más estables.

KPI 2:
- Antes: 1.5 horas diarias por usuario
- Después: 2.2 horas diarias por usuario
- Por qué mejora la rentabilidad: Mayor uso de la plataforma aumenta el valor percibido del servicio.

KPI 3:
- Antes: 40% de los usuarios encontraban contenido nuevo fácilmente
- Después: 70% de los usuarios descubren contenido recomendado
- Por qué mejora la rentabilidad: Mejora la satisfacción del usuario y reduce la probabilidad de cancelar.

## 6) Diagrama del pipeline (ASCII o Mermaid)
(Pega aquí el diagrama)

## 7) Riesgos y mitigación
Riesgo 1:
- Mitigación 1:

Riesgo 2:
- Mitigación 2:

## 8) Valoración (criterio c): importancia presente y futura de la IA (10–15 líneas)
- Importancia actual (hoy):
- Importancia futura (3–5 años):
- Condiciones/limitaciones (datos, costes, regulación, ética, seguridad, empleo):
- Conclusión razonada:

## 9) Fuentes oficiales (mín. 2)
- Big Data/analítica (enlace oficial):
- IA/técnica/modelo (enlace oficial):
