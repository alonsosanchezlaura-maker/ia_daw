# Práctica IA (RA4 · f)

## 1) Caso de uso
- Tipo de aplicación: Aplicación web de e-commerce con sistema de recomendaciones inteligentes.
- Problema: Los usuarios pierden tiempo buscando productos relevantes; la empresa pierde ventas potenciales y engagement.
- Usuario: Clientes de la tienda online, interesados en compras personalizadas basadas en su historial y preferencias.
- El uso de IA permite analizar comportamientos y preferencias de manera automática, ofreciendo recomendaciones precisas que aumentan la probabilidad de compra y mejoran la experiencia de usuario.

## 2) Datos
- Datos:
Logs de navegación: páginas visitadas, tiempo por producto, secuencia de clicks.
Historial de compras: productos adquiridos, frecuencia y valor de la compra.
Búsquedas realizadas: palabras clave ingresadas.
Valoraciones y comentarios de productos.
Información demográfica opcional: edad, ubicación, género (anonimizada).

Utilidad de los datos:
Permiten identificar patrones de comportamiento.
Facilitan el clustering de usuarios con gustos similares.
Sirven para entrenar modelos de predicción de productos que el usuario podría comprar.

- Tipo minería:
Clasificación: Predecir categorías de productos que le interesan a un usuario.
Clustering: Agrupar usuarios según comportamiento similar.
Filtrado colaborativo: Sistema de recomendación basado en comportamientos similares de otros usuarios.
Predicción: Estimar la probabilidad de que un usuario compre un producto específico.

## 3) Pipeline
- Recogida:
  Captura automática mediante eventos de la web: clics, páginas vistas, búsquedas, compras.
  Almacenamiento en bases de datos SQL/NoSQL y en logs de servidor.
  
- Limpieza:
  Eliminación de registros duplicados.
  Filtrado de datos incompletos (por ejemplo, clics sin usuario identificado).
  Normalización de formatos (fechas, categorías, puntuaciones).
  
- Transformación:
  Creación de matrices usuario-producto (ratings o interacciones).
  Codificación de variables categóricas (one-hot encoding).
  Escalado de datos numéricos para algoritmos de ML.
  
- Entrenamiento:
  Modelo de recomendación (ej. filtrado colaborativo o machine learning)
- Predicción:
  El sistema genera recomendaciones personalizadas
- Uso:
  Se muestran productos recomendados en la interfaz web



