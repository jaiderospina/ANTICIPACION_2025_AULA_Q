# **TOP 8 :imp: CIBERATAQUES 2025**
![EQUIPO DE HACKING ÉTICO MGOT](https://media.licdn.com/dms/image/v2/D4E12AQGtgZUaecTDtg/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1704959664316?e=2147483647&v=beta&t=PovZR5gg6Mznz1sZ-ErCfzXwaOfQl0qAr_ZpUeM_YBM)

Grupo **MGOT** Aula "Q".

En el siguiente ejercicio se destacarán los 8 principales ciberataques según el SISAP*, para lo cual se tratará cada uno en particular, su descripción general, mecanismo de ataque, indicador de compromiso IOC, estrategia de mitigación y recursos.

- [X] MY. MARIO GÓMEZ
- [X] MY. DANIEL TORRES
- [X] MY. LUIS MILLÁN
- [X] MY. YEFERSON OBANDO

***

## 1. PHISHING
_El phishing es un tipo de ciberataque que utiliza correos electrónicos, mensajes de texto, llamadas telefónicas o sitios web fraudulentos para engañar a las personas y hacer que compartan datos confidenciales, descarguen malware o se expongan de otro modo a la ciberdelincuencia_
![Phising](https://imagenes.eltiempo.com/files/image_1200_535/files/fp/uploads/2023/10/19/65314b395be1f.r_d.1143-406.jpeg)

### 1.1 DESCRIPCIÓN GENERAL:
Los ataques de phishing son una forma de ingeniería social. A diferencia de otros ciberataques que se dirigen directamente a redes y recursos, los ataques de ingeniería social utilizan errores humanos, historias falsas y tácticas de presión para manipular a las víctimas para que se perjudiquen involuntariamente a sí mismas o a sus organizaciones. 

En un intento típico de phishing, un hacker se hace pasar por alguien en quien la víctima confía, como un compañero, jefe, figura de autoridad o representante de una marca conocida. El hacker envía un mensaje a la víctima para que pague una factura, abra un archivo adjunto, haga clic en un enlace o realice cualquier otra acción.

*Al confiar en la supuesta fuente del mensaje, el usuario sigue las instrucciones y cae de lleno en la trampa del estafador. Esa "factura" puede llevar directamente a la cuenta de un hacker. Ese archivo adjunto podría instalar ransomware en el dispositivo del usuario. Ese enlace podría llevar al usuario a un sitio web que roba números de tarjetas de crédito, números de cuentas bancarias, credenciales de inicio de sesión u otros datos personales.*

### 1.2 MECANISMOS DE ATAQUE:

   * Correos electrónicos fraudulentos:
Los atacantes envían correos con enlaces o archivos adjuntos maliciosos diseñados para robar información o instalar malware.
   * Páginas web falsas:
Sitios que imitan páginas legítimas para capturar credenciales o datos confidenciales.
   * Mensajes de texto y llamadas (smishing y vishing):
En el caso de smishing, mensajes de texto engañosos; vishing implica llamadas telefónicas para obtener datos personales.
   * Ataques dirigidos (spear phishing):
Personalización de mensajes para atacar objetivos específicos, como empleados de alto nivel o departamentos clave.
   * Pharming:
Manipulación del sistema DNS o del dispositivo de la víctima para redirigirla a un sitio falso sin que lo perciba.
   * Uso de ingeniería social:
Aprovechan el comportamiento humano, como la confianza o el miedo, para persuadir a las víctimas a actuar de forma apresurada.

### 1.3 IOC (INDICADORES DE COMPROMISO)

| IOC  | Explicación |
| ------------- |:-------------:|
| 1. Correos electrónicos sospechosos      | Errores gramaticales, direcciones de remitente inusuales, nombres de dominio similares pero no exactos (ejemplo @ seguro-banco.com en lugar de ejemplo @ banco.com)     |
| 2. URLs maliciosas      | Enlaces acortados o que no coinciden con la URL oficial de la entidad legítima.     |
| 3. Archivos adjuntos      | Documentos o archivos con extensiones dobles (documento.pdf.exe) o inusuales.     |
| 4. Redirecciones no autorizadas      | Navegadores que llevan a sitios desconocidos sin intervención del usuario.     |
| 5. Actividad inusual      | Inicios de sesión desde ubicaciones o dispositivos no reconocidos.     |
| 6. Anomalías en sistemas      | Instalación de malware, cambios no autorizados en la configuración o comunicaciones inusuales hacia servidores externos.     |

### 1.4 ESTRATEGIAS DE MITIGACIÓN:

   * Concienciación y capacitación:
Entrenar a los empleados para reconocer correos electrónicos sospechosos, verificar enlaces y no compartir información confidencial sin validar la autenticidad.
   * Autenticación multifactor (MFA):
Añadir una capa adicional de seguridad para impedir accesos no autorizados incluso si las credenciales son comprometidas.
   * Filtrado de correo electrónico:
Implementar herramientas de detección de spam y análisis de enlaces y archivos adjuntos maliciosos.
   * Análisis de tráfico de red:
Supervisar el tráfico en busca de conexiones hacia dominios conocidos como maliciosos.
   * Políticas de acceso restrictivas:
Limitar privilegios y aplicar el principio de menor privilegio (PoLP) en sistemas y aplicaciones.
   * Simulaciones de phishing:
Realizar pruebas periódicas para medir la resiliencia de los empleados frente a ataques.
   * Actualización de software y parches:
Mantener sistemas actualizados para proteger contra vulnerabilidades conocidas.
   * Seguridad en DNS:
Implementar DNS seguro y autenticación de correo como SPF, DKIM y DMARC.

### 1.5 RECURSOS:
* Herramientas de análisis de phishing:
   * PhishTank para verificar URLs sospechosas.
   * VirusTotal para analizar enlaces y archivos adjuntos.
* Informes de incidentes:
Contactar a equipos de respuesta a incidentes como CERTs (Computer Emergency Response Teams) nacionales.
* Políticas y normativas:
Cumplir con estándares de seguridad como ISO 27001, GDPR, o NIST para gestionar riesgos de phishing.
* Soluciones tecnológicas:
   * SIEM (Security Information and Event Management): Para correlacionar eventos relacionados con phishing.
   * EDR (Endpoint Detection and Response): Para responder a incidentes en dispositivos afectados.


***

## 2. RAMSOMWARE
El ransomware es un tipo de malware que retiene como rehenes los datos confidenciales o el dispositivo de una víctima, amenazando con mantenerlos bloqueados, o algo peor, a menos que la víctima pague un rescate al atacante.
![Ramsomeware](https://www.redseguridad.com/wp-content/uploads/sites/2/2021/09/pago-ransomware-malware-.jpg)

### 2.1 DESCRIPCIÓN GENERAL:
El ransomware es un tipo de malware que cifra los archivos de una víctima o bloquea el acceso a su sistema, exigiendo un pago (usualmente en criptomonedas) a cambio de restaurar el acceso a los datos. Es una de las amenazas más destructivas y de rápido crecimiento en la ciberseguridad, ya que no solo afecta a individuos, sino también a organizaciones, gobiernos y servicios críticos. A menudo, los atacantes envían un mensaje de rescate que incluye instrucciones para pagar el "rescate", mientras advierten de las consecuencias de no hacerlo.

### 2.2 MECANISMOS DE ATAQUE:
* Phishing:
El ransomware suele distribuirse a través de correos electrónicos de phishing que contienen enlaces maliciosos o archivos adjuntos infectados, como documentos de Office con macros maliciosas o archivos comprimidos que ejecutan el ransomware al abrirlos.
* Exploits de vulnerabilidades:
Los atacantes aprovechan vulnerabilidades no parcheadas en sistemas operativos, software de terceros o aplicaciones, como los famosos ataques de EternalBlue (exploitable en SMB de Windows) que fueron utilizados en el ataque de WannaCry.
* Redirección de tráfico y sitios comprometidos:
Algunos tipos de ransomware utilizan sitios web comprometidos o anuncios maliciosos (malvertising) para infectar a los usuarios al visitar una página legítima.
* Acceso remoto:
Uso de credenciales robadas o fuerza bruta para obtener acceso a servidores y dispositivos, lo que permite a los atacantes ejecutar el ransomware manualmente o de manera automatizada.
* Ransomware como servicio (RaaS):
Plataformas en línea donde los cibercriminales pueden alquilar ransomware preempaquetado y usarlo para lanzar ataques sin tener que ser expertos técnicos. El ataque se comparte entre el creador del ransomware y el atacante.
* Movimiento lateral:
Después de infectar un sistema, los atacantes a menudo se desplazan por la red para infectar más dispositivos, lo que permite un mayor alcance y la oportunidad de cifrar más datos.


### 2.3 IOC (INDICADORES DE COMPROMISO)

| IOC  | Descripción |
| ------------- |:-------------:|
| 1. Archivos cifrados      | Archivos con extensiones desconocidas o de una extensión característica de ransomware, como .locked, .encrypted, .crypt, .zip, entre otras.     |
| 2. Comportamientos de cifrado      | Actividad en el sistema como procesos que intentan cifrar una gran cantidad de archivos, especialmente aquellos de alto valor como documentos y bases de datos.     |
| 3. Archivos de rescate      | Archivos que contienen mensajes de rescate como "README.txt", "DECRYPT_INSTRUCTION.txt", o archivos con el nombre de los atacantes y cómo contactar para el pago.     |
| 4. Comunicaciones maliciosas      | Rastrear tráfico hacia servidores de comando y control (C&C) del atacante o direcciones IP relacionadas con las demandas de rescate o pagos.     |
| 5. Fallas de acceso al sistema      | Sistemas que muestran mensajes de "acceso denegado" o muestran información sobre el cifrado de archivos, así como cambios inesperados en permisos de archivos y configuraciones del sistema.     |
| 6. Archivos de registros anómalos      | Registros de eventos que indican la ejecución de scripts, ejecución de comandos inusuales o cambios de permisos en los sistemas de archivos.     |

### 2.4 ESTRATEGIAS DE MITIGACIÓN:
* Respaldo regular de datos.
* Parches y actualizaciones constantes:
* Segmentación de redes.
* Autenticación multifactor (MFA).
* Filtrado de correos electrónicos y URLs.
* Educación y concienciación del personal.
* Monitoreo continuo y análisis forense.
* Restricción de privilegios de ejecución.
* Deshabilitar SMBv1.
* Plan de respuesta a incidentes (IR).

### 2. 5 RECURSOS:
1. Herramientas de desencriptación:
  * No More Ransom es una iniciativa que ofrece herramientas de desencriptación gratuitas para varias familias de ransomware.
  * ID Ransomware permite identificar el tipo de ransomware y proporcionar recursos de desencriptación.
2. Antivirus y soluciones EDR (Endpoint Detection and Response):
  * Soluciones como CrowdStrike, Sophos, Bitdefender, y Kaspersky ofrecen protección contra ransomware mediante la detección proactiva y la remediación de los sistemas comprometidos.
3. Plataformas de respaldo en la nube:
  * Usar servicios de almacenamiento en la nube como Google Drive, Dropbox o soluciones especializadas como Veeam o Acronis para mantener copias de seguridad de los datos de forma segura.
4. Plataformas de monitoreo y SIEM:
  * Herramientas como Splunk, LogRhythm, o AlienVault proporcionan capacidades avanzadas de monitoreo y análisis de seguridad, lo que facilita la detección temprana de ransomware.
5. Certificados de seguridad:
  * Mantener certificados SSL/TLS válidos y configurar servidores web de manera segura, así como verificar los protocolos de autenticación y encriptación en todas las comunicaciones.

![Ejemplo de imagen desde un link externo](https://upload.wikimedia.org/wikipedia/commons/d/d9/Goldeneye-ransomware-161212.jpg)


***

## 3. DENIAL OF SERVICE (DOS)
![Ataque DOS](https://grupogaratu.com/wp-content/uploads/sites/4/2018/08/ataque-dos-ddos-seguridad-empresa-ciberseguridad-e1535478792912.jpg)

### 3.1 DESCRIPCIÓN GENERAL:
Ataque cibernético diseñado para “interrumpir el funcionamiento normal de un servidor, servicio o red” haciéndolo inoperable para sus usuarios legítimos. El objetivo principal de este ataque es “sobrecargar los recursos” del sistema objetivo (como ancho de banda, memoria o capacidad de procesamiento), haciendo que deje de responder o funcione de forma extremadamente lenta.

### 3.2 MECANISMOS DE ATAQUE
El atacante envía “grandes volúmenes de tráfico o solicitudes maliciosas” al sistema objetivo, superando su capacidad para gestionarlas. Esto puede provocar:
1.	Saturación de recursos: Como el ancho de banda o la CPU.
2.	Interrupción del servicio: El sistema no puede procesar solicitudes legítimas.
3.	Desconexión temporal: El sistema puede colapsar por completo.

### 3.3 IOC (INDICADORES DE COMPROMISO)
Los Indicadores de Compromiso (IoCs) de un ataque DoS (Denial of Service) son señales o evidencias que indican que un sistema está siendo víctima de un ataque de denegación de servicio. Estos indicadores pueden detectarse en registros de red, métricas del sistema o monitoreo de aplicaciones.

### 3.4 ESTRATEGIAS DE MITIGACIÓN:

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
   
3. Estrategias Preventivas
3.1 Pruebas de Resiliencia
3.2 Fortalecer la Infraestructura DNS
3.3 Mantener el Software Actualizado
3.4 Uso de Redes de Entrega de Contenidos (CDN)

4. Estrategias a Nivel de Aplicación
4.1 Validación de Entradas
4.2 Configuración de Timeouts
4.3 Restricción de Recursos

### 3.5 RECURSOS
![GitHub](https://foundations.projectpythia.org/_images/GitHub-logo.png)

https://github.com/thehackingsage/ddos/tree/master/Protection%20Tools


## 4. MAN IN THE MIDDLE (MitM)

![MITM](https://beaglesecurity.com/blog/images/man-in-the-middle-attacks.webp)

### 4.1 DESCRIPCIÓN GENERAL
Un ataque Man-in-the-Middle (MitM) ocurre cuando un atacante intercepta, modifica o manipula la comunicación entre dos partes (por ejemplo, un usuario y un servidor) sin que estas lo sepan. Su objetivo principal es robar información sensible como contraseñas, datos financieros o identidades, o alterar los datos transmitidos.

### 4.2 MECANISMOS DE ATAQUE

Intercepción:
•	El atacante se posiciona entre el usuario y el servidor.
•	Métodos comunes: red Wi-Fi pública no segura, redirección de DNS o ARP Spoofing.

Suplantación:
•	El atacante finge ser una de las partes legítimas para capturar datos.

Manipulación de datos:
•	Puede alterar o inyectar contenido en la comunicación interceptada.

### 4.3 IOC (INDICADORES DE COMPROMISO)
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

### 4.4 ESTRATEGIAS DE MITIGACIÓN
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

### 4.5 RECURSOS
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

## 5. SQL INJECTION

### 5.1 DESCRIPCIÓN GENERAL
La inyección de lenguaje de consulta estructurada (SQLi) es un ataque de inyección de código que permite al atacante recuperar, manipular o destruir información confidencial ubicada en bases de datos SQL. Estos ataques funcionan al insertar comandos especializados en campos de consulta SQL.
Cuando se ejecutan, los comandos pueden permitir al atacante suplantar la identidad de usuarios legítimos, ver o recuperar datos protegidos e incluso obtener acceso root a servidores.

### 5.2 MECANISMOS DE ATAQUE
1) Inyección SQL 
La inyección SQL es una debilidad en la seguridad web que podría permitir a un atacante cambiar las consultas SQL que se ejecutan en la base de datos.
2) Ataques de secuencias de comandos entre sitios (XSS)
El ataque de secuencias de comandos entre sitios, también conocido como XSS, permite a un atacante tomar el control de la forma en que los usuarios interactúan con una aplicación que es vulnerable a él.

### 5.3 IOC (INDICADORES DE COMPROMISO)
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

### 5.4 ESTRATEGIAS DE MITIGACIÓN
Dentro de una aplicación, existen dos enfoques para la validación de entrada que pueden defenderse de los ataques de inyección SQL: listas negras y listas blancas. Con las listas negras, se eliminan o reemplazan caracteres maliciosos específicos y conocidos en la entrada del usuario.

### 5.5 RECURSOS
Análisis de Logs del Servidor Web
Revisa los logs de tu servidor web (Apache, NGINX, IIS) para buscar patrones de ataque.
Palabras clave sospechosas:
```
' OR 1=1 --
UNION SELECT
DROP TABLE
INSERT INTO
```
Herramientas útiles para analizar logs:
GoAccess: Herramienta de análisis de logs en tiempo real.
ELK Stack (Elasticsearch, Logstash, Kibana): Para analizar grandes volúmenes de logs.

![Ejemplo de imagen desde un link externo]( https://miro.medium.com/v2/resize:fit:720/format:webp/1*rVA-dKOa7omxIQLYxRc1sw.gif) 


***

## 6. CROSS - SITE SCRIPTING  (XSS)

### 6.1 DESCRIPCIÓN GENERAL
Cross-site scripting (XSS) es un ataque informático que consiste en inyectar código malicioso en una página web o aplicación. El objetivo de este ataque es que el navegador del usuario ejecute el código malicioso y así obtener información privada. 
El XSS es uno de los ataques de seguridad más comunes en la web. Puede afectar a cualquier aplicación web, como sitios de comercio electrónico o redes sociales.

### 6.2 MECANISMOS DE ATAQUE
Fases del Mecanismo de Ataque XSS
Identificación de una vulnerabilidad XSS:
El atacante busca un punto en la aplicación web donde las entradas del usuario no sean correctamente validadas o sanitizadas.
Esto puede ocurrir en formularios, parámetros en URLs, cabeceras HTTP, comentarios, o cualquier otro punto donde se acepten datos del usuario.

### 6.3 IOC (INDICADORES DE COMPROMISO)
1. Comportamiento anómalo en la aplicación web
Aparición de ventanas emergentes inesperadas
Cambios visuales no autorizados en la interfaz de usuario (redirecciones, formularios alterados, etc.).
Contenido inesperado cargado en la página, como scripts externos, imágenes o anuncios no legítimos.

2. Actividades sospechosas en los logs del servidor
Parámetros de entrada con contenido sospechoso:
Scripts inyectados:
```
<script>alert('XSS')</script>
```
Uso de funciones como 
```
document.cookie
window.location
eval()
```
URLs con caracteres o patrones maliciosos:
```
%3Cscript%3E (versión codificada de <script>).
```

### 6.4 ESTRATEGIAS DE MITIGACIÓN
Para mitigar un ataque Cross-Site Scripting (XSS) y prevenir futuras vulnerabilidades, se deben implementar estrategias robustas que abarcan la validación de entradas, codificación de salidas, uso de configuraciones de seguridad y herramientas especializadas.

1. Validación y Saneamiento de Entradas
La primera línea de defensa es verificar y limpiar todos los datos ingresados por los usuarios.
Prácticas clave:
Validar entradas en el lado del servidor y del cliente:
Define reglas estrictas para los datos aceptados (tamaño, tipo, formato).

2. Saneamiento de datos (Sanitization):
Escapa caracteres especiales que puedan interpretarse como código:
```
< → &lt;
> → &gt;
& → &amp;
' → &#39;
" → &quot;
```

### 6.5 RECURSOS
1. Análisis de Logs
Los logs de tu servidor y aplicación son una de las primeras líneas para detectar ataques XSS.
Qué buscar: Solicitudes HTTP sospechosas:
URLs con patrones maliciosos como:
```
<script>
document.cookie
window.location
```
2. Parámetros codificados como 
```
%3Cscript%3E
```

3. Herramientas recomendadas
GoAccess: Análisis en tiempo real de logs.
Graylog o ELK Stack (Elasticsearch, Logstash, Kibana): Para centralizar y analizar patrones de tráfico.

![XSS imagen]( https://gogetsecure.com/wp-content/uploads/2023/03/cross-site-scripting-xss.jpg)


***

## 7. ZERO DAY EXPLOITS

### 7.1 DESCRIPCIÓN GENERAL
Un zero day exploits o vulnerabilidad de día cero es un fallo de seguridad informática que nunca se había visto antes. Por lo general, un atacante sondea a un sistema hasta que descubre una vulnerabilidad.

### 7.2 MECANISMOS DE ATAQUE
Un ataque de día cero se produce cuando los agentes maliciosos obtienen acceso a un sistema o red aprovechando una vulnerabilidad o debilidad de seguridad en un programa de software que el fabricante de este no conoce, lo que le deja “cero días” para solucionar el problema.

### 7.3 IOC (INDICADORES DE COMPROMISO)
1.	Presencia de archivos ejecutables desconocidos o recientemente creados.
2.	Procesos en ejecución que no coinciden con los patrones normales del sistema.
3.	Modificaciones en archivos del sistema o registros sin autorización.

### 7.4 ESTRATEGIAS DE MITIGACIÓN
Segmentación de Red y Acceso Controlado
1.	Microsegmentación: Divide la red en segmentos más pequeños para limitar la propagación de un ataque.
2.	Control de Acceso: Implementa el principio de menor privilegio, asegurándote de que usuarios y aplicaciones solo tengan los permisos estrictamente necesarios.
3.	Firewalls y ACLs: Configura reglas estrictas para controlar el tráfico entrante y saliente.

### 7.5 RECURSOS
Sistemas de Monitoreo Avanzado
1.	EDR (Endpoint Detection and Response): Herramientas como:
2.	CrowdStrike Falcon
3.	Microsoft Defender for Endpoint
4.	Sentinel One Estas herramientas monitorizan el comportamiento de los endpoints en busca de actividades anómalas y técnicas de explotación

![Zero Day Exploit imagen]( https://www.pandasecurity.com/es/mediacenter/src/uploads/2015/10/zero-day-ataque-1024x413.jpg)


***

## 8. DNS SPOOFING

### 8.1 DESCRIPCIÓN GENERAL
El DNS spoofing, o suplantación de DNS, es el proceso de alterar entradas en un servidor de DNS para redirigir a un usuario específico a una web malintencionada que está bajo control del atacante.

### 8.2 MECANISMO DE ATAQUE
Consiste en manipular la resolución DNS para redirigir a los usuarios hacia sitios web fraudulentos. 

### 8.3 IOC (INDICADORES DE COMPROMISO)
1.	Respuestas DNS con direcciones IP desconocidas o que no coinciden con los registros esperados (por ejemplo, direcciones IP fuera del rango legítimo del proveedor de servicios).
2.	Múltiples respuestas a una consulta única (indicativo de posibles ataques de envenenamiento de caché).

### 8.4 ESTRATEGIAS DE MITIGACIÓN
Implementar DNSSEC (Domain Name System Security Extensions)
1.	Qué hace: DNSSEC utiliza firmas digitales para garantizar la autenticidad y la integridad de las respuestas DNS, previniendo manipulaciones.
2.	Cómo implementarlo:

•	Habilita DNSSEC en tu servidor DNS autoritativo.
•	Asegúrate de que los clientes que consultan tu servidor soporten validación DNSSEC.

### 8.5 RECURSOS
Estas herramientas te permiten analizar el tráfico DNS y detectar anomalías:
1.	Wireshark:
•	Captura y analiza el tráfico DNS en tiempo real.
•	Busca discrepancias entre las solicitudes DNS enviadas y las respuestas recibidas (por ejemplo, direcciones IP que no corresponden con los dominios legítimos).
2.	DNSQuerySniffer:
•	Monitorea y muestra consultas DNS realizadas por tu sistema.
•	Detecta consultas que devuelven IPs maliciosas o inesperadas.
3.	Fiddler o Burp Suite:
•	Analizan el tráfico de red y permiten inspeccionar si el tráfico está siendo redirigido a servidores no legítimos

![DNS spoofing imagen]( https://www.keyfactor.com/wp-content/uploads/HACKER-1.jpg)
