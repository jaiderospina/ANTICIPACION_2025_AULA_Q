# **TOP 8 :imp: CIBERATAQUES 2025**
Grupo MGOT 

## 1. PHISHING (MY. GÓMEZ)
Esto es un párrafo prueba, para escribir algo general introductorio.
Ejemplos de listas de opciones con chulito:
- [x] Primera tarea
- [ ] Segunda tarea
- [ ] Tercera tarea

### Descripción General:
Aquí se escribe un párrafo de máximo 3 líneas.
Ejemplos de textos: 
*Así es letra italic*  
_Otro ejempli de italic_
**Este texto estará en negrilla bold**  

### Mecanistmo de ataque:
Aquí se escribe un párrafo de máximo 3 líneas.
Ejemplo de código para tener en cuenta:
## Blocks of code

```
let message = 'PRUEBA DE CÓDIGO APACHE';
alert(message);
```

### IOC (Indicador de Compromiso)
Aquí se escribe un párrafo de máximo 3 líneas.
Ejemplo de tabla:
## Tables

| Left columns  | Right columns |
| ------------- |:-------------:|
| left foo      | right foo     |
| left bar      | right bar     |
| left baz      | right baz     |

### Estrategias de Mitigación:
Aquí se escribe un párrafo de máximo 3 líneas.
* Item 1
* Item 2
* Item 2a
* Item 2b
    * Item 3a
    * Item 3b

### Recursos:
Aquí se escribe un párrafo de máximo 3 líneas.
Ejemplo: Así se pueden poner links de internet así [Título de la noticia o página](https://www.eltiempo.com/tecnosfera/novedades-tecnologia/ciberataques-en-colombia-han-estado-aumentando-en-comparacion-con-el-2022-827595/).

Ejemplo de emojis así:
Me encanta tu sonrisa :smile:, pero eres más lento que una tortuga :turtle:
:satisfied:
:grin:
:cold_sweat:
:scream:

Aquí está el listado de códigos emojis: https://tutorialmarkdown.com/emojis

![Ejemplo de imagen desde un link externo](https://imagenes.eltiempo.com/files/image_1200_535/files/fp/uploads/2023/10/19/65314b395be1f.r_d.1143-406.jpeg)

***

## 2. RAMSOMWARE (MY. GÓMEZ)

***

## 3. DENIAL OF SERVICE (DOS) (MY. TORRES)
### Descripción General:
Ataque cibernético diseñado para “interrumpir el funcionamiento normal de un servidor, servicio o red” haciéndolo inoperable para sus usuarios legítimos. El objetivo principal de este ataque es “sobrecargar los recursos” del sistema objetivo (como ancho de banda, memoria o capacidad de procesamiento), haciendo que deje de responder o funcione de forma extremadamente lenta.
Ejemplos de textos: 
*Así es letra italic*  
_Otro ejempli de italic_
**Este texto estará en negrilla bold**  
asdf
## 4. MAN IN THE MIDDLE (MitM) (MY. TORRES)
### Descripción General:

***

## 5. SQL INJECTION  (MY. MILLAN)
### DESCRIPCIÓN GENERAL
La inyección de lenguaje de consulta estructurada (SQLi) es un ataque de inyección de código que permite al atacante recuperar, manipular o destruir información confidencial ubicada en bases de datos SQL. Estos ataques funcionan al insertar comandos especializados en campos de consulta SQL.
Cuando se ejecutan, los comandos pueden permitir al atacante suplantar la identidad de usuarios legítimos, ver o recuperar datos protegidos e incluso obtener acceso root a servidores.

### MECANISMO DE ATAQUE
1) Inyección SQL 
La inyección SQL es una debilidad en la seguridad web que podría permitir a un atacante cambiar las consultas SQL que se ejecutan en la base de datos.
2) Ataques de secuencias de comandos entre sitios (XSS)
El ataque de secuencias de comandos entre sitios, también conocido como XSS, permite a un atacante tomar el control de la forma en que los usuarios interactúan con una aplicación que es vulnerable a él.

### IOC (INDICADOR DE COMPROMISO)
Un indicador de compromiso (IoC) ante un ataque de SQL Injection puede manifestarse de diferentes formas, dependiendo del tipo de ataque y su propósito. Algunos ejemplos comunes incluyen:

