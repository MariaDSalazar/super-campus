# Súper Campus

Juego de plataformas para practicar dependencias funcionales con casos de una universidad.

El jugador recorre el campus de corrido, como en un juego de plataformas clásico: salta, junta créditos, aplasta bichos y, en cada reto, golpea con la cabeza los bloques que lo resuelven. La meta de cada reto queda cerrada hasta resolverlo: si el bloque no es el correcto, el juego explica por qué esa elección no sirve, sin mostrar la respuesta, y el jugador golpea otro sin que la partida se detenga.

## Contenido

- 6 niveles y 22 retos sobre una tabla de matrículas (estudiantes, materias y profesores), con un jefe final.
- Temas: semántica de los atributos, redundancia, anomalías, valores NULL, tuplas espurias, cómo se comprueba X → Y y tipos de dependencia funcional.
- Al terminar aparece un informe de entendimiento por tema, calculado con el primer intento de cada reto, con lo que conviene repasar. Se puede copiar o imprimir.

## Características

- Todo el contenido de los retos va cifrado y en cadena: cada reto se abre solo después de resolver bien el anterior.
- Funciona en el navegador del celular o del computador, sin cuentas ni instalación.
- El avance se guarda en el mismo navegador.

## Ejecutar en local

Es un sitio estático. Desde la carpeta del repositorio:

```
python -m http.server 8000
```

y abrir `http://localhost:8000`.
