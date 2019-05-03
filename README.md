# Singleton

## Descripción

El patrón de diseño Singleton o de instancia única está diseñado para restringir la creación de objetos pertenecientes a una clase o el valor de un tipo a un único objeto. Su intención consiste en garantizar que una clase sólo tenga una instancia y proporcionar un punto de acceso global a ella. No se encarga de la creación de objetos en sí, sino que se enfoca en la restricción en la creación de un objeto en uno propio.

## Clasificación

Es de tipo patrones creacionales.
Esta clasificación son los que facilitan la tarea de creación de nuevos objetos, de tal forma que el proceso de creación pueda ser desacoplado de la implementación del resto del sistema.

### Están basados en dos conceptos:

    1. Encapsular el conocimiento acerca de los tipos concretos que nuestro sistema utiliza. Estos patrones normalmente trabajarán con interfaces, por lo que la implementación concreta que utilicemos queda aislada.
    2. Ocultar cómo estas implementaciones concretas necesitan ser creadas y cómo se combinan entre sí.

## Ventajas de su uso.

    • Este patrón de diseño se encarga de que una clase determinada unicamente pueda tener un único objeto.
    • Mejora sobre las variables globales. Ya no se reservan nombres para las variables globales, ahora solo existen instancias.
    • Controla el acceso a la instancia única, porque la clase Singleton encapsula la única instancia. Así se obtiene control sobre cómo y cuándo se accede a ella.
    • Permite el refinamiento de las operaciones y la representación.
    • Permite un numero variable de instancias. 
    • El patrón es fácilmente configurable para permitir más de una instanciamás flexible que las operaciones de clases.
