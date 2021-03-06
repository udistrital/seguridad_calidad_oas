# Aseguramiento de la Calidad (QA)
En esta sección se encuentran los lineamientos que todos los desarrollos de software deben cumplir en el marco de la calidad de la Oficina Asesora de Sistemas (OAS). Cada uno de los requerimientos han sido documentados y socializados con los miembros de cada proyecto de desarrollo y consolidadas en repositorio github de la organización.

## Pruebas Funcionales
Busca ejecutar, revisar y retroalimentar el comportameinto previamente diseñado en el aplicacito.

### Pruebas unitarias
Las pruebas unitarias son las que aseguran que cada línea del código desarrollado en un componente, requerimiento, necesida brinde los resultados adecuados.  
Sirven para garantizar que los componentes ya finalizados y que contengan sus respectivas pruebas; puedan ser revisados ante un nuevo requerimiento o modificaciones dependiente. Al integrar los nuevos requerimientos, si las pruebas unitarias son satisfactorias se podría asegurar que las funcionalidades primarias siguen siendo funcionales y que los nuevos requerimientos no afectaron la lógica predecesora.  
Se  desarrollan pruebas que validen las reglas del negocio, los perfiles y permisos, funciones y cálculos específicos o controles de entrada en formularios.  


### Pruebas de humo
Las pruebas de humo se realizan para verificar si las funcionalidades más significativas de la aplicación funcionan o no. De forma que lo más básico del software se ejecute de forma correcta con pruebas sencillas y rápidas.   
En entornos productivos, son de gran utilidad para identificar rápidamente una falla o caída de un servicio dentro de una arquitectura orientado a microservicios.  
Por Ejemplo: Una prueba de humo esencial es la validación de que los EndPoint a consumir dentro de un api_mid “Middleware” se encuentren activos o respondiendo un estado 200 en sus solicitudes.


### Pruebas de componentes
Este tipo de pruebas se ejecutan de forma independiente o separada, el alcance de la prueba está limitado única y exclusivamente a un requerimiento pequeño  o historia de usuario o módulo en particular “el componente específico”; para comprobar que el resultado sea el requerido.

### Pruebas de integración
Este tipo de pruebas busca complementar el tipo de pruebas de componentes, ya que lo que se ha trabajado en las pruebas de componentes ahora se verifica en los componentes posteriores o subyacentes, componentes en los que dependen o proporcionan información con otros. busca verificar que el flujo entre componentes concuerde, que su integración no tenga ningún tipo de dificultad.

### Pruebas de regresión
Es normal que los desarrolladores modifiquen y mejoren las funcionalidades de su desarrollo por iteraciones, entregas o sprint. Por ello existe una gran posibilidad de que puedan causar ‘efectos’ inesperados en su comportamiento. Estas pruebas de regresión se realizan para asegurar que los cambios o adiciones no hayan alterado ni eliminado las funcionalidades existentes.   
El objetivo de las pruebas de regresión es encontrar errores que puedan haber sido introducidos accidentalmente en la compilación existente y así garantizar que los errores eliminados continúen así.

### Pruebas de cordura
Si tienes una compilación con modificaciones menores, en vez de ejecutar las pruebas de regresión, realizamos una prueba de cordura.   
Con ella podemos determinar que las modificaciones realmente hayan solucionado los problemas. Y que dichas correcciones no hayan generado ningún problema. Usualmente estas pruebas son subpruebas de la de ‘Regresión’  ya que están relacionadas con los cambios realizados en el producto.

### Pruebas de aceptación
Cuando el software o el componente desarrollado se encuentra en una versión estable, se somete a la validación funcional por el  Equipo de QA/Equipo de analistas/Equipo de requerimientos o el mismo cliente los cual verifica que el requerimientos o historia de usuario exista y realice lo que se especificó.

## Tomado de:
[Tipos de pruebas funcionales para el aseguramiento de la calidad](https://trycore.co/transformacion-digital/tipos-de-pruebas-funcionales/)
