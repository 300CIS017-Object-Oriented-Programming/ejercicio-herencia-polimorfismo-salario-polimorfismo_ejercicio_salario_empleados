# polimorfismo - Ejercicio Salario de Empleados
Ejercicio que usa conceptos de polimorfismo en POO

## Enunciado
Diseña un sistema de gestión de nómina para una empresa de desarrollo de software que permita calcular el salario de diferentes tipos de empleados:  desarrolladores junior, desarrolladores senior, líderes técnicos y testers.

* Los desarrolladores junior ganan su salario base.
* Los desarrolladores senior reciben un bono del 20% sobre su salario base.
* Los líderes técnicos reciben un bono del 25% sobre su salario base.
* Los testers reciben un bono del 5% sobre su salario base

El sistema debe ser capaz de:
* Procesar la nómina de todos los empleados registrados, mostrando el salario calculado para cada uno. [ Por cuestión de pruebas cree un metodo "inicializarDatos" en los que cree empleados de todos los tipos al menos dos de cada tipo]. Use poliformismo 
* Calcular y mostrar el valor total a pagar a todos los empleados. Use polimorfismo

## Ejemplo
Para solucionar este ejercicio puede tomar como ejemplo lo desarrollado en https://github.com/300CIS017-Object-Oriented-Programming/solucionHerenciaFigurasGeometricas

## ⚙️ Requerimientos no funcionales

- La solución debe implementar relaciones de herencia de manera adecuada y explícita.
- Se debe aplicar polimorfismo mediante la sobrescritura de métodos, manteniendo las mismas firmas en la clase base y en las derivadas.
- Se recomienda incorporar un archivo `.gitignore` en el repositorio para excluir del repo carpetas de archivos de compilación como la carpeta cmake-build-debug y la .idea.
- Organice el proyecto en carpetas, en el ejemplo puede ver una estructura de directorios que podría seguir.
- Use un cmake parecido al del ejemplo pues le facilitará la gestión de nuevas clases

## 📦 Entregables
 
A - Incluya en el README una sección llamada `Evidencia de ejecución`.

Allí debe mostrar:

- Una captura de pantalla o bloque de salida de consola donde se vea la nómina procesada.
- El salario calculado para al menos ocho empleados.
- El total de la nómina.
- Una tabla con los datos de prueba usados.

B - Explicación corta del diseño

B - Incluya una sección llamada `Explicación del diseño`.
1. ¿Cuál es la clase base y por qué?
2. ¿Qué método se sobrescribe en las clases derivadas?
3. ¿Dónde se evidencia el polimorfismo en el programa?
4. ¿Por qué sería menos adecuado resolver este ejercicio con muchos `if` o `switch` para identificar el tipo de empleado?

La explicación debe estar escrita con palabras propias. No se espera una definición teórica larga, sino una explicación conectada con el código entregado.


Incluya una sección llamada `Dificultad encontrada`.

C- Explique una dificultad que apareció durante la actividad. Puede estar relacionada con:

- La herencia.
- La sobrescritura de métodos.
- El uso de apuntadores.
- La organización en archivos `.h` y `.cpp`.
- La ejecución del proyecto
- La comprensión del polimorfismo.

La respuesta debe incluir:

- Qué problema apareció.
- Qué parte del código estaba relacionada con el problema.
- Cómo lo corrigió o qué entendió después de revisarlo.

6. Declaración de uso de IA

Incluya una sección llamada `Uso de IA`.

Seleccione una de las siguientes opciones y complétela:

#### Opción A: no usé IA

> No usé herramientas de IA generativa para resolver esta actividad. El diseño, el código y las pruebas fueron desarrollados por mí.

#### Opción B: usé IA como apoyo

> Usé IA generativa como apoyo en esta actividad. La utilicé para: [explicar un error / revisar una idea / sugerir pruebas / aclarar un concepto / mejorar la documentación / otra].
>
> Fragmento o idea sugerida por la IA:
> [Describa brevemente qué le sugirió la IA].
>
> Qué revisé antes de usarlo:
> [Explique cómo verificó que la sugerencia tenía sentido].
>
> Qué cambié o adapté:
> [Explique qué parte ajustó con criterio propio].

El uso de IA no reemplaza la responsabilidad del estudiante sobre el código entregado. El estudiante debe poder explicar cualquier parte de su solución.



