# Bitacora de tecnicas avanzadas

Laboratorio 07: Tecnicas Avanzadas de Prompting. Herramienta de IA usada: (escribe aqui cual usaste)
##	Ejercicio	2:	Zero-shot, one-shot y few-shot

| Tipo | Aciertos (de 5) | Formato de la respuesta | Todas con el mismo formato (Si/No)
|----|----|----|-----|
| Zero-shot |Si | No| si, pero no era el formato|
| One-shot |Si |Si |Si |
| Few-shot |Si |Si | Si|


##	Ejercicio	3:	Chain of Thought

| Pedido | Respuesta de la IA | Muestra los pasos (Si/No) | Correcta (Si/No) |
|---|---|---|----|
| Directo | Correcto| No| Si |
| Paso a paso | Correcto|Si | Si |


##	Ejercicio	4:	Role prompting

| Version | Vocabulario (sencillo/tecnico) | Usa ejemplos o codigo | A quien le sirve mas |
|---|---|---|---|
| A. Sin rol | Sencillo| Si|Aprendiz |
| B. Rol docente | Sencillo |Si | Estudiante|
| C. Rol senior | Técnico| Si| Personal técnico |


##	Ejercicio	5:	Descomposicion
```texto
Voy a crear un sistema de inventario para una tienda pequena en Java. Lista los 5 requisitos principales del sistema.
```

```texto
Con esos requisitos, disena las clases necesarias. Para cada clase indica sus atributos con su tipo de dato.
```
```texto
Escribe el codigo Java de la clase Producto con sus atributos, un constructor y los metodos get y set.
```
```texto
Revisa el codigo de la clase Producto y propone 3 mejoras concretas.
```

##	Ejercicio	6:	Prompt estructurado y autocritica


<rol>Actua como analista de pruebas de software.</rol>

<contexto>Login web con correo y contrasena. La cuenta se bloquea despues de 3 intentos fallidos.</contexto>

<tarea>Piensa paso a paso que puede fallar y escribe 6 casos de prueba.</tarea>

<formato>Tabla con las columnas: ID, escenario, datos de entrada, resultado esperado.</formato>

Revisa tu tabla: faltan casos limite como campos vacios, correo sin @
o contrasena con espacios? Agrega los que falten e indica cuales agregaste.

