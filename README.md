# EXAMEN DE KOTLIN

## Objetivo
En estos ejercicios se identifican errores en fragmentos de código Kotlin, se plantea la solución esperada y se indica el resultado que debe obtenerse.  
Las imágenes del problema y de la solución serán colocadas aparte.

Trabajado en: [https://play.kotlinlang.org/](https://play.kotlinlang.org/)

---

# Problema 1

## Imagen: problema
![Problema 1 - Problema]
<img width="259" height="147" alt="Captura de pantalla 2026-03-27 a las 20 25 37" src="https://github.com/user-attachments/assets/494e93c5-56db-42be-a482-8959af4d5bf2" />

## Explicación
Aquí se intenta cambiar el valor de una variable que fue declarada como inmutable.

## Solución esperada
La variable debe declararse de forma que sí permita cambiar su valor.

## Imagen: solución esperada
![Problema 1 - Solución esperada]

<img width="282" height="183" alt="Captura de pantalla 2026-03-27 a las 20 26 04" src="https://github.com/user-attachments/assets/71d0091f-9a25-4bd1-ba90-019454614a31" />

## Resultado esperado
Debe mostrar el valor **25**.

---

# Problema 2

## Imagen: problema
![Problema 2 - Problema]


## Explicación
En la condición se está usando el signo de asignación en lugar del signo de comparación.

## Solución esperada
La condición debe corregirse usando el operador de comparación correcto.

## Imagen: solución esperada
![Problema 2 - Solución esperada]


## Resultado esperado
Debe mostrar el mensaje **"Correcto"**.

---

# Problema 3

## Imagen: problema
![Problema 3 - Problema]



## Explicación
La variable fue declarada, pero se intenta usar sin haberle dado un valor antes.

## Solución esperada
Primero debe asignarse un valor a la variable y luego imprimirla.

## Imagen: solución esperada
![Problema 3 - Solución esperada]



## Resultado esperado
Debe mostrar el texto asignado a la variable, por ejemplo: **"César"**.

---

# Problema 4

## Imagen: problema
![Problema 4 - Problema]




## Explicación
La estructura `when` fue usada de forma incorrecta para evaluar una condición.

## Solución esperada
Debe corregirse la estructura para que evalúe correctamente la condición de la nota.

## Imagen: solución esperada
![Problema 4 - Solución esperada]



## Resultado esperado
Como la nota es 15, debe mostrar **"Aprobado"**.

---

# Problema 5

## Imagen: problema
![Problema 5 - Problema]



## Explicación
El ciclo `for` está escrito con una sintaxis que no corresponde a Kotlin.

## Solución esperada
Debe reescribirse el ciclo usando la sintaxis correcta de Kotlin para recorrer números.

## Imagen: solución esperada
![Problema 5 - Solución esperada]



## Resultado esperado
Debe mostrar:

```text
1
2
3
4
5
```

---

# Problema 6

## Imagen: problema
![Problema 6 - Problema](ruta-de-tu-imagen-11)

## Explicación
El código puede funcionar, pero está mejor escrito si la estructura condicional queda más clara y ordenada.

## Solución esperada
Se debe organizar correctamente el `if` y el `else` para que el código quede más limpio.

## Imagen: solución esperada
![Problema 6 - Solución esperada](ruta-de-tu-imagen-12)

## Resultado esperado
Como el número es 5, debe mostrar **"Menor"**.

---

# Problema 7

## Imagen: problema
![Problema 7 - Problema](ruta-de-tu-imagen-13)

## Explicación
Se vuelve a usar `when` de forma incorrecta para comparar condiciones.

## Solución esperada
Debe corregirse la estructura para evaluar correctamente cada caso según la nota.

## Imagen: solución esperada
![Problema 7 - Solución esperada](ruta-de-tu-imagen-14)

## Resultado esperado
Como la nota es 18, debe mostrar **"Excelente"**.

---

# Problema 8

## Imagen: problema
![Problema 8 - Problema](ruta-de-tu-imagen-15)

## Explicación
La función indica que devolverá un tipo de dato, pero en realidad retorna otro diferente.

## Solución esperada
Debe corregirse para que el valor retornado sea del mismo tipo que se declaró en la función.

## Imagen: solución esperada
![Problema 8 - Solución esperada](ruta-de-tu-imagen-16)

## Resultado esperado
La función debe devolver un texto.  
Si luego se imprime ese valor, por ejemplo, podría mostrarse **"Hola"**.

---

# Problema 9

## Imagen: problema
![Problema 9 - Problema](ruta-de-tu-imagen-17)

## Explicación
La función necesita recibir un dato, pero fue llamada sin enviarlo.

## Solución esperada
Debe llamarse la función enviándole el argumento que necesita.

## Imagen: solución esperada
![Problema 9 - Solución esperada](ruta-de-tu-imagen-18)

## Resultado esperado
Debe mostrar el texto enviado a la función, por ejemplo: **"César"**.

---

# Problema 10

## Imagen: problema
![Problema 10 - Problema](ruta-de-tu-imagen-19)

## Explicación
La misma variable fue declarada dos veces en el mismo bloque.

## Solución esperada
La variable no debe volver a declararse; solo debe cambiarse su valor.

## Imagen: solución esperada
![Problema 10 - Solución esperada](ruta-de-tu-imagen-20)

## Resultado esperado
Debe mostrar el valor final de la variable, es decir: **20**.

---

# Conclusión

Estos ejercicios permiten reconocer errores básicos en Kotlin, como el uso incorrecto de variables, comparaciones, estructuras condicionales, ciclos y funciones.

Al corregirlos, se comprende mejor cómo escribir código de forma correcta y ordenada en este lenguaje.