1. Errores de base de datos visibles
Mensajes de error en las páginas web que revelan información sensible sobre la base de datos, como:
Versiones de SQL.
Nombres de tablas o columnas.
Detalles del motor de la base de datos.

2. Comportamiento anómalo en la aplicación
Respuestas inesperadas de la aplicación, como mostrar datos que no deberían ser accesibles.
Salto de autenticación: un atacante puede acceder a cuentas sin credenciales válidas.
Páginas con listados de datos no autorizados.

### ESTRATEGIAS DE MITIGACIÓN
Dentro de una aplicación, existen dos enfoques para la validación de entrada que pueden defenderse de los ataques de inyección SQL: listas negras y listas blancas. Con las listas negras, se eliminan o reemplazan caracteres maliciosos específicos y conocidos en la entrada del usuario.

### RECURSOS
1. Análisis de Logs del Servidor Web
Revisa los logs de tu servidor web (Apache, NGINX, IIS) para buscar patrones de ataque.
Palabras clave sospechosas:
' OR 1=1 --
UNION SELECT
DROP TABLE
INSERT INTO
Herramientas útiles para analizar logs:
GoAccess: Herramienta de análisis de logs en tiempo real.
ELK Stack (Elasticsearch, Logstash, Kibana): Para analizar grandes volúmenes de logs.

