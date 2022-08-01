# Términos de Seguridad de Nami

última actualización: 2 de Agosto del 2022.

### Definiciones.

- Las palabras ***`dependencia(s)`*** hacen referencia a todos los paquetes (código público que sirve para estructuración de datos ya presentes o para la agilización de datos) utilizados en las versiones anteriores o presentes de cualquiera de las apps de Nami.

- Las palabras ***`database(s)`*** hacen referencia a las 2 bases de datos que sirven para el funcionamiento continúo de Nami, ya sea firebase como base de datos principales y realtime dabatase como caché.

- Estas definiciones son un complemento a las [definiciones de los Términos de Servicio de Nami](https://github.com/Kisu-s-fluff-workgroup/TermsAndConditions/blob/V0/terms/service%20terms.md#definiciones) por lo cuál las definiciones del documento mencionado actúan como definiciones globales en todos los documentos presentes.

### Introducción
En este apartado se estará hablando acerca de la seguridad de Nami, así como diferentes estrategias para asegurar el correcto funcionamiento de todos los datos ya [sean públicos o confidenciales](https://github.com/Kisu-s-fluff-workgroup/TermsAndConditions/blob/V0/terms/service%20terms.md#52-entendiendo-que-son-los-datos-privados), usando la tecnología más actualizada para brindar la mayor seguridad a los usuarios en todo momento.

Para brindar mayor seguridad a los datos y a todos sus derivados se han implementado diferentes sistemas de seguridad a los que se explicará el como proteger los datos de la mejor manera y el como funciona el flujo de datos dentro de estas mismas apps.

Estos términos son un derivado de los [Términos de Servicio de Nami](https://github.com/Kisu-s-fluff-workgroup/TermsAndConditions/blob/V0/terms/service%20terms.md) por lo cual estos se acomodan a todos los criterios de disposiciones de propiedad, las renuncias de garantía, la indemnización y limitaciones de responsabilidad, así como se adapta a todas las limitaciones en cuanto al rompimiento de estos algoritmos de seguridad.

### 1. Nuestras tecnologías
##### 1.1 Encriptación de datos.
Nosotros al tratar de brindar la mayor seguridad al usuario brindamos diferentes capas de encriptación a en si los datos encriptados usando la tecnología `HS256` y firmado por [JWT](https://datatracker.ietf.org/doc/html/rfc7519) usando así la mayor seguridad de cifrado y con sus algoritmos criptograficos seguros se ofrece la mayor seguridad a los campos más sensibles de las tablas de los usuarios, así como a los servidores.

##### 1.2 Sistemas de seguridad contra injecciones de código.
Nosotros al estar concientes de todos los ataques por injecciones de código mediante campos del usuario, hemos implementado sistemas de seguridad en todos los formularios que representan algoritmos confidenciales de Nami, aparte de utilizar sistemas modernos que realmente no aceptan el uso de Inyección SQL.

##### 1.3 Autorización
Nosotros al estar tan pendientes de la seguridad hemos brindado un sistema de autenticación un 96% más seguro al usar la autenticación de Discord para brindar herramientas de autenticación, por lo cuál es imposible que puedan entrar a cualquier tipo de información de Nami sin tener acceso primero a cualquiera de las cuentas del staff de Nami.


### 2. Tecnologías de terceros de seguridad
##### 2.1 La seguridad de nuestras *databases*
Nuestras bases de datos al ser hosteadas por terceros, estas siguen un [reglamento de seguridad](https://firebase.google.com/support/privacy) muy estricto, al user firebase estas se adecúan a toda la seguridad HTTPS brindada por Google. Al igual de tener certificados y cada solicitud ser revisada por los sistemas de ReCaptchaV3 de Google. Por lo cuál cada petición tiene una forma aútentica de ser revisada con los mejores análisis de datos.

##### 2.2 La seguridad de nuestros *sitios webs*
Nuestros sitios webs, al ser hosteados directamente en servidores con control total y hosteados localmente por nosotros, brindamos toda la seguridad de poder brindar un soporte profesional y rápido en caso de falla, siguiendo las [Limitaciones de Responsabilidad de Nami y Descargos de Responsabilidad de Nami](https://github.com/Kisu-s-fluff-workgroup/TermsAndConditions/blob/V0/terms/service%20terms.md#8-limitaciones-de-responsabilidad).

Todos nuestros sitios webs estan protegidos en su totalidad por [CloudFare](https://www.cloudflare.com) y se adecúan a sus sistemas de seguridad que realmente forman parte de la información confidencial de Nami.

##### 2.3 La seguridad de nuestras *dependencias*

### 3. Descargos de responsabilidad en cuanto a Seguridad.
##### 3.1 Tú seguridad no es la misma que nuestra seguridad.
Nosotros nos comprometemos en brindar la mayor seguridad en nuestros servicios, pero nosotros no nos hacemos cargo si de alguna manera se tratan de romper los acuerdos de [Limitaciones de Software](https://github.com/Kisu-s-fluff-workgroup/TermsAndConditions/blob/V0/terms/service%20terms.md#31-restricciones-de-software) bajo herramientas de terceros u usando las herramientas de desarrollador del navegador web, por lo cuál esto si se llega a presentar una queja, no tiene nada que ver con nosotros.


##### 3.2 En caso de infección de malware usando nuestros servicios.
El reporte será válido solo si el contenido es realmente del código interno de Nami, por lo cuál el contenido puesto por terceros ya sean usuarios como se dice en la [claúsula de responsabilidad de contenido de los Términos de Servicio de Nami](https://github.com/Kisu-s-fluff-workgroup/TermsAndConditions/blob/V0/terms/service%20terms.md#el-contenido) cualquier contenido subido por usuarios, no será responsabilidad del staff de Nami.

La única acción pertinente que será hecha será la eliminación de la cuenta permanentemente del usuario que suba malware usando cualquiera de las apps de Nami.

Si el reporte cumple con las condiciones, este será reportado por medio de un ticket al staff, para que así puedan ayudar al usuario y darle una [indemnización](https://github.com/Kisu-s-fluff-workgroup/TermsAndConditions/blob/V0/terms/service%20terms.md#indemnización) por todo el contenido dañado parcialmente o en su totalidad.

### 4. Conexión con los Términos de Servicio de Nami
##### 4.1 Las conexiones
Al brindar todos estos sistemas de seguridad se estan cumpliendo y haciendo visibles todos los términos estipulados en los Términos de Servicio de Nami, y estos estan ligados totalmente con los Términos de Servicio.



