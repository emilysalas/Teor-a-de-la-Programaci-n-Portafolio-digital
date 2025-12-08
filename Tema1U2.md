# 🧩 Tema 1: Estructuras Condicionales

---

## 📊 ¿Qué son las estructuras condicionales?

Las estructuras condicionales son instrucciones de programación que permiten al programa tomar decisiones y ejecutar diferentes bloques de código dependiendo de si se cumple o no una condición lógica (*verdadera o falsa*). Es decir, dirigen el flujo del programa según situaciones específicas evaluadas en tiempo de ejecución [8]. 

---

## 📚 Principales tipos de estructuras condicionales (Resumen)

| Icono | Estructura | ¿Cuándo usarla? | Ventaja |
|:-----:|:----------:|:----------------:|:-------|
| 🔹 | **if** (simple) | Cuando solo se ejecuta algo si se cumple la condición [8][9]. | Sintaxis simple y directa |
| 🔸 | **if - else** | Cuando hay dos caminos (si se cumple / si no) [9][10]. | Cubre ambos resultados posibles |
| 🔺 | **if - else if - else** | Cuando hay múltiples alternativas [8][9]. | Evita múltiples `if` independientes |
| 🔁 | **switch - case** | Cuando se compara una variable contra varios valores constantes [8][10]. | Más legible que muchos `if` encadenados |

---

## ✨ Descripciones y ejemplos

### 🔹 IF (condicional simple)
Ejecuta un bloque solo si la condición es verdadera [8][9].
```c
if (edad >= 18) {
    printf("Eres mayor de edad\n");
}
````

### 🔸 IF - ELSE (condicional doble)

Selecciona entre dos caminos (verdadero o falso) [9][10].

```c
if (numero > 0) {
    printf("Positivo\n");
} else {
    printf("No es positivo\n");
}
```

### 🔺 IF - ELSE IF - ELSE (condicional múltiple)

Para varias alternativas exclusivas [8][11].

```c
if (nota >= 90) {
    printf("A\n");
} else if (nota >= 80) {
    printf("B\n");
} else {
    printf("C o menor\n");
}
```

### 🔁 SWITCH - CASE

Útil para múltiples valores discretos de una variable (enteros, chars, enums) [9][10].

```c
switch (opcion) {
    case 1:
        // acción 1
        break;
    case 2:
        // acción 2
        break;
    default:
        // acción por defecto
}
```

---
<img width="975" height="532" alt="image" src="https://github.com/user-attachments/assets/caf63120-90a8-4a38-9bdd-634d18b67bef" />

----

## 📝 ¿Para qué sirven en la práctica?

* Tomar decisiones según la entrada del usuario.
* Habilitar/deshabilitar funciones según condiciones del estado.
* Implementar validaciones y controles de seguridad.
* Dirigir el flujo para diferentes tipos de salida o formatos.

---

<details>
<summary>🔍 Ejemplo usando el If- Else (🖱️da click )</summary>

--------

**Problema:** Dado un número entero, indicar si es positivo, negativo o cero; además indicar si es par o impar.

**Código en Lenguaje (C):**

<img width="471" height="521" alt="image" src="https://github.com/user-attachments/assets/d64a1e95-c148-4b19-83db-94751fc162d1" />

*Verificación de la ejecución*

<img width="590" height="237" alt="image" src="https://github.com/user-attachments/assets/7c453a85-4879-4ed0-b6c2-afc57622c468" />

</details>

---

<details>
<summary>🔍 Ejemplo usando el Switch - Case (🖱️da click )</summary>

--------

**Problema:** Dados dos números enteros, el usuario indica que aperación desea realizar, se ejecuta la operación dependiendo del signo que ingrese el usuario, y finalmente se da la respuesta.

**Código en Lenguaje (C):**

<img width="522" height="714" alt="image" src="https://github.com/user-attachments/assets/1de3ae81-8fff-4921-ac20-a5673b28339f" />

*Verificación de la ejecución*

➕ **Suma**

<img width="593" height="142" alt="image" src="https://github.com/user-attachments/assets/9140a6a6-40ca-4f87-9f37-f9c4f62b910f" />

➖ **Resta**

<img width="281" height="126" alt="image" src="https://github.com/user-attachments/assets/5cb9b07b-6e47-4c92-a0c1-d482ef08b198" />

✖️ **Multiplicación**

<img width="307" height="127" alt="image" src="https://github.com/user-attachments/assets/987226c8-7a0d-4861-afc5-7e6c216e2f20" />

➗ **División**

<img width="283" height="127" alt="image" src="https://github.com/user-attachments/assets/346b4494-743e-4e2a-9102-ae219267783b" />

</details>

------
💡Desea regresar? [🔙](Unidad2.md)







