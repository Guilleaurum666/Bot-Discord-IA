# Bot-Discord-IA
1) INSTRUCCIONES
   1. Clonar el repositorio
   2. Descomprimir el modelo
   3. Configurar el token de Discord
   
2) DESCRIPCIÓN
   1. Carga el modelo
   2. Carga las etiquetas
   3. Redimensiona la imagen a 224x224 píxeles
   4. Ordena los valores de los píxeles
   5. Realiza una predicción
   6. Obtiene la clase con mayor probabilidad
   7.1. Si la confianza es menor al 80%, envía "respuesta no clara"
   7.2. Si supera el 80%, envía datos: probabilidad y categoría

