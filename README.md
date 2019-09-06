## Contador de Caracteres

### 1.	Introducción 

Con el objetivo de contar las letras que contiene una palabra en español máxima de 20 caracteres, se diseña un servicio web en lenguaje Java.


 ### 2.	Requerimientos del Sistema 

### 2.1.	Requerimientos Funcionales

*	Solo pueden usarlo las personas que conozcan un clave que debe ser ingresada en un campo.
*	Recibir una palabra en español sin espacios ni caracteres especiales de máximo 20 caracteres.
*	Se debe restringir que el usuario ingrese una palabra con más de 20 caracteres.
*	La palabra se debe ingresar por teclado en un campo dispuesto para ello.
*	Devolver en pantalla el número de caracteres palabra escrito en letras en español.


### 2.2.	Requerimientos no Funcionales

*	La interfaz gráfica debe cumplir los estándares WCAG A


### 3.	Arquitectura del Sistema

Controlador: Gestiona los eventos que provoca el usuario al interactuar con la interfaz gráfica, en este proyecto está compuesto por las clases:
```
CounterLettersController
LoginController
```
Vista: Es cada una de las interfaces gráficas con las que interactúa el usuario y en este proyecto son:
```
Index.jsp
CounterView.jsp
numberLetters.jsp
```
Modelo: Contiene la logica del programa y está compuesto por las clases: 
```
Usuario 
Contador.  
```
