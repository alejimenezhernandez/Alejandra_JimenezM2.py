Solicitar una Palabra
Este programa solicita al usuario que ingrese una palabra que debe tener entre 4 y 8 letras. El usuario tiene un máximo de 3 intentos para ingresar una palabra válida.

Función Principal: solicitar_una_palabra()

intentos: Contador de intentos, inicializado en 0.
palabra_valida: Se establece se verificara si la palabra ingresada es válida

El bucle se ejecuta mientras el número de intentos sea menor a 3 y no se haya ingresado una palabra válida.
Se solicita al usuario que ingrese una palabra que debe tener entre 4 y 8 letras.
Se calcula la longitud de la palabra ingresada.

Si la longitud de la palabra está entre 4 y 8 letras, se considera válida y se imprime un mensaje confirmando esto.
Si la longitud es menor a 4 letras, se imprime un mensaje indicando que faltan letras.
Si la longitud es mayor a 8 letras, se imprime un mensaje indicando que sobran letras.

Se incrementa el contador de intentos después de cada intento.

Si el usuario comete 3 errores, se imprime un mensaje indicando que el programa se cerrará.

La función solicitar_una_palabra() se llama al final del script para iniciar el proceso.




Este programa identifica en qué cuadrante del plano cartesiano se encuentran las coordenadas ingresadas por el usuario.

Función Principal: identificar_cuadrante(x, y)
Verifica si alguna de las coordenadas es igual a 0.
Si alguna coordenada es 0, retorna un mensaje indicando que las coordenadas no deben ser igual a 0.

Identificación del Cuadrante:
Si ( x > 0 ) y ( y > 0 ), retorna que los puntos están en el primer cuadrante.
Si ( x < 0 ) y ( y > 0 ), retorna que los puntos están en el segundo cuadrante.
Si ( x < 0 ) y ( y < 0 ), retorna que los puntos están en el tercer cuadrante.
Si ( x > 0 ) y ( y < 0 ), retorna que los puntos están en el cuarto cuadrante.

Entrada de Coordenadas:
Solicita al usuario que ingrese las coordenadas ( x ) y ( y ).

Llama a la función identificar_cuadrante(x, y) con las coordenadas ingresadas.

Imprime el resultado devuelto por la función, indicando en qué cuadrante se encuentran las coordenadas.

