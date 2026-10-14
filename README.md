# examen-cpp
Examen de Tecnología

## Nombre completo: Ramsés Badilla Navarro

## Tabla de Errores

| Linea | Justificacion | Correccion |
| --- | --- | --- |
| 8 | Falta el punto y coma al final de la estructura esto genera un error de sintaxis en el compilador. | }; |
| 10 | El parámetro j se pasa por valor y debe pasarse por referencia (Jugador&) para que al modificarlo afecte al objeto original. | void sumarPuntos(Jugador& j, int extra) { |
| 22 | Se puso una cadena de caracteres ("A") a una variable de char, que causa un error de compilació. | char inicial = 'A'; |
| 25 | Se declaro a respaldo como referencia (Jugador&), haciendo que apunte a "a", deberia ser una copia para guardar los 90 puntos originales de Ana. | Jugador respaldo = a; |
| 29 | La condición "> 100" no se cumple cuando los puntos llegan a 100 causando mostrar el mensaje del puntaje máximo. | if (a.puntos >= 100) { |
