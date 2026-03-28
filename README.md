# EXAMEN DE KOTLIN

## Objetivo
En estos ejercicios se identifican errores en fragmentos de código Kotlin, se plantea la solución esperada y se indica el resultado que debe obtenerse.  
Las imágenes del problema y de la solución serán colocadas aparte.

Trabajado en: [https://play.kotlinlang.org/](https://play.kotlinlang.org/)

---

# Problema 1

## Imagen: problema
![Problema 1 - Problema]
<img width="460" height="568" alt="Captura de pantalla 2026-03-27 a las 20 40 46" src="https://github.com/user-attachments/assets/6366e569-3259-4718-8b0f-6c7868190d55" />


## Explicación
Aquí se intenta cambiar el valor de una variable que fue declarada como inmutable.

## Solución esperada
La variable debe declararse de forma que sí permita cambiar su valor.

## Imagen: solución esperada
![Problema 1 - Solución esperada]
<img width="834" height="605" alt="Captura de pantalla 2026-03-27 a las 20 41 18" src="https://github.com/user-attachments/assets/dce1ca66-a96e-4195-849a-5eeabf0c6c44" />


## Resultado esperado
Debe mostrar el valor **25**.

---

# Problema 2

## Imagen: problema
![Problema 2 - Problema]

<img width="761" height="561" alt="Captura de pantalla 2026-03-27 a las 20 26 58" src="https://github.com/user-attachments/assets/2264ab5c-d56f-4bc6-877d-8334af86900b" />

## Explicación
En la condición se está usando el signo de asignación en lugar del signo de comparación.

## Solución esperada
La condición debe corregirse usando el operador de comparación correcto.

## Imagen: solución esperada
![Problema 2 - Solución esperada]
<img width="464" height="595" alt="Captura de pantalla 2026-03-27 a las 20 27 58" src="https://github.com/user-attachments/assets/5acdce34-3aab-40a7-a9d3-305462393b2e" />


## Resultado esperado
Debe mostrar el mensaje **"Correcto"**.

---

# Problema 3

## Imagen: problema
![Problema 3 - Problema]
<img width="557" height="558" alt="Captura de pantalla 2026-03-27 a las 20 29 21" src="https://github.com/user-attachments/assets/2508c9f6-6639-4c85-89f2-f960894a593e" />


## Explicación
La variable fue declarada, pero se intenta usar sin haberle dado un valor antes.

## Solución esperada
Primero debe asignarse un valor a la variable y luego imprimirla.

## Imagen: solución esperada
![Problema 3 - Solución esperada]
<img width="450" height="570" alt="Captura de pantalla 2026-03-27 a las 20 28 39" src="https://github.com/user-attachments/assets/c471b77b-a2d7-4199-b588-7851992660a1" />


## Resultado esperado
Debe mostrar el texto asignado a la variable, por ejemplo: **"César"**.

---

# Problema 4

## Imagen: problema
![Problema 4 - Problema]
<img width="474" height="535" alt="Captura de pantalla 2026-03-27 a las 20 29 49" src="https://github.com/user-attachments/assets/80e5192a-c0dc-4e07-931d-fbe9cdc6486c" />



## Explicación
La estructura `when` fue usada de forma incorrecta para evaluar una condición.

## Solución esperada
Debe corregirse la estructura para que evalúe correctamente la condición de la nota.

## Imagen: solución esperada
![Problema 4 - Solución esperada]

<img width="593" height="570" alt="Captura de pantalla 2026-03-27 a las 20 30 22" src="https://github.com/user-attachments/assets/c1337d73-fcc9-46ac-a117-3825da76d397" />


## Resultado esperado
Como la nota es 15, debe mostrar **"Aprobado"**.

---

# Problema 5

## Imagen: problema
![Problema 5 - Problema]

<img width="1323" height="714" alt="Captura de pantalla 2026-03-27 a las 20 31 20" src="https://github.com/user-attachments/assets/1db4682d-028c-49d9-a078-a1ae43d9cc97" />


## Explicación
El ciclo `for` está escrito con una sintaxis que no corresponde a Kotlin.

## Solución esperada
Debe reescribirse el ciclo usando la sintaxis correcta de Kotlin para recorrer números.

## Imagen: solución esperada
![Problema 5 - Solución esperada]
<img width="457" height="669" alt="Captura de pantalla 2026-03-27 a las 20 31 51" src="https://github.com/user-attachments/assets/e9a0085e-5884-42ca-aa71-7a2128a13f8d" />


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
![Problema 6 - Problema]

<img width="268" height="563" alt="Captura de pantalla 2026-03-27 a las 20 33 05" src="https://github.com/user-attachments/assets/ab42d2eb-de96-4b7b-8a95-44fb919a6c31" />


## Explicación
El código puede funcionar, pero está mejor escrito si la estructura condicional queda más clara y ordenada.

## Solución esperada
Se debe organizar correctamente el `if` y el `else` para que el código quede más limpio.

## Imagen: solución esperada
![Problema 6 - Solución esperada]


<img width="386" height="545" alt="Captura de pantalla 2026-03-27 a las 20 33 47" src="https://github.com/user-attachments/assets/ca1a4964-b01c-4152-9b8d-3c60c157b898" />

## Resultado esperado
Como el número es 5, debe mostrar **"Menor"**.

---

# Problema 7

## Imagen: problema
![Problema 7 - Problema]

<img width="1389" height="696" alt="Captura de pantalla 2026-03-27 a las 20 34 37" src="https://github.com/user-attachments/assets/74028052-c7d4-4201-808d-94e5b68baa56" />

## Explicación
Se vuelve a usar `when` de forma incorrecta para comparar condiciones.

## Solución esperada
Debe corregirse la estructura para evaluar correctamente cada caso según la nota.

## Imagen: solución esperada
![Problema 7 - Solución esperada]
<img width="630" height="545" alt="Captura de pantalla 2026-03-27 a las 20 35 30" src="https://github.com/user-attachments/assets/18f4d21b-19f4-479d-9c2d-301f88fdba6b" />


## Resultado esperado
Como la nota es 18, debe mostrar **"Excelente"**.

---

# Problema 8

## Imagen: problema
![Problema 8 - Problema]
<img width="807" height="571" alt="Captura de pantalla 2026-03-27 a las 20 36 01" src="https://github.com/user-attachments/assets/00db11c3-920c-4f6a-9cd7-3898509055da" />


## Explicación
La función indica que devolverá un tipo de dato, pero en realidad retorna otro diferente.

## Solución esperada
Debe corregirse para que el valor retornado sea del mismo tipo que se declaró en la función.

## Imagen: solución esperada
![Problema 8 - Solución esperada]
<img width="584" height="575" alt="Captura de pantalla 2026-03-27 a las 20 36 23" src="https://github.com/user-attachments/assets/5f3b3e1f-fe26-4fca-86c5-0e09dc818bf8" />



## Resultado esperado
La función debe devolver un texto.  
Si luego se imprime ese valor, por ejemplo, podría mostrarse **"Hola"**.

---

# Problema 9

## Imagen: problema
![Problema 9 - Problema]
<img width="637" height="575" alt="Captura de pantalla 2026-03-27 a las 20 38 02" src="https://github.com/user-attachments/assets/6552f26d-2ed7-41cc-b81c-8c7644e1ea8c" />


## Explicación
La función necesita recibir un dato, pero fue llamada sin enviarlo.

## Solución esperada
Debe llamarse la función enviándole el argumento que necesita.

## Imagen: solución esperada
![Problema 9 - Solución esperada]
<img width="544" height="539" alt="Captura de pantalla 2026-03-27 a las 20 39 19" src="https://github.com/user-attachments/assets/d9f02916-d3e9-4aab-992f-d1e2a7c45724" />



## Resultado esperado
Debe mostrar el texto enviado a la función, por ejemplo: **"César"**.

---

# Problema 10

## Imagen: problema
![Problema 10 - Problema]
<img width="856" height="628" alt="Captura de pantalla 2026-03-27 a las 20 39 55" src="https://github.com/user-attachments/assets/dcdc392b-5b59-4f45-a904-b47a2e0f8290" />



## Explicación
La misma variable fue declarada dos veces en el mismo bloque.

## Solución esperada
La variable no debe volver a declararse; solo debe cambiarse su valor.

## Imagen: solución esperada
![Problema 10 - Solución esperada]
<img width="613" height="640" alt="Captura de pantalla 2026-03-27 a las 20 40 22" src="https://github.com/user-attachments/assets/b206e305-2050-41f9-9223-2579a11f0956" />


## Resultado esperado
Debe mostrar el valor final de la variable, es decir: **20**.

---

# Conclusión

Estos ejercicios permiten reconocer errores básicos en Kotlin, como el uso incorrecto de variables, comparaciones, estructuras condicionales, ciclos y funciones.

Al corregirlos, se comprende mejor cómo escribir código de forma correcta y ordenada en este lenguaje.
