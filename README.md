# EJEMPLO 2 DE RXJAVA

## Proposito 
En este ejemplo veremos la usabilidad de RxJava usando .just en el observer.
___

### Instrucciones
Debemos de ubicar el archivo Build.Gradle, en este proyecto lo genero con el nombre: *build.gradle.kts*
1. Despues agregaremos la siguiente linea de comando en dependencias
~~~
 implementation ("io.reactivex.rxjava3:rxjava:3.1.6-RC0")
~~~
2. En caso de que el archivo lo genere como simplemente *build.gradle* no es necesario implementar las **()**
3. Posteriormente le indicaremos a Gradle cargar las dependencias insertadas.
