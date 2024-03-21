## Observaciones:
- Distintos tamaños de YOLO. En general mientras más grande mejor serán los resultados. Ahora mismo he entrenado uno small.
- En el entreno que he hecho solo use los datos de China_MotorBike.
- En el entreno que he hecho cometí el error de eliminar todos los background. Esto hace que mi modelo nunca aprenda a detectar backgrounds.
- Estoy entrenando en Google Colab y me descargo los pesos para predecir en local.
- Por ahora, no he podido implementar los repos de los participantes de la competición.

## Próximos pasos:
- Entrenar un primer modelo que usa todos los datos con un batch size y epochs adecuados.
- Analizar resultados, comprobar como evaluar en test usando web de la competición y comparar con otros participantes.
- Implementar los repos de los participantes de la competición. Alternativamente, ver que ensemble han usado e intentar replicarlos.