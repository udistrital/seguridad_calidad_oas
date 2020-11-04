# Aseguramiento de la Calidad (QA)
En esta sección se encuentran los lineamientos que todos los desarrollos de software deben cumplir en el marco de la calidad de la Oficina Asesora de Sistemas (OAS). Cada uno de los requerimientos han sido documentados y socializados con los miembros de cada proyecto de desarrollo y consolidadas en repositorio github de la organización.

## Pruebas No Funcionales
Busca identificar problemas de desempeño y rendimiento. Verifica un atributo o requisito para determinar la operación de un sistema.   
Es un medio de control de calidad que incluye pruebas de: Rendimiento, Carga, Estrés, Usabilidad, Mantenibilidad, Fiabilidad o Portabilidad.


### Prueba de carga (:heavy_check_mark:)
Las pruebas de carga consisten en simular demanda sobre una aplicación de software y medir el resultado. Estas pruebas se realizan bajo demanda esperada y también en condiciones de sobrecarga (picos en la demanda).

Las pruebas de carga nos pueden brindar el rendimiento de un aplicativo bajo un cierto número de usuario concurrentes bajo un escenario.


### Pruebas de estres (:heavy_check_mark:)
Las prueba de estrés es llevar al límite la aplicación con un número de usuarios y ver cómo se comporta el aplicativo bajo este escenario.

Son pruebas de carga que se realizan con demandas mayores a la capacidad operativa, con frecuencia hasta llegar al punto de ruptura.


### Pruebas de volumen
Consiste en validar el funcionamiento de la aplicación con cierto volumen de datos.
Es muy común que cuando las aplicaciones son nuevas, los filtros y las búsquedas funcionan de maravilla ya que las bases datos aún no han consolidado un volumen considerable. Es por esto la razón de estas pruebas.  


### Pruebas de configuración (:heavy_check_mark:)
Se realizan para validar que efectos en el desempeño tienen ciertos cambios en la configuración; también llamado tuneo o tunning, en la que a nivel tanto de infraestructura como de aplicación o agentes externos de seguridad entre otros  se proporcionan características al sistema y de acuerdo a cada configuración la aplicación presenta un comportamiento.

### Pruebas de seguridad (:heavy_check_mark:)
Consiste en probar los atributos o características de seguridad del sistema, si es un sistema seguro o no, si puede ser vulnerado, si existe control de acceso por medio de cuentas de usuario, si pueden ser vulnerados estos accesos.   
Se abordará un capitulo especifico en este tema.


## Tomado de:
[10 tipos de pruebas no funcionales](http://www.pmoinformatica.com/2016/07/tipos-pruebas-no-funcionales.html)
