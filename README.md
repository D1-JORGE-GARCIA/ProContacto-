# Training ProContacto
#####  1.	¿Qué es un servidor HTTP?
Es un programa informático que procesa una aplicación del lado del servidor, realizando conexiones bidireccionales o unidireccionales y síncronas o asíncronas con el cliente y generando o cediendo una respuesta en cualquier lenguaje o aplicación del lado del cliente
##### 2.	 ¿Qué son los verbos HTTP? Mencionar los más conocidos
Estos verbos indican qué acción queremos realizar sobre el servidor y son GET, POST, PUT, PATCH, DELETE, HEAD, CONNECT, OPTIONS y TRACE. ... Cada uno indica una acción diferente a la que el servidor debe responder.
##### 3.	¿Qué es un request y un response en una comunicación HTTP? 
Estos verbos indican qué acción queremos realizar sobre el servidor y son GET, POST, PUT, PATCH, DELETE, HEAD, CONNECT, OPTIONS y TRACE. ... Cada uno indica una acción diferente a la que el servidor debe responder.

##### 4.	¿Qué son los headers?
Los HTTP headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc. La primera línea es la línea del request, que contiene su información básica (método HTTP, URL y versión). Lo demás son headers HTTP.
##### 5.	¿Qué es un queryString? (En el contexto de una url)
Es un término informático que se utiliza para hacer referencia a una interacción con una base de datos. Es la parte de una URL que contiene los datos que deben pasar a aplicaciones web como los programas CGI
##### 6.	 ¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
un código de respuesta (similar a los códigos de estado HTTP) que indica si la solicitud de codificación geográfica se ha realizado correctamente o no. 401 error is another HTTP response code. 401 error es otro código de respuesta HTTP.
##### 7.	 ¿Cómo se envía la data en un Get y cómo en un POST?
La diferencia entre los métodos get y post radica en la forma de enviar los datos a la página cuando se pulsa el botón “Enviar”. Mientras que el método GET envía los datos usando la URL, el método POST los envía de forma que no podemos verlos (en un segundo plano u "ocultos" al usuario).
##### 8.	 ¿Qué verbo http utiliza el navegador cuando accedemos a una página?
Todas las direcciones en Internet comienzan por http:// (o https://). Estas siglas hacen referencia al protocolo HTTP, que es el que utiliza el navegador para acceder a una página web.
 
##### 9.	 Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

##### Xml (Extensible Markup Language):
XML es uno de los formatos más utilizados para el intercambio de información entre sistemas. El formato de este estándar está basado en texto para representar información estructurada: datos, documentos, configuración, etc.


#### Ejemplo 

```javascript
 		<pieza tipo="A">
    <nombre>Tornillo</nombre>
    <descripcion>Cilindro mecanico con una cabeza utilizado en la fijación temporal de unas piezas con otras 
    </descripcion>
    <caracateristica>
        <tipo>metal</tipo>
        <tamanyo>10</tamanyo>
    </caracateristica>
    <vacio></vacio>
</pieza>
```

##### JSON (JavaScript Object Notation) 
Este estándar esta mantenido por ECMAInternational y está basado en un subconjunto del lenguaje de programación JavaScript (ECMA-262).

#### Ejemplo 
```javascript
{
    “pieza”: {
        “tipo”: “A”
        “nombre”: “Tornillo”,
        “descripcion”: “Cilindro mecánico con una cabeza utilizado en la fijación temporal de unas piezas con otras”,
        “caracteristica”: {
            “tipo”: “metal”
            “tamanyo”: 10
        },
        “vacio”: “”
     }
}
```
 
##### 10.	 Explicar brevemente el estándar SOAP
SOAP (originalmente las siglas de Simple Object Access Protocol) es un protocolo estándar que define cómo dos objetos en diferentes procesos pueden comunicarse por medio de intercambio de datos XML. Este protocolo deriva de un protocolo creado por Dave Winer en 1998, llamado XML-RPC.
##### 11.	 Explicar brevemente el estándar REST Full
Es considerada una técnica de arquitectura de software, es decir, un conjunto de principios y patrones de comunicación que ayudan a crear una forma de pensar y construir las APIs. Este tipo de arquitectura se define por un conjunto de restricciones entre los elementos, componentes, conectores y datos usados
##### 12.	 ¿Qué son los headers en un request? 
Los headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc. La primera línea es la línea del request, que contiene su información básica (método HTTP, URL y versión).

