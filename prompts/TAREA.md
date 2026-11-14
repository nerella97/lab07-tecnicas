# Tarea: Mi prompt avanzado

En este documento se presenta el proceso iterativo de diseño de un prompt a lo largo de tres versiones (`v1`, `v2` y `v3`). El objetivo es demostrar cómo la combinación progresiva de técnicas de ingeniería de prompts —**Role Prompting**, **Chain of Thought** y **Autocrítica**— mejora significativamente la calidad, estructura y confiabilidad de las respuestas generadas por un modelo de lenguaje.

## Tarea elegida

Creación de un módulo en Java para el registro de clientes aplicando principios de Programación Orientada a Objetos (POO) y validación defensiva de datos..

## Version 1: prompt basico [Role Prompting]

```texto
 Actúa como un desarrollador Backend Java Senior especializado en programación orientada a objetos y validación defensiva de datos, y crea un registro de clientes.
 ```

## Version 2 [Chain of Thought]

```texto
 Actúa como un desarrollador Backend Java Senior especializado en programación orientada a objetos y validación defensiva de datos, y crea un registro de clientes.

 Crea una clase Cliente con los atributos nombre, dni, correo y direccion, considerando las siguientes restricciones:

  - Ningún atributo debe aceptar valores nulos, vacíos o espacios en blanco.

- nombre debe contener únicamente letras, tildes, ñ y espacios.

- dni debe ser de tipo String y contener exactamente 8 dígitos numéricos.

- correo debe cumplir con un formato válido que incluya usuario, @ y dominio.

Antes de implementar la solución, analiza paso a paso los requisitos e identifica posibles casos límite.
```
## Version 3: prompt final [Autocritica]

```texto
 Actúa como un desarrollador Backend Java Senior especializado en programación orientada a objetos y validación defensiva de datos, y crea un registro de clientes.

 Crea una clase Cliente con los atributos nombre, dni, correo y direccion, considerando las siguientes restricciones:

  - Ningún atributo debe aceptar valores nulos, vacíos o espacios en blanco.

- nombre debe contener únicamente letras, tildes, ñ y espacios.

- dni debe ser de tipo String y contener exactamente 8 dígitos numéricos.

- correo debe cumplir con un formato válido que incluya usuario, @ y dominio.

Antes de implementar la solución, analiza paso a paso los requisitos e identifica posibles casos límite.

Una vez desarrollado el código, realiza una autocrítica para detectar errores, validaciones faltantes o incumplimientos de los requisitos. Corrige los problemas identificados antes de presentar la solución definitiva.
```
## Tecnicas usadas en el prompt final 

| Técnica utilizada | Fragmento / Sección del prompt final | 
| :--- | :--- | 
| **Role Prompting** | *"Actúa como un desarrollador Backend Java Senior especializado en programación orientada a objetos y validación defensiva de datos..."* | 
| **Chain of Thought** | *"Antes de implementar la solución, analiza paso a paso los requisitos e identifica posibles casos límite."* | 
| **Autocrítica** | *"Una vez desarrollado el código, realiza una autocrítica para detectar errores, validaciones faltantes o incumplimientos de los requisitos. Corrige los problemas identificados..."* | 
