# Curso de Historias de Usuario en Scrum
### ORIGEN DE SCRUM
El origen de la metodoliga SCRUM parte de un marco de trabajo llamado **EXTREME PROGRAMMING**. Esta metodogia fue fundamental y de gran importancia dentro del manifiesto agil y es una de las razones por las cuales usamos HU en SCRUM. 
El concepto de Scrum tiene su origen en un estudio de 1986 sobre los nuevos procesos de desarrollo utilizados en productos exitosos en Japón y los Estados Unidos (cámaras de fotos de Canon, fotocopiadoras de Xerox, automóviles de Honda, ordenadores de HP y otros). Los equipos que desarrollaron estos productos partían de requisitos muy generales, así como novedosos, y debían salir al mercado en mucho menos del tiempo del que se tardó en lanzar productos anteriores.
En 1993 se realizó el primer Scrum para desarrollo de software y en 1995 el proceso fue formalizado. Ya para el 2001 un grupo de personas muy relevantes en lo que empezaba a ser el desarrollo ágil escribieron los valores fundamentales de los procesos ágiles.
> *Fuente:* https://proyectosagiles.org/

### Que es una Historia de Usuario (HU)?
Una HU describe de manera simple una funcionalidad esperada, contada desde la perspectiva de la persona que la va a usar.
Las Historias de Usuario son los elementos más específicos de la lista de producto y contienen la visión del usuario sobre la funcionalidad esperada de ese producto. <br><br>
**Nota:** 
1. No confundir al usurio final de esta funcionalidad con la persona que solicita el software o cliente final (Produt Owner).
2. No se deben confundir las Historias de Usuario con requerimientos, en ellas se referencia lo que el usuario quiere o espera del producto terminado.
- **Que es Product Owner?**
El Product Owner es la voz del cliente, dentro del grupo SCRUM y representa los intereses de un mercado y/o un grupo de usuarios/clientes finales.

###  Componentes de una HU
Cuando hablamos de historias de usuario, siempre debemos considerar 4 elementos importantes:
1. **Usuario:** Representa a quien va a usar la funcionalidad. (Quien)
2. **Funcionalidad:** Que es lo que especificamente se quiere hacer? (Que)
3. **Veneficio:** Para que se pide esa funcionalidad? (Para Que)
4. **Criterios de Aceptacion:** Representan las condiciones de calidad. 
Son las guia de aceptacion de dicha funcionalidad.

Los componentes que debe tener una buena Historia de Usuario, para que sea fácil de entender por parte del equipo, generen valor y simplifiquen el proceso de desarrollo son:

**Título:** Permite conocer rápidamente de qué se trata la historia y por ello debe ser concreta y clara.
**Descripción:** Contiene información sobre cómo se deben ejecutar las tareas, puede incluir componentes técnicos, especificar el tipo de diseño, el lugar donde se van a almacenar las tareas o el flujo de arquitectura que se debe seguir. En resumen, contempla una definición más específica para completar la historia.

- **Ejemplo: Plantilla de Historias de Usuario**
                    
| | Clave - Nombre abreviado de la funcionalidad |
| ------------ | ------------ |
| **Quién ** | Quien va a usar la funcionalidad |
| **Qué**  | Especificamente que se quiere hacer |
| **Para qué**  | Para que se pide esa funcionalidad |
|  | **Criterios de Aceptación** |
| 1 | Condición 1  |
| 2 | ------------  |
| 3 | ------------  |
| 4 | ------------  |
| x | Condición x  |


| | | Como "rol" quiero "funcionalidad" para poder "beneficio" |
| ------------ | ------------ |------------ |
|  | CRITERIOS ACEPTACION | |
| 1 | escenario 1 | Condicion1 que se debe cumplir |
| 2 | escenario 2 |------------ |
| 3 | escenario 3 |------------ |
| x | escenario x | Condicion(x) que se debe cumplir |

## Estrategias para Implementar una HU de Manera Efectiva.
### * Dimensionamiento:
1. **Entendimiento del Problema:** Entender el origen de lo que se esta pidiendo. Saber y entender que problema es el que se esta resolviendo.
2. **Objetivos de negocio:** Entender que el retrabajo, la falta de entendimiento y la falta de calidad afecta a nuestro negocio.
3. **Requerimientos Tecnicos: ** Todo lo que es necesario para entregar el producto.
4. **Requerimientos de Transición:** Considerar que entre ambientes pasan eventualidades que pueden provocar fallos inesperados.