![Ejemplo de imagen desde un link externo]( https://miro.medium.com/v2/resize:fit:720/format:webp/1*rVA-dKOa7omxIQLYxRc1sw.gif) 

## 6. CROSS- SITE SCRIPTING  (XSS)  (MY. MILLAN)

### DESCRIPCIÓN GENERAL
Cross-site scripting (XSS) es un ataque informático que consiste en inyectar código malicioso en una página web o aplicación. El objetivo de este ataque es que el navegador del usuario ejecute el código malicioso y así obtener información privada. 
El XSS es uno de los ataques de seguridad más comunes en la web. Puede afectar a cualquier aplicación web, como sitios de comercio electrónico o redes sociales.

### MECANISMO DE ATAQUE
Fases del Mecanismo de Ataque XSS
Identificación de una vulnerabilidad XSS:
El atacante busca un punto en la aplicación web donde las entradas del usuario no sean correctamente validadas o sanitizadas.
Esto puede ocurrir en formularios, parámetros en URLs, cabeceras HTTP, comentarios, o cualquier otro punto donde se acepten datos del usuario.

### IOC (INDICADOR DE COMPROMISO)
1. Comportamiento anómalo en la aplicación web
Aparición de ventanas emergentes inesperadas
Cambios visuales no autorizados en la interfaz de usuario (redirecciones, formularios alterados, etc.).
Contenido inesperado cargado en la página, como scripts externos, imágenes o anuncios no legítimos.

2. Actividades sospechosas en los logs del servidor
Parámetros de entrada con contenido sospechoso:
Scripts inyectados: <script>alert('XSS')</script>
Uso de funciones como document.cookie, window.location, eval().
URLs con caracteres o patrones maliciosos:
%3Cscript%3E (versión codificada de <script>).

### ESTRATEGIAS DE MITIGACIÓN
Para mitigar un ataque Cross-Site Scripting (XSS) y prevenir futuras vulnerabilidades, se deben implementar estrategias robustas que abarcan la validación de entradas, codificación de salidas, uso de configuraciones de seguridad y herramientas especializadas.

1. Validación y Saneamiento de Entradas
La primera línea de defensa es verificar y limpiar todos los datos ingresados por los usuarios.
Prácticas clave:
Validar entradas en el lado del servidor y del cliente:
Define reglas estrictas para los datos aceptados (tamaño, tipo, formato).

Saneamiento de datos (Sanitization):
Escapa caracteres especiales que puedan interpretarse como código:
< → &lt;
> → &gt;
& → &amp;
' → &#39;
" → &quot;

### RECURSOS
1. Análisis de Logs
Los logs de tu servidor y aplicación son una de las primeras líneas para detectar ataques XSS.
Qué buscar:
Solicitudes HTTP sospechosas:
URLs con patrones maliciosos como <script>, document.cookie, window.location.
Parámetros codificados como %3Cscript%3E.

Herramientas recomendadas
GoAccess: Análisis en tiempo real de logs.
Graylog o ELK Stack (Elasticsearch, Logstash, Kibana): Para centralizar y analizar patrones de tráfico.


## 7 ZERO DAY EXPLOITS (MY. OBANDO)

### DESCRIPCIÓN GENERAL
Un zero day exploits o vulnerabilidad de día cero es un fallo de seguridad informática que nunca se había visto antes. Por lo general, un atacante sondea a un sistema hasta que descubre una vulnerabilidad.
MECANISMO DE ATAQUE
Un ataque de día cero se produce cuando los agentes maliciosos obtienen acceso a un sistema o red aprovechando una vulnerabilidad o debilidad de seguridad en un programa de software que el fabricante de este no conoce, lo que le deja “cero días” para solucionar el problema.

### IOC (INDICADOR DE COMPROMISO)
1.	Presencia de archivos ejecutables desconocidos o recientemente creados.
2.	Procesos en ejecución que no coinciden con los patrones normales del sistema.
3.	Modificaciones en archivos del sistema o registros sin autorización.

### ESTRATEGIAS DE MITIGACIÓN
Segmentación de Red y Acceso Controlado
1.	Microsegmentación: Divide la red en segmentos más pequeños para limitar la propagación de un ataque.
2.	Control de Acceso: Implementa el principio de menor privilegio, asegurándote de que usuarios y aplicaciones solo tengan los permisos estrictamente necesarios.
3.	Firewalls y ACLs: Configura reglas estrictas para controlar el tráfico entrante y saliente.

### RECURSOS
Sistemas de Monitoreo Avanzado
1.	EDR (Endpoint Detection and Response): Herramientas como:
2.	CrowdStrike Falcon
3.	Microsoft Defender for Endpoint
4.	Sentinel One Estas herramientas monitorizan el comportamiento de los endpoints en busca de actividades anómalas y técnicas de explotación


![Ejemplo de imagen desde un link externo]( https://www.pandasecurity.com/es/mediacenter/src/uploads/2015/10/zero-day-ataque-1024x413.jpg)

## 8 DNS SPOOFING (MY. OBANDO)

### DESCRIPCIÓN GENERAL
El DNS spoofing, o suplantación de DNS, es el proceso de alterar entradas en un servidor de DNS para redirigir a un usuario específico a una web malintencionada que está bajo control del atacante.
MECANISMO DE ATAQUE
Consiste en manipular la resolución DNS para redirigir a los usuarios hacia sitios web fraudulentos. 

### IOC (INDICADOR DE COMPROMISO)
1.	Respuestas DNS con direcciones IP desconocidas o que no coinciden con los registros esperados (por ejemplo, direcciones IP fuera del rango legítimo del proveedor de servicios).
2.	Múltiples respuestas a una consulta única (indicativo de posibles ataques de envenenamiento de caché).

### ESTRATEGIAS DE MITIGACIÓN
Implementar DNSSEC (Domain Name System Security Extensions)
1.	Qué hace: DNSSEC utiliza firmas digitales para garantizar la autenticidad y la integridad de las respuestas DNS, previniendo manipulaciones.
2.	Cómo implementarlo:

•	Habilita DNSSEC en tu servidor DNS autoritativo.
•	Asegúrate de que los clientes que consultan tu servidor soporten validación DNSSEC.

### RECURSOS
Estas herramientas te permiten analizar el tráfico DNS y detectar anomalías:
1.	Wireshark:
•	Captura y analiza el tráfico DNS en tiempo real.
•	Busca discrepancias entre las solicitudes DNS enviadas y las respuestas recibidas (por ejemplo, direcciones IP que no corresponden con los dominios legítimos).
2.	DNSQuerySniffer:
•	Monitorea y muestra consultas DNS realizadas por tu sistema.
•	Detecta consultas que devuelven IPs maliciosas o inesperadas.
3.	Fiddler o Burp Suite:
•	Analizan el tráfico de red y permiten inspeccionar si el tráfico está siendo redirigido a servidores no legítimos


![Ejemplo de imagen desde un link externo]( https://www.keyfactor.com/wp-content/uploads/HACKER-1.jpg)








