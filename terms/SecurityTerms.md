# Términos de Seguridad de Nami

Última actualización: 1 de agosto del 2022.

### Definiciones.

- Las palabras ***`dependencia(s)`*** hacen referencia a todos los paquetes (código público que sirve para estructuración de datos ya presentes o para la agilización de datos) utilizados en las versiones anteriores o presentes de cualquiera de las apps de Nami.

- Las palabras ***`database(s)`*** hacen referencia a las 2 bases de datos que sirven para el funcionamiento continúo de Nami, ya sea Firebase como base de datos principales y real-time database como caché.

- Las palabras ***`algoritmo(s)`*** hacen referencia a toda la cadena de procesos que se utilizan para la agilización de datos de Nami, así como su seguridad.

- Estas definiciones son un complemento a las [definiciones de los Términos de Servicio de Nami](https://github.com/Kisu-s-fluff-workgroup/TerminosYCondicionesNami/blob/V0/terms/ServiceTerms.md#definiciones) por lo cual las definiciones del documento mencionado actúan como definiciones globales en todos los documentos presentes.

### Introducción
En este documento se hablará acerca de las estrategias de seguridad de Nami, así como diferentes sistemas para asegurar el correcto funcionamiento de todos los datos ya [sean públicos o confidenciales](https://github.com/Kisu-s-fluff-workgroup/TerminosYCondicionesNami/blob/V0/terms/ServiceTerms.md#52-entendiendo-que-son-los-datos-privados).

En este documento se explicará toda la política/revisiones de seguridad por las que pasa todo el sistema de Nami para hacer que luzca centrado, bonito y conciso.

Estos términos son un derivado de los [Términos de Servicio de Nami](https://github.com/Kisu-s-fluff-workgroup/TerminosYCondicionesNami/blob/V0/terms/ServiceTerms.md) por lo cual estos se acomodan a todos los criterios de disposiciones de propiedad, las renuncias de garantía, la indemnización y limitaciones de responsabilidad, así como se adapta a todas las limitaciones en cuanto al rompimiento de estos algoritmos de seguridad.

### 1. Nuestras tecnologías
##### 1.1 Encriptación de datos.
Nosotros al tratar de brindar la mayor seguridad al usuario brindamos diferentes capas de encriptación a en si los datos encriptados usando la tecnología `HS256` y firmado por [JWT](https://datatracker.ietf.org/doc/html/rfc7519) usando así la mayor seguridad de cifrado y con sus algoritmos criptográficos seguros se ofrece la mayor seguridad a los campos más sensibles de las tablas de los usuarios, así como a los servidores.

##### 1.2 Sistemas de seguridad contra inyecciones de código.
Nosotros, enfocándonos en la seguridad de los visitantes y usuarios de Nami, brindamos un sistema moderno que no admite la inyección de código.

##### 1.3 Autorización
Gracias a los modernos sistemas que tiene la API de Discord Inc., empezamos a brindar un sistema que funciona por medio de la autorización de Discord, así como un sistema de autorización que funciona por medio de una API de Nami, lo que hace que el sistema sea más seguro y más fácil de usar.

### 2. Tecnologías de terceros de seguridad
##### 2.1 La seguridad de nuestras *databases*
Nuestras bases de datos al ser hosteadas por terceros, estas siguen un [reglamento de seguridad](https://firebase.google.com/support/privacy) que nos obliga a cumplir con una serie de reglas de seguridad para que los datos sean seguros y no sean manipulados por terceros.

Además de adecuarnos a este reglamento, nosotros también brindamos un sistema de seguridad para que los datos sean seguros y no sean manipulados por terceros, usando la tecnología `HS256` y firmado por [JWT](https://datatracker.ietf.org/doc/html/rfc7519).

##### 2.2 La seguridad de nuestros *sitios webs*
Nuestros sitios webs, al ser hosteados directamente en servidores con control total y hosteados localmente por nosotros, brindamos toda la seguridad de poder brindar un soporte profesional y rápido en caso de falla, siguiendo las [Limitaciones de Responsabilidad de Nami y Descargos de Responsabilidad de Nami](https://github.com/Kisu-s-fluff-workgroup/TerminosYCondicionesNami/blob/V0/terms/ServiceTerms.md#8-limitaciones-de-responsabilidad).

Todos nuestros sitios webs están protegidos en su totalidad por [CloudFare](https://www.cloudflare.com) y se adecúan a sus sistemas de seguridad que realmente forman parte de la información confidencial de Nami.

##### 2.3 La seguridad de nuestras *dependencias*
Nosotros, estamos constamente enfocados en las brechas de seguridad de nuestras dependencias, así como en la seguridad de nuestros servicios, por lo cual nos esforzamos en brindar un sistema de seguridad que nos permita asegurar que nuestras dependencias sean seguras y no sean manipuladas por terceros.

Todo esto con un equipo que se encarga automáticamente de actualizar las dependencias de Nami, para que estas brechas de seguridad sean más fáciles de detectar y solucionar, todo esto usando el sistema de seguridad de Nami.
### 3. Descargos de responsabilidad en cuanto a Seguridad.
##### 3.1 Tú seguridad no es la misma que nuestra seguridad.
Nosotros nos comprometemos en brindar la mayor seguridad en nuestros servicios, pero nosotros no nos hacemos cargo si de alguna manera se tratan de romper los acuerdos de [Limitaciones de Software](https://github.com/Kisu-s-fluff-workgroup/TerminosYCondicionesNami/blob/V0/terms/ServiceTerms.md#31-restricciones-de-software) bajo herramientas de terceros u usando las herramientas de desarrollador del navegador web, por lo cual esto si se llega a presentar una queja, no tiene nada que ver con nosotros.

##### 3.2 En caso de infección de malware usando nuestros servicios.
El reporte será válido solo si el contenido es realmente del código interno de Nami, por lo cual el contenido puesto por terceros ya sean usuarios como se dice en la [cláusula de responsabilidad de contenido de los Términos de Servicio de Nami](https://github.com/Kisu-s-fluff-workgroup/TerminosYCondicionesNami/blob/V0/terms/ServiceTerms.md#el-contenido) cualquier contenido subido por usuarios, no será responsabilidad del staff de Nami.

La única acción pertinente que será hecha será la eliminación de la cuenta permanentemente del usuario que suba malware usando cualquiera de las apps de Nami.

Si el reporte cumple con las condiciones, este será reportado por medio de un ticket al staff, para que así puedan ayudar al usuario y darle una [indemnización](hhttps://github.com/Kisu-s-fluff-workgroup/TerminosYCondicionesNami/blob/V0/terms/ServiceTerms.md#indemnización) por todo el contenido dañado parcialmente o en su totalidad.

### 4. Conexión con los Términos de Servicio de Nami
##### 4.1 Las conexiones
Al brindar todos estos sistemas de seguridad se están cumpliendo y haciendo visibles todos los términos estipulados en los Términos de Servicio de Nami, y estos están ligados totalmente con los Términos de Servicio, por lo cual de manera inmutablemente y permanentemente, estos estan ligados con los Términos de Servicio de Nami.