# Biodatascience
Proyecto para desarrollar una arquitectura que pueda:
  1. Recibir el input de la grabación del video.
  2. Recibir las señales del electromiograma.
  3. De alguna manera combinarlos para determinar si el ejercicio está realizándose correctamente.
## Primer approach:
Realizar 2 arquitecturas por separado. Una que reciba el input de la grabación y otra que se encargue de recibir el de la señal. Se combinarían linealmente ambos outputs para determinar la clasificación final (ejercicio realizado correcta o incorrectamente).

## Segundo approach:
Combinar los dos inputs en una sola arquitectura.  
