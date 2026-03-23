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
  Algoritmos: filtrado colaborativo (user-based o item-based), KNN, o modelos de deep learning tipo    embeddings.
  División de datos en training/validation/test para evitar overfitting.
- Predicción:
  El modelo genera un ranking de productos recomendados por usuario.
  Se actualiza dinámicamente según interacciones recientes.
- Uso:
  Recomendaciones mostradas en paneles de productos: “Recomendados para ti”, “Clientes como tú         también compraron…”.
  Sistema integrado con la API REST del backend que consulta el modelo IA en tiempo real.

## 4) Integración
- Backend:
  API REST en Node.js o Python (Flask/FastAPI)
  Microservicio de IA que recibe el ID de usuario y devuelve recomendaciones.
  
- Frontend:
  Interfaz en React/Angular
  Componentes para mostrar listas personalizadas de productos.
  Actualización dinámica usando fetch/axios para consumir la API.
  
- Flujo:
  Usuario → App Web → Backend → Modelo IA → Recomendaciones → Usuario

## 5) Valor
- Mejora:
  Experiencia de usuario personalizada.
  Incremento en la tasa de conversión (usuarios compran más productos).
  Reducción de abandono de carrito.
  
- Sin IA:
  Productos mostrados de forma genérica.
  Menor engagement y menos ventas.
  
- Rentabilidad:
  Aumento estimado de ventas de un 15–25% por recomendaciones precisas.
  Fidelización de clientes a largo plazo.

## 6) Diagrama
Usuario → App Web → Backend → Sistema IA → Recomendaciones → Usuario


