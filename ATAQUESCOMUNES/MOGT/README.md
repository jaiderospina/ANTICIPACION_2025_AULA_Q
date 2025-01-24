# **TOP 8 :imp: CIBERATAQUES 2025**
![EQUIPO DE HACKING ÉTICO MGOT](https://files.oaiusercontent.com/file-SGU3EmbjtgH4VqC4GC5LQk?se=2025-01-24T23%3A15%3A31Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D0f1dc602-7ab8-4eb6-80ad-26905f89b677.webp&sig=%2Bz4iHDxrnqFzB1rHPem0c/aQs6u9SwHlLLq%2B6pNG2Qk%3D)

Grupo MGOT 

MY. MARIO GÓMEZ

MY. LUIS MILLÁN

MY. DANIEL TORRES

MY. YEFERSON OBANDO

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
![Ataque DOS](https://grupogaratu.com/wp-content/uploads/sites/4/2018/08/ataque-dos-ddos-seguridad-empresa-ciberseguridad-e1535478792912.jpg)

### DESCRIPCIÓN GENERAL
Ataque cibernético diseñado para “interrumpir el funcionamiento normal de un servidor, servicio o red” haciéndolo inoperable para sus usuarios legítimos. El objetivo principal de este ataque es “sobrecargar los recursos” del sistema objetivo (como ancho de banda, memoria o capacidad de procesamiento), haciendo que deje de responder o funcione de forma extremadamente lenta.

### MECANISMO DE ATAQUE
El atacante envía “grandes volúmenes de tráfico o solicitudes maliciosas” al sistema objetivo, superando su capacidad para gestionarlas. Esto puede provocar:
1.	Saturación de recursos: Como el ancho de banda o la CPU.
2.	Interrupción del servicio: El sistema no puede procesar solicitudes legítimas.
3.	Desconexión temporal: El sistema puede colapsar por completo.

### IOC (INDICADOR DE COMPROMISO)
Los Indicadores de Compromiso (IoCs) de un ataque DoS (Denial of Service) son señales o evidencias que indican que un sistema está siendo víctima de un ataque de denegación de servicio. Estos indicadores pueden detectarse en registros de red, métricas del sistema o monitoreo de aplicaciones.

### ESTRATEGIAS DE MITIGACIÓN
1. Estrategias Técnicas
1.1 Uso de Firewalls y Sistemas de Detección
1.2 Implementar Servicios Anti-DDoS
1.3 Tasa de Limitación (Rate Limiting)
1.4 Filtrado de Tráfico
1.5 Balanceo de Carga
1.6 Escalabilidad en la Infraestructura
1.7 Validación de Solicitudes

2. Estrategias Operativas
2.1 Monitoreo Proactivo
2.2 Respuesta Rápida a Incidentes
2.3 Colaboración con Proveedores de Servicios
2.4 Segmentación de Redes
   
4. Estrategias Preventivas
3.1 Pruebas de Resiliencia
3.2 Fortalecer la Infraestructura DNS
3.3 Mantener el Software Actualizado
3.4 Uso de Redes de Entrega de Contenidos (CDN)

5. Estrategias a Nivel de Aplicación
5.1 Validación de Entradas
5.2 Configuración de Timeouts
5.3 Restricción de Recursos

### RECURSOS
![GitHub](https://foundations.projectpythia.org/_images/GitHub-logo.png)

https://github.com/thehackingsage/ddos/tree/master/Protection%20Tools



## 4. MAN IN THE MIDDLE (MitM) (MY. TORRES)

![MITM](https://beaglesecurity.com/blog/images/man-in-the-middle-attacks.webp)

### DESCRIPCIÓN GENERAL
Un ataque Man-in-the-Middle (MitM) ocurre cuando un atacante intercepta, modifica o manipula la comunicación entre dos partes (por ejemplo, un usuario y un servidor) sin que estas lo sepan. Su objetivo principal es robar información sensible como contraseñas, datos financieros o identidades, o alterar los datos transmitidos.

### MECANISMO DE ATAQUE

Intercepción:
•	El atacante se posiciona entre el usuario y el servidor.
•	Métodos comunes: red Wi-Fi pública no segura, redirección de DNS o ARP Spoofing.

Suplantación:
•	El atacante finge ser una de las partes legítimas para capturar datos.

Manipulación de datos:
•	Puede alterar o inyectar contenido en la comunicación interceptada.

### IOC (INDICADOR DE COMPROMISO)
Conexiones inseguras:
•	Comunicación a través de HTTP en lugar de HTTPS.
•	Certificados SSL inválidos o inexistentes.

Anomalías en la red:
•	Direcciones IP desconocidas o sospechosas en las tablas ARP.
•	Latencia inusual en las comunicaciones.

Mensajes de advertencia:
•	Alertas en navegadores sobre conexiones no seguras.
•	Certificados digitales autofirmados o caducados.

Tráfico inesperado:
•	Paquetes de red con direcciones IP falsificadas o múltiples retransmisiones.

### ESTRATEGIAS DE MITIGACIÓN
1.	Uso de cifrado:
o	Implementar HTTPS y TLS para proteger las comunicaciones.
o	Configurar VPN para garantizar un canal seguro.
2.	Concienciación del usuario:
o	Evitar redes Wi-Fi públicas no seguras sin protección adicional.
o	Verificar manualmente la legitimidad de los certificados digitales.
3.	Implementación de autenticación robusta:
o	Autenticación multifactor (MFA) para reducir el impacto del robo de credenciales.
o	Firmas digitales para garantizar la integridad de los datos.
4.	Seguridad de la red:
o	Configurar detección de anomalías con sistemas IDS/IPS.
o	Habilitar protocolos seguros como DNSSEC para evitar redirecciones maliciosas.
5.	Monitoreo continuo:
o	Analizar registros de tráfico y patrones anómalos.
o	Revisar y actualizar certificados SSL regularmente.

### RECURSOS
![MITM](https://img-c.udemycdn.com/course/750x422/1969416_1f51_7.jpg)

https://github.com/byt3bl33d3r/MITMf
https://github.com/jtesta/ssh-mitm
https://github.com/LionSec/xerosploit

### :imp::imp::imp::imp::imp:CONOCE UN POCO MÁS SOBRE ATAQUES DDOS...............



![PING DE LA MUERTE](https://www.ionos.mx/digitalguide/fileadmin/DigitalGuide/Schaubilder/ping-de-la-muerte.png)


## ¿Qué es un ataque de ping de la muerte (PoD)?

Un ataque de ping de muerte (PoD) es una forma de ataque DDoS en el que un atacante envía al equipo receptor solicitudes de ping simples como paquetes de IP fragmentados que son demasiado grandes o tienen un formato incorrecto. Estos paquetes no se adhieren al formato del paquete IP cuando se vuelven a ensamblar, lo que genera errores de almacenamiento dinámico/memoria y bloqueos del sistema.

Las solicitudes de ping del protocolo de mensajes de control de Internet (ICMP) se utilizan para comprobar la conectividad y el estado de los equipos de red. En un ping ICMP legítimo, el equipo receptor responde a una solicitud de eco ICMP. La respuesta indica la salud del destinatario. Enviar una solicitud de ping con un encabezado mayor a 65,535 bytes viola el Protocolo de Internet.

## ¿Cómo funciona un ataque de ping de muerte?

Una vez que el equipo destinatario vuelve a ensamblar la solicitud de ping (con sus paquetes de IP fragmentados), esto puede dar como resultado un tamaño de solicitud de IP superior a 65,535 bytes, lo que puede provocar fallas en el sistema. Los bloqueos son causados por errores de almacenamiento dinámico/memoria debido al desbordamiento de los búferes asignados para volver a ensamblar los encabezados y el cuerpo de IP.

Aunque PoD es un ataque DDoS heredado y los ataques de inundación ICMP se usan con más frecuencia, PoD aún puede afectar los sistemas sin parches. Se han descubierto vulnerabilidades a PoD recientemente en 2018 en equipos Apple que usaban un kernel XNU sin parches. Esto provocó desbordamientos de montículo y los hizo susceptibles a la ejecución remota de código.


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

![Ejemplo de imagen desde un link externo]( https://gogetsecure.com/wp-content/uploads/2023/03/cross-site-scripting-xss.jpg)


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








