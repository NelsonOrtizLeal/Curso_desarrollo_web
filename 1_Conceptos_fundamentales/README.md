# Componentes de una pagina Web

## Indice
1. [El inicio](#el-inicio)
2. [Como funciona el internet](#como-funciona-el-internet)

--- 
### El inicio 

Una pagina `WEB` se compone esencialmente de un archivo `.HTML` este tipo de archivo es **OBLIGATORIO**  para tu sitio web, si no existe este archivo el navegador no mostrara tu pagina web.

Archivos que componen una pagina web:

- Archivo `.html` -> `index.html`
- Archivo `.js` -> `index.js`
- Archivo `.css` -> `style.css`
- Carpeta `assets/` -> `tu_proyecto/assets/img`

Cada tipo de archivo tiene una funcionalidad para la pagina web:

| Tipo de archivo | Funcionalidad |
|------------------|---------------|
| `.html`          | Estructura de la pagina web |
| `.js`            | Comportamiento de la pagina web |
| `.css`           | Estilo de la pagina web |
| `assets/`        | Recursos multimedia (imágenes, videos, etc.) |

Cada uno de estos archivos se relaciona entre si, por ejemplo el archivo `.html` puede hacer referencia a un archivo `.css` para aplicar estilos a los elementos de la pagina web, o a un archivo `.js` para agregar interactividad a la pagina web, el agregar `.js` a tu pagina web le puede dar dinamismo para que el usuario interactue con ella.

### Como funciona el internet

Alguna vez te has preguntado que sucede cuando entras a tu **navegador** y accedes a un sitio web como **you tube, facebook, instagram**.
Resulta que el internet funciona bajo una arquitectura llamada **Cliente y Servidor**.

Esta arquitectura se basa en que existen dos tipos de dispositivos clientes y servidores:

- Un `cliente` es cualquier dispositivo que puedes solicitar un recurso, o dicho de otra forma **un dispositivo que manda solicitudes a otros dispositivos**.
- Un `servidor` es ese dispositivo configurado y dedicado para que responda o ofresca a otros dispositivos la informacion, valores, archivos, documentos, etc.

Sin embargo un dispositivo puede ser `cliente` y `servidor` al mismo tiempo o intercambiar los roles cuando sea necesario. Para identificarlos solo debes preguntar, `Quien esta solicitando la informacion y quien esta respondiendo`.

Ahora bien, estos dispositivos se deben comunicar, deben tener un lenguaje en comun para que se puedan preguntar y responder, este lenguaje es el **Protocolo de Transferencia de Hipertexto (HTTP)**, este protocolo define las reglas y convenciones para la comunicacion entre dispositivos en la web.

Ya tenemos el idioma/lenguaje que utilizan para comunicarse entre dispositivos, ahora se necesita algun `medio` o `canal` por el cual se puedan comunicar, este `canal` es el `internet`.

> El internet esta compuesto de multiples `protoloces` y capas de comunicacion, via la red.

Significa que nuestro dispositivo esta conectado o interconectado en una red virtual en la que millones de computadoras estan solicitando y compartiendo informacion, un mundo virtual donde hay servidores y clientes.

Para que nuestro dispositivo sepa a que servidor pedirle el recurso, necesitamos tener alguna forma de identificar, es decir debe existar una manera de saber la direccion de la maquina a la que te quieres conectar. Para que todas las computadoras se puedan identificar y puedan saber a cual de millones de computadoras debe dirigirse es que existe el protocolo **IP** (Protocolo de internet/Internet Protocol), este protocolo te indentifica a que computadora o  **router** te quieres conectar, se menciona router porque es el dispositivo al cual conectas tu computadora para acceder al internet.

> Utiliza el siguiente comando en tu CMD, para saber la IP de algún sitio web:
>
> ```cmd
> ping www.google.com
> ```
>
> Esto te devolverá la IP en la cual se encuentra el sitio.

Ahora bien, que un humano pueda recordar la `IP` es muy complicado, por lo que se invento un sistema de nombres de dominio, es decir en lugar de recordar la `IP` 123.456.789.000, podemos recordar un nombre mas amigable como `www.google.com`, este nombre es mas facil de recordar y es lo que conocemos como `URL` (Localizador Uniforme de Recursos) y los servidores de nombres de dominio `(DNS)` se encargan de traducir estos nombres amigables a direcciones IP que las computadoras pueden entender.
La forma en que se utilizar un DNS es parecido a como se utilizaba la seccion amarilla de telfonos, la cual era un directorio de nombres de personas y numeros.
