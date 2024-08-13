# Lenguajes Funcionales

Los lenguajes funcionales son una categoría de lenguajes de programación que se basan en el paradigma de la programación funcional. Este paradigma se centra en el uso de funciones matemáticas para operar sobre datos y evita el uso de estado mutable y efectos secundarios.

## Características Principales

1. **Funciones de Primera Clase**: Las funciones son tratadas como ciudadanos de primera clase, lo que significa que pueden ser pasadas como argumentos a otras funciones, retornadas como valores de otras funciones, y asignadas a variables.

2. **Inmutabilidad**: En los lenguajes funcionales, los datos son inmutables. Una vez que se crea un dato, no se puede cambiar. En lugar de modificar un dato, se crean nuevos datos.

3. **Funciones Puras**: Una función pura es una función que, para una misma entrada, siempre devuelve la misma salida y no tiene efectos secundarios.

4. **Expresiones en lugar de Sentencias**: Los lenguajes funcionales suelen usar expresiones en lugar de sentencias. Las expresiones devuelven valores y pueden ser anidadas para formar programas complejos.

5. **Evaluación Perezosa**: Algunos lenguajes funcionales usan evaluación perezosa, que retrasa la evaluación de una expresión hasta que su valor sea realmente necesario.

## Lenguajes Funcionales Populares

### Haskell

 Haskell es un lenguaje puramente funcional que se enfoca en la robustez y la corrección del código. Es conocido por su fuerte sistema de tipos y su capacidad para manejar la programación concurrente.

 ampliamente utilizado en investigación académica y en la industria para aplicaciones que requieren alta fiabilidad.
 
### Erlang

 Erlang es un lenguaje diseñado para sistemas concurrentes y distribuidos. Es muy utilizado en aplicaciones de telecomunicaciones y tiene un enfoque en la tolerancia a fallos.

 Utilizado en sistemas de telecomunicaciones y en aplicaciones que requieren alta disponibilidad y tolerancia a fallos.
 
### Scala

 Scala combina características de los lenguajes funcionales y orientados a objetos. Es ampliamente utilizado en la industria, especialmente en aplicaciones que requieren alta escalabilidad.

 Utilizado en aplicaciones empresariales y en el desarrollo de software que se ejecuta en la JVM (Java Virtual Machine).
 
### Clojure

 Clojure es un lenguaje funcional que se ejecuta sobre la máquina virtual de Java (JVM). Se centra en la programación concurrente y la simplicidad.
 
### F#

 es un lenguaje funcional que se ejecuta sobre la plataforma .NET. Ofrece un equilibrio entre programación funcional y orientada a objetos.

 ampliamente utilizado en el desarrollo de aplicaciones financieras y científicas.
 
## Beneficios de la Programación Funcional

- **Facilita el Razonamiento sobre el Código**: Al evitar efectos secundarios y estado mutable, es más fácil predecir cómo se comportará el código.
- **Mejora la Concisión**: Las funciones de primera clase y la inmutabilidad permiten escribir código más conciso y expresivo.
- **Facilita el Paralelismo**: La programación funcional se presta naturalmente para la ejecución en paralelo, dado que las funciones puras no tienen efectos secundarios.

## Comparación con Otros Paradigmas

**Programación Imperativa**: En contraste con la programación funcional, la programación imperativa se centra en la manipulación de estados y el uso de instrucciones secuenciales.

**Programación Orientada**: a Objetos: Mientras que la programación orientada a objetos organiza el código en torno a objetos y clases, la programación funcional se centra en las funciones y los datos inmutables.

## Ventajas y Desventajas

**Ventajas**

-Predecibilidad: Las funciones puras y la inmutabilidad conducen a un código más predecible y menos propenso a errores.

-Concisión: Los lenguajes funcionales a menudo permiten escribir código más conciso y expresivo.

-Facilidad de Razón: El enfoque en funciones puras facilita la comprensión y el razonamiento sobre el código.

**Desventajas**

-Curva de Aprendizaje: Los conceptos funcionales pueden ser difíciles de aprender para los programadores acostumbrados a paradigmas imperativos.

-Desempeño: La evaluación perezosa y la creación constante de nuevos datos pueden llevar a problemas de rendimiento en algunas aplicaciones.

