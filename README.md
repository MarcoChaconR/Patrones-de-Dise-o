<div align="center">
    <h1>Patrones de Diseño</h1>
</div>

<div>
Este repositorio pretende realizar una recolección de los patrones de diseño más conocidos y los no tan conocidos, de forma que se pueda tener una navaja suiza de desarrollo de software.<br /><br />

Por el momento se empezara en lenguaje Java; sin embargo, se espera poder ampliar esta lista en varios lenguajes como python, javascript y C#.
  <br><br>
  Los patrnes de diseño de software son una solución general y reutilizable para un problema común dentro de un contexto dado en el diseño de software . No es un diseño terminado que puede transformarse directamente en código fuente o máquina. Más bien, es una descripción o plantilla sobre cómo resolver un problema que se puede usar en muchas situaciones diferentes. Los patrones de diseño son mejores prácticas formalizadas que el programador puede usar para resolver problemas comunes al diseñar una aplicación o sistema.<br><br>Los patrones de diseño orientados a objetos generalmente muestran relaciones e interacciones entre clases u objetos, sin especificar las clases u objetos finales de la aplicación que están involucrados. Los patrones que implican un estado mutable pueden no ser adecuados para los lenguajes de programación funcionales. Algunos patrones pueden volverse innecesarios en lenguajes que tienen soporte incorporado para resolver el problema que intentan resolver, y los patrones orientados a objetos no son necesariamente adecuados para lenguajes no orientados a objetos.
</div>
<br />

---

<br />

## Indice

* [Creacionales](#Creacionales)
* [Estructurales](#Estructurales)
* [Comportamiento](#Comportamiento)
* [Patrones de concurrencia ](#Comportamiento)
---

<br>

### Creacionales
| Lenguaje | Repositorio | Nombre del Patron | Descripción |
|---|---|---|---|
| Java | [AbstractFactory](https://github.com/MarcoChaconR/AbstractFactory) | Abstract Factory |  Proporcione una interfaz para crear familias de objetos relacionados o dependientes sin especificar sus clases concretas. |
| Java | [Builder](https://github.com/MarcoChaconR/Buider) |Builder| Separar la construcción de un objeto complejo de su representación, permitiendo que un mismo proceso de construcción genere varias representaciones. |
| Java | [FactoryMethod](https://github.com/MarcoChaconR/FactoryMethod)|Factory Method| Defina una interfaz para crear un solo objeto, pero deje que las subclases decidan qué clase instanciar. Factory Method permite que una clase difiera la creación de instancias a las subclases. |
| Java | [Prototype](https://github.com/MarcoChaconR/Prototype)| Prototype | Crea nuevos objetos a partir del "esqueleto" de un objeto existente, aumentando así el rendimiento y reduciendo al mínimo las huellas de memoria. |
| Java | [PrototypeShallowClone](https://github.com/MarcoChaconR/PrototypeShallowClone)| Prototype Shallow Clone | Crea objetos nuevos de una instancia ya existente, implementa la interface de Java Cloneable, unicamente copia los tipos de datos básicos. |
| Java | [PrototypeDeepClone](https://github.com/MarcoChaconR/PrototypeDeepClone)| Prototype Deep Clone | Crea objetos nuevos de una instancia ya existente, implementa la interface de Java Cloneable, este patron clona objetos completos. |
| Java | [Singleton](https://github.com/MarcoChaconR/Singleton)| Singleton | Este patrón se asegura de que una clase tenga solo una instancia y proporcione un punto de acceso global a ella. |
| Java | [DependencyInjection]() | Dependency Injection | Una clase acepta los objetos que requiere de un inyector en lugar de crear los objetos directamente. |
<br />

**[⬆ Regresar al indice ](#Indice)**

---

<br />

### Estructurales


<br />

**[⬆ Regresar al indice ](#Indice)**

---

<br />

### Comportamiento


<br />

**[⬆ Regresar al indice ](#Indice)**

---

<br />

### Patrones de concurrencia 


<br />

**[⬆ Regresar al indice ](#Indice)**

---

<br />