##### 13.	¿Para qué se utiliza el key Content-type en un header?
Content-Type es la propiedad de cabecera (header) usada para indicar el media type (en-US) del recurso. Content-Type dice al cliente que tipo de contenido será retornado. En solicitudes (tales como POST o PUT ), el cliente indica al servidor que tipo de dato es enviado actualmente


###### ¿Qué diferencias se observan entre las llamadas el punto 1 y 3?
En el punto uno todavía no existía una respuesta, simplemente era la llamada de un valor determinado de la URL con la respuesta de los participantes anteriores 

En el 3er punto es la llamada de la respuesta ya incluida nuestra petición 
 
[![imagen 1](file:///C:/Users/win10/Downloads/Procontacto/index.html "imagen 1")](file:///C:/Users/win10/Downloads/Procontacto/index.html "imagen 1")
 
[![imagen 2](file:///C:/Users/win10/Downloads/Procontacto/imagen1.png "imagen 2")](http://file:///C:/Users/win10/Downloads/Procontacto/index.html "imagen 2")

[![imagen3](file:///C:/Users/win10/Downloads/Procontacto/imagen1.png "imagen3")](file:///C:/Users/win10/Downloads/Procontacto/imagen%203.png "imagen3")
 
qué datos almacenan en forma estándar y cómo se relacionan el resto (algunos no se relacionan entre sí) cada uno de los siguientes objetos de Salesforce:

 [![imagen4](file:///C:/Users/win10/Downloads/Procontacto/imagen%204.png "imagen4")](file:///C:/Users/win10/Downloads/Procontacto/index.html "imagen4")
 
## Soluciones de Salesforce
#### A.	¿Qué es Salesforce?

Salesforce es una solución de gestión de relaciones con clientes que une empresas y clientes. Es una plataforma CRM integrada que brinda a todos los departamentos, incluidos marketing, ventas, comercio y servicios, una vista única y compartida de cada cliente

#### B.	¿Qué es Sales Cloud?

Sales Cloud es un software de ventas y CRM que reúne la mayor parte de las funcionalidades encontradas en las demás plataformas. La gran ventaja es que, con un CRM de ventas, se puede aprovechar todos los recursos de automatización que necesite en una única plataforma

#### C.	¿Qué es Service Cloud?

Service Cloud de Salesforce es una de las soluciones de software de servicio al cliente más populares del mundo y la mejor calificada. Ya sea por teléfono, web, chatbot o correo electrónico, este software permite a los agentes conectarse con los clientes y resolver problemas rápidamente. Es la mejor forma de optimizar procesos y llamadas del equipo, reduciendo el tiempo promedio de servicio

#### D.	¿Qué es Health Cloud?

Health Cloud es una plataforma especialmente diseñada para la gestión clínica de pacientes por medio de tecnologías on-cloud, la cual ofrece: una comunicación más personalizado entre pacientes, miembros, proveedores y prestadores de servicios de salud, y un mejor ajuste a los procesos, servicios y datos médicos

#### E.	¿Qué es Marketing Cloud?

Es una plataforma de Salesforce que las pymes y grandes empresas pueden utilizar para invertir en estrategias de email marketing de nivel profesional. Y se utiliza para planificar personalizar y optimizar el recorrido de los clientes 

Funcionalidades de Salesforce
#### A.	¿Qué es un RecordType?

nos permiten definir diferentes Business Process, Pages Layouts y Picklist Values en un determinado objeto. Así mismo, los Record Types nos ayudan a mostrar distintos tipos de información según el perfil del usuario.
 
#### B.	¿Qué es un ReportType?
indica el tipo de informe al que pertenece la plantilla seleccionada previamente por el creador de la misma.
#### C.	¿Qué es un Page Layout?
Es el control del diseño y la originación de botones, campos, s-controls, visualforce,enlaces personalizados y listas relacionadas en páginas de registro de objetos
#### D.	¿Qué es un Compact Layout?
E un diseño compacto que muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail
#### E.	¿Qué es un Perfil?
Los perfiles se definen cómo los  accesos de los usuarios a objetos y datos que pueden realizar en la aplicación ya que cuando se crea un usuario este se asigna a un perfil cada uno 
#### F.	¿Qué es un Rol?
Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización.
G.	¿Qué es un Validation Rule?
Este verifica que los datos que un usuario ingresa en un registro cumplan con los estándares que se especifica antes de que el usuario pueda guardar el registro
#### H.	¿Qué diferencia hay entre una relación

Master Detail y Lookup?
Lookup: Se permiten hasta 25 para el objeto, Parent no es un campo obligatorio. Sin impacto en la seguridad y el acceso, Sin impacto en la eliminación, Puede tener varias capas de profundidad, El campo de búsqueda no es obligatorio.
Master Detail: La relación Master Detail es la relación padre-hijo. En el que el maestro representa al padre y el detalle representa al hijo. Si se elimina Parent, entonces Child también se elimina. Los campos de resumen acumulado solo se pueden crear en registros maestros que calcularán la SUMA, PROMEDIO, MIN de los registros secundarios.
#### I.	¿Qué es un Sandbox?
Es una copia de su organización en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación, las operaciones que realice en los entornos sandbox no afectan a la organización de producción de Salesforce. Y se pueden crear distintos entornos sanbox para la organización en función de las necesidades de almacenamiento 
#### JJ.	¿Qué es un ChangeSet?
Es un conjunto de cambios que se utilizan para personalizar de una organización de salesforce a otra, en este caso se puede probar un nuevo objeto en una organización de sandbox y luego enviarlo a su organización de producción mediante un conjunto de cambios 

 
#### K.	¿Para qué sirve el import Wizard de Salesforce?
Permite importar datos en objetos estándar comunes como, contactos, prospectos, cuentas y objetos personalizados, este permite importar hasta 50,000 registros al mismo tiempo y es una interfaz sencilla para especificar parámetros de configuración, fuentes de datos y asignaciones de campos.
#### L.	¿Para qué sirve la funcionalidad Web to Lead?
Sirve para capturar informacion de visitantes nuevos en un sitio web donde ingresan informacion de ellos mismos  y almacenar dicha informacion como un nuevo cliente potencial salesforce.
#### M.	¿Para qué sirve la funcionalidad Web to Case?
Se utiliza para recopilar consultas de asistencia y convertirlas automáticamente en casos y nos ayuda a responder con mayor rapidez lo que nos da una mayor productividad en un equipo de atención a clientes.
#### N.	¿Para qué sirve la funcionalidad Omnichannel?
Nos permite que los clientes se conecten sin problemas con su personal de soporte a través de múltiples canales y al mismo tiempo, estos agentes de soporte tienen acceso inmediato a una imagen holística de la persona a la que están a punto de ayudar. En pocas palabras es una herramienta de soporte que nos ayuda a relacionar tanto al cliente con soporte y soporte a una respuesta 
#### O.	¿Para qué sirve la funcionalidad Chatter?
Permite a los usuarios trabajar juntos, comunicarse y compartir información.
Chatter permite a los usuarios colaborar en oportunidades de ventas, casos de servicio, campañas y proyectos con aplicaciones integradas y acciones personalizadas.
 
### Conceptos generales
#### A.	¿Qué significa SaaS?
Software as a Service; Es una forma de poner a disposición softwares y soluciones de tecnología por medio de internet, como un servicio.
#### B.	¿Salesforce es Saas?
No, salesforce es una compañía de PaaS (plataforma como servicio), un concepto que nace como resultado de la aplicación al desarrollo de Software del modelo SaaS (Software como Servicio). Este modelo abarca el ciclo completo para desarrollar e implantar aplicaciones desde Internet.
#### C.	¿Qué significa que una solución sea Cloud?
Que es es una tecnología que permite acceso remoto a softwares, almacenamiento de archivos y procesamiento de datos por medio de Internet, siendo así, una alternativa a la ejecución en una computadora personal o servidor local
#### D.	¿Qué significa que una solución sea On-Premise?
Es el tipo de instalación de una solución de software. Esta instalación se lleva a cabo dentro del servidor y la infraestructura (TIC) de una empresa. Ya que Con el modelo on-premise, la empresa es la responsable de la seguridad, disponibilidad y gestión del software
#### E.	¿Qué es un pipeline de ventas?
Es el proceso de actividades y estrategias que necesita un vendedor para acelerar el ciclo de ventas, transformando clientes potenciales (aquellos que acaban de conocer tu marca o servicio) en clientes
#### F.	¿Qué es un funnel de ventas?
es la forma en que una empresa planea y establece procesos para ponerse en contacto con los diferentes usuarios y así llegar a cumplir un objetivo final, que bien puede ser la conversión de clientes, lograr un registro, cerrar una venta, entre otros.

#### G.	¿Qué significa Customer Experience?
También llamada experiencia del cliente o CX, es la experiencia que formará tu consumidor en función de sus interacciones con tu marca, que pueden ser positivas o negativas.
#### H.	¿Qué significa omnicanalidad?
Es una estrategia de comunicación utilizada para estar en contacto con los prospectos o clientes a través de diferentes canales (email, redes sociales, sitio web, etc.). El uso de los diferentes canales debe hacerse bajo una misma estrategia para llegar al consumidor en el momento indicado
#### I.	¿Qué significa que un negocio sea B2B?
Es un modelo de negocio que consiste en los servicios que una compañía entrega a otra con el objetivo de mejorar las ventas de los productos y bienes que ofrece. Es decir, una transacción comercial entre empresas
 
#### J.	¿Qué significa que un negocio sea B2C?
Es el acrónimo en inglés de “business to consumer” (empresa a consumidor). Es decir, es un modelo de negocio en el que una empresa le vende de forma directa al consumidor final. Este modelo es el de las empresas que ofrecen bienes y servicios de consumo masivo.
#### K.	¿Qué es un KPI?
conocido también como indicador clave o medidor de desempeño o indicador clave de rendimiento, es una medida del nivel del rendimiento de un proceso. El valor del indicador está directamente relacionado con un objetivo fijado previamente y normalmente se expresa en valores porcentuales.
#### L.	¿Qué es una API y en qué se diferencia de una Rest API?
Es una abreviatura de Application Programming Interfaces, que en español significa interfaz de programación de aplicaciones  este es un conjunto de subrutinas, funciones y procedimientos que ofrece cierta biblioteca para ser utilizada por otro software como una capa de abstracción.
Una API típica especifica cómo los componentes de software deben interactuar entre sí utilizando el protocolo web (HTTP) como intermediario. 
Las API's de REST suelen utilizar el protocolo de comunicación de la web (nuevamente, HTTP), pero no están limitadas de la misma manera que lo es un servicio web.
#### M.	¿Qué es un Proceso Batch?
Es la ejecución de un programa sin el control o supervisión directa del usuario que se denomina. Este tipo de programas se caracterizan porque su ejecución no precisa ningún tipo de interacción con el usuario

#### N.	¿Qué es Kanban?
Es un sistema de información que controla de modo armónico la fabricación de los productos necesarios en la cantidad y tiempo necesarios en cada uno de los procesos que tienen lugar tanto en el interior de la fábrica, como entre distintas empresas
#### O.	¿Qué es un ERP?
Son los sistemas de información gerenciales que integran y manejan muchos de los negocios asociados con las operaciones de producción y de los aspectos de distribución de una compañía en la producción de bienes o servicios
#### P.	¿Salesforce es un ERP?
Es un complemento a la plataforma mediante la conversión de los datos de la gestión de procesos desde el prospecto hasta el pedido de Salesforce CPQ en datos de transacciones



# [Mi avance (Salesforce)](http://https://trailblazer.me/id/jgarcia643  "Mi avance (Salesorce)")
[![salesforce](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.muycanal.com%2F2019%2F04%2F25%2Fel-origen-de-un-gigante-salesforce&psig=AOvVaw1ssI9EbiEa_rH9cHsdv-1D&ust=1645550862036000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCIi9muiokfYCFQAAAAAdAAAAABAD "salesforce")](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.muycanal.com%2F2019%2F04%2F25%2Fel-origen-de-un-gigante-salesforce&psig=AOvVaw1ssI9EbiEa_rH9cHsdv-1D&ust=1645550862036000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCIi9muiokfYCFQAAAAAdAAAAABAD "salesforce")