### * Propiedades IVEST:
Estas propiedades estan relacionadas con las historias de usuario de la siguiente manera y debes velar porque cada Historia de Usuario las tenga:
I : **Independent**. Cuidar que una HU no sea una *Epica*.
N: **Negotiable.** Poder de descartar historias no valiosas, negociar el orden y la priorización.
V: **Valuable.** Toda historia de usuaria debe ser valiosa cuando queda claro el*“para que”.*
E: **Estimable**. El equipo de desarrollo, debe de calcular el tiempo y esfuerzo que le llevara cumplir con la HU.
S: **Small.** Se da mas peso a la conversación que nos alimenten el contexto.
T: **Testeable.** Valida que los criterios de aceptación, y especifica si la HU esta siendo “correcta”o“incorrecta”. <br><br>
**NOTA:** *Cuando todo urge nada realmente importa, porque si todo urge tiene la misma importancia, y si tiene la misma importancia no importa el orden en que lo hagas.*

## ¿Qué es un Backlog en Scrum?
El product backlog en Scrum es una lista de características que han sido priorizadas, y contiene descripciones breves sobre todo lo que se desea para el producto que se va a desarrollar. En resumen, el backlog o pila de producto, es una lista emeregente y ordenada de lo que se va a desarrollar.

### * Refinamiento Del Backlog (Backlog Grooming )
El propósito del Refinamiento del Backlog del Producto es añadir detalles, descubrir, estimar y ordenar a los elementos del Product Backlog. Durante el Refinamiento de la Lista de Pendientes del Producto, los ítems son revisados, actualizados y modificados. Esta actividad la hace todo el equipo Scrum.

## Cómo hacemos Historias de Usuario a partir listas de requerimientos?
Las historias de usuario son un componente clave de la metodología Scrum. Son una forma de describir las necesidades del usuario y de garantizar que el equipo de desarrollo las comprenda y las pueda implementar.
**Algunos pasos que podrias seguir son:**
1. **Identifique el Usuario:** Quién es el usuario que va a utilizar esta característica?, Cuáles son sus necesidades y deseos?, Que FUNCIONALIDADES hay en esos requerimientos?.
2. **Describa la Tarea:** Qué tarea quiere realizar el usuario?, Cuál es el objetivo de la tarea?
3. **Especifica los Criterios de Aceptación:** Cómo sabrás que la historia de usuario se ha completado correctamente?. Estos criterios deben ser específicos, medibles, alcanzables, relevantes y oportunos.
4. **Estima el Esfuerzo: ** Cuánto tiempo y esfuerzo requerirá la implementación de esta historia de usuario?.
5. **Prioriza las historias de usuario:** No todas las historias de usuario son iguales. Algunas son más importantes que otras. Prioriza las historias de usuario en función de su importancia y urgencia.

**NOTA:**
***Que son Criterios de Aceptacion?*** <br>
Los criterios de aceptación son una lista de requisitos que deben cumplirse para que una historia de usuario se considere completa. Se utilizan para garantizar que el equipo de desarrollo entienda las necesidades del usuario y que el producto final cumpla con las expectativas y estandar de caliadad.
Los criterios de aceptación generalmente se dividen en dos categorías: **Criterios Funcionales** y **No Funcionales**. Los criterios funcionales se refieren a las funciones específicas del producto que deben cumplirse. Los criterios no funcionales se refieren a los atributos del producto, como el rendimiento, la seguridad y la facilidad de uso.

# Test Curso de Historias de Usuario en Scrum
### Qué es una Historia de Usuario?
Es una descripción simple una característica esperada, contada desde la perspectiva de la persona que va a usar esa capacidad.
                
----
###  Cuál es una mala práctica frecuente que impide que las Historias de Usuario se utilicen correctamente?
Trabajar con Historias de Usuario de gran tamaño y difícil de estimar (épicas).
                
----
### Por qué solemos subestimar las Historias de Usuario?
Por la simplicidad.
                
----
### De qué se trata la "I" de la propiedad INVEST que deben de tener las Historias de Usuario?
Independencia
                
----
### De qué se trata la "V" de la propiedad INVEST que deben de tener las Historias de Usuario?
Valiosa
                
----
### De qué se trata la "E" de la propiedad INVEST que deben de tener las Historias de Usuario?
Estimable
                
----
### Qué es el Backlog en Scrum?
Es una lista emergente y ordenada de lo que se necesita para mejorar el producto.
                
----
### Qué es el refinamiento?
Es descomponer y definir aún más los elementos de trabajo pendiente del producto en artículos más pequeños y precisos.
                
----
### Se pueden crear Historias de Usuario a partir de listas de requisitos?
Verdadero
                
----
### Qué son los criterios de aceptación?
Son características que deben de estar presentes para considerar que se está construyendo el producto correctamente.
                
----
### Cuál de las características de la Propiedad Invest ayuda más a la priorización?
Valiosa 
