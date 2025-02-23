# **LOS MOSQUETEROS** 
## **VICTOR ALFONSO GOMEZ GUZMAN**
## MIGUEL ANGEL GARNICA TORRES 
## RUBEN EDUARDO RINCON SOLANO 
## JHON VARGAS MARTINEZ JHON 
---


# PHISING ATTAK
---


# Phishing Attack

![enter image description here](https://www.usd.de/wp-content/uploads/usd-ag-news-phishing-angriffe.jpg)

## ¿Qué es un ataque de phishing?

Un ataque de phishing es un método de ciberataque utilizado para engañar a las personas y obtener información confidencial como contraseñas, números de tarjeta de crédito o información personal. Estos ataques suelen realizarse mediante correos electrónicos, mensajes o sitios web fraudulentos diseñados para parecer legítimos.

---
***
# man-in-the-middle (MitM)**
***
Un ataque Man-in-the-Middle (MitM) ocurre cuando un atacante se interpone en la comunicación entre dos partes, interceptando y potencialmente manipulando el tráfico que fluye entre ellas. Las víctimas creen que están comunicándose directamente entre sí, sin saber que un tercero está espiando o alterando la conversación.

**¿Cómo funciona un ataque MitM?**

1. **Intercepción:** El atacante se posiciona entre las dos partes, ya sea mediante técnicas de envenenamiento ARP, DNS spoofing o controlando un punto de acceso Wi-Fi malicioso.
2. **Redirección:** El tráfico de la víctima se redirige al atacante, quien puede leer, modificar o incluso bloquear la información.
3. **Transparencia:** El atacante reenvía el tráfico a la víctima original, haciendo que la comunicación parezca normal.

**Tipos de ataques MitM:**

* **Envenenamiento ARP:** El atacante envía mensajes ARP falsos para asociar su dirección MAC con la dirección IP de otra máquina en la red, redirigiendo el tráfico a través de él.
* **DNS Spoofing:** El atacante manipula los registros DNS para redirigir a las víctimas a sitios web falsos que parecen legítimos.
* **HTTPS Spoofing:** El atacante utiliza certificados SSL/TLS falsos para hacerse pasar por un sitio web seguro, interceptando información confidencial como contraseñas y datos bancarios.
* **Wi-Fi Spoofing:** El atacante crea un punto de acceso Wi-Fi falso que parece legítimo para capturar el tráfico de las víctimas que se conectan.

**Consecuencias de un ataque MitM:**

* **Robo de información:** El atacante puede capturar información confidencial como contraseñas, datos bancarios, información personal, etc.
* **Manipulación de datos:** El atacante puede modificar la información en tránsito, por ejemplo, alterando transacciones bancarias o inyectando malware en archivos descargados.
* **Suplantación de identidad:** El atacante puede hacerse pasar por una de las partes, engañando a la víctima para que revele información confidencial o realice acciones no deseadas.

**Mitigación de ataques MitM:**

* **Usar conexiones HTTPS:** Asegúrate de que los sitios web que visitas utilicen HTTPS, lo que cifra la comunicación y dificulta la interceptación.
* **Verificar certificados SSL/TLS:** Presta atención a las advertencias del navegador sobre certificados inválidos o sospechosos.
* **Usar una VPN:** Una VPN cifra todo tu tráfico de Internet, haciéndolo más difícil de interceptar.
* **Usar autenticación de dos factores:** Agrega una capa adicional de seguridad a tus cuentas.
* **Ser cauteloso al usar redes Wi-Fi públicas:** Evita realizar transacciones sensibles en redes Wi-Fi públicas o utiliza una VPN para proteger tu conexión.


## ¿Cómo funciona un ataque de phishing?

1. **Creación de una página falsa**: El atacante crea un sitio web que imita a uno legítimo, como un banco o una red social.
2. **Envío de correos o mensajes engañosos**: Se envían mensajes con enlaces que llevan a la página falsa, a menudo disfrazados como notificaciones urgentes.
3. **Recolección de información**: Cuando la víctima introduce sus datos, estos son enviados al atacante.

---

## Ejemplo de ataque de phishing

> Un atacante envía un correo que parece provenir de "tu banco", indicando que tu cuenta ha sido bloqueada y pidiéndote iniciar sesión en un enlace proporcionado. El enlace lleva a un sitio web que se ve exactamente como el de tu banco, pero es falso.

---

## Cómo prevenir un ataque de phishing

- Verifica la URL de los sitios web antes de ingresar información.
- No hagas clic en enlaces sospechosos en correos electrónicos o mensajes.
- Habilita la autenticación en dos pasos en tus cuentas.
- Mantén actualizado tu software de seguridad.

----


# Ransomware Attack

![enter image description here](https://www.globalsign.com/application/files/5516/6488/2151/Ransomware.png)

## ¿Qué es un ataque de ransomware?

Un ataque de ransomware es un tipo de ciberataque en el que los atacantes cifran los datos de una víctima y exigen un rescate ("ransom") a cambio de la clave para restaurar el acceso. Estos ataques pueden paralizar sistemas enteros y causar grandes pérdidas económicas.

---

## ¿Cómo funciona un ataque de ransomware?

1. **Infección inicial**: El atacante introduce el ransomware a través de correos electrónicos maliciosos, descargas de software no confiables o vulnerabilidades del sistema.
2. **Cifrado de datos**: Una vez en el sistema, el ransomware cifra los archivos importantes, haciéndolos inaccesibles para el usuario.
3. **Demanda de rescate**: El atacante deja una nota exigiendo el pago de un rescate, generalmente en criptomonedas, para proporcionar la clave de descifrado.

---

## Ejemplo de ataque de ransomware

> Un empleado descarga un archivo adjunto de un correo que parece provenir de un cliente. El archivo contiene un ransomware que se activa, cifrando todos los archivos de la empresa y dejando un mensaje pidiendo el pago de 5 bitcoins para recuperar el acceso.

---

## Cómo prevenir un ataque de ransomware

- Realiza copias de seguridad de tus datos regularmente y almacénalas de forma segura.
- No abras archivos adjuntos de remitentes desconocidos.
- Mantén actualizado tu software y sistema operativo.
- Utiliza herramientas de seguridad que detecten y bloqueen ransomware.
- Capacita a tu equipo para identificar posibles amenazas.

---
---
## Denegación de Servicio (DoS)

![enter image description here](https://cdn.computerhoy.com/sites/navi.axelspringer.es/public/media/image/2019/12/7-mayores-ataques-ddos-historia-internet_2.jpg)

Un ataque de denegación de servicio (DoS) es un intento malicioso de hacer que un servidor, servicio o red no esté disponible para los usuarios legítimos. Esto generalmente se logra inundando el objetivo con tráfico o enviando solicitudes maliciosas que causan que el objetivo se sobrecargue o se bloquee.

**Tipos comunes de ataques DoS:**

* **Inundación SYN:** El atacante envía un gran número de solicitudes SYN (solicitud de conexión) al objetivo, pero no completa el protocolo de enlace TCP. Esto agota los recursos del objetivo y le impide responder a solicitudes legítimas.
* **Ataque de inundación ICMP:** El atacante envía un gran número de paquetes ICMP (Protocolo de mensajes de control de Internet) al objetivo, como solicitudes de "ping". Esto puede saturar el ancho de banda del objetivo o sobrecargar su capacidad de procesamiento.
* **Ataque de inundación UDP:** El atacante envía un gran número de paquetes UDP (Protocolo de datagramas de usuario) al objetivo. Esto puede saturar el ancho de banda del objetivo o sobrecargar su capacidad de procesamiento.
* **Ataque de amplificación:** El atacante envía una pequeña solicitud a un servidor que responde con una respuesta mucho más grande. El atacante falsifica la dirección IP de origen para que la respuesta se envíe al objetivo, amplificando el ataque.

**Consecuencias de un ataque DoS:**

* **Pérdida de ingresos:** Las empresas pueden perder ingresos si sus sitios web o servicios no están disponibles para los clientes.
* **Daño a la reputación:** Un ataque DoS puede dañar la reputación de una empresa si los clientes perciben que no puede proteger sus datos o servicios.
* **Pérdida de productividad:** Los empleados pueden no poder trabajar si los sistemas de la empresa no están disponibles.
* **Costos de recuperación:** Las empresas pueden incurrir en costos significativos para recuperarse de un ataque DoS.

**Mitigación de ataques DoS:**

* **Utilizar un firewall:** Un firewall puede ayudar a bloquear el tráfico malicioso.
* **Utilizar un sistema de detección de intrusiones (IDS):** Un IDS puede ayudar a identificar y bloquear ataques DoS.
* **Utilizar un proveedor de servicios de mitigación de DDoS:** Un proveedor de servicios de mitigación de DDoS puede ayudar a absorber el tráfico malicioso y proteger el objetivo.
* **Implementar medidas de seguridad en la red:** Esto puede incluir el uso de listas de control de acceso (ACL) y la segmentación de la red.

***

# Ataque Man-in-the-Middle (MitM)
---
![enter image description here](https://aboutssl.org/wp-content/uploads/2020/03/man-in-the-middle-attack.svg)

---
Un ataque Man-in-the-Middle (MitM) ocurre cuando un atacante se interpone en la comunicación entre dos partes, interceptando y potencialmente manipulando el tráfico que fluye entre ellas. Las víctimas creen que están comunicándose directamente entre sí, sin saber que un tercero está espiando o alterando la conversación.

## ¿Cómo funciona un ataque MitM?

1. **Intercepción:** El atacante se posiciona entre las dos partes, ya sea mediante técnicas de envenenamiento ARP, DNS spoofing o controlando un punto de acceso Wi-Fi malicioso.
2. **Redirección:** El tráfico de la víctima se redirige al atacante, quien puede leer, modificar o incluso bloquear la información.
3. **Transparencia:** El atacante reenvía el tráfico a la víctima original, haciendo que la comunicación parezca normal.

## Tipos de ataques MitM:

* **Envenenamiento ARP:** El atacante envía mensajes ARP falsos para asociar su dirección MAC con la dirección IP de otra máquina en la red, redirigiendo el tráfico a través de él.
* **DNS Spoofing:** El atacante manipula los registros DNS para redirigir a las víctimas a sitios web falsos que parecen legítimos.
* **HTTPS Spoofing:** El atacante utiliza certificados SSL/TLS falsos para hacerse pasar por un sitio web seguro, interceptando información confidencial como contraseñas y datos bancarios.
* **Wi-Fi Spoofing:** El atacante crea un punto de acceso Wi-Fi falso que parece legítimo para capturar el tráfico de las víctimas que se conectan.

## Consecuencias de un ataque MitM:

* **Robo de información:** El atacante puede capturar información confidencial como contraseñas, datos bancarios, información personal, etc.
* **Manipulación de datos:** El atacante puede modificar la información en tránsito, por ejemplo, alterando transacciones bancarias o inyectando malware en archivos descargados.
* **Suplantación de identidad:** El atacante puede hacerse pasar por una de las partes, engañando a la víctima para que revele información confidencial o realice acciones no deseadas.

## Mitigación de ataques MitM:

* **Usar conexiones HTTPS:** Asegúrate de que los sitios web que visitas utilicen HTTPS, lo que cifra la comunicación y dificulta la interceptación.
* **Verificar certificados SSL/TLS:** Presta atención a las advertencias del navegador sobre certificados inválidos o sospechosos.
* **Usar una VPN:** Una VPN cifra todo tu tráfico de Internet, haciéndolo más difícil de interceptar.

----

## INYECCION DE SQL ##

Es un lenguaje de consulta estructurado **(«Structured Query Language»)** que se ha convertido en el lenguaje estándar para la gestión de bases de datos. Cuando un sitio web necesita acceder a la base de datos que tiene en su servidor para buscar o editar información, utiliza SQL para procesar esa «consulta» o solicitud 

## ¿Y dónde entra la parte de la inyección?

se producen cuando el hacker introduce o inyecta en el sitio web código SQL malicioso, un tipo de malware que se conoce como la carga útil, y consigue subrepticiamente que envíe ese código a su base de datos como si de una consulta legítima se tratara.


# ¿Qué efecto tienen los ataques de inyección de SQL?

Los hackers recurren a los ataques de inyección de SQL con el fin de introducirse en la base de datos de un sitio web. A veces solo quieren eliminar datos para provocar el caos y, en otras ocasiones, lo que buscan es editar la base de datos, especialmente en el caso de sitios web financieros. En el momento en que el hacker ha logrado el control de la base de datos, ya es fácil interferir en los saldos de las cuentas de los clientes y mandarse dinero a su propia cuenta.
Sin embargo, a menudo lo que el ciberdelincuente quiere son los datos de usuario guardados en el sitio web, como las credenciales de inicio de sesión. Estos datos de inicio de sesión robados puede emplearlos para realizar acciones en nombre de los usuarios afectados o reunirlos en una gran lista que luego venderá a otros ciberdelincuentes en la red oscura. Las personas que compran información robada lo hacen, frecuentemente, con la finalidad de robar identidades y cometer fraudes.

* **Introducción de Datos del Usuario:** Es la forma más sencilla de perpetrar un ataque de inyección de SQL. Hay un montón de sitios web que recopilan las entradas del usuario y las transmiten al servidor.
*  **Modificación de Cookies:** Las cookies son archivos pequeños que residen en el navegador y facilitan a los sitios web información sobre el usuario.
* **Mediante Variables de Servidor:** Al introducir la URL de un sitio web en el navegador, tiene lugar una rápida secuencia de comunicaciones cuya finalidad es ofrecer el sitio al usuario. Dentro de este proceso, el navegador solicita una lista de datos denominada «variables de servidor» que sirve para que el sitio se renderice correctamente. Un hacker astuto puede meter sigilosamente código SQL en las solicitudes del navegador, las cuales, si no se sanean debidamente, se inyectarán en la base de datos del sitio web, que se encuentra en el servidor.
* **Mediante Herramientas de Hackeo Automáticas:** Hay herramientas automáticas de inyección de SQL, como SQLMAP, que detectan y aprovechan las vulnerabilidades en la inyección de SQL presentes en un sitio web determinado y en su base datos.  
**SQLMAP** es una herramienta de código abierto muy popular entre los gestores de bases de datos y los desarrolladores de sitios web que quieren parchear sus sitios para protegerlos contra la inyección de SQL.


**ATAQUES SQL DE SEGUNDO ORDEN**

La inyección de SQL de segundo orden va un poco más lejos, ya que emplea un método mucho más sofisticado. Dado que muchos sitios web se sanean para evitar la introducción de datos directa por parte los usuarios, los hackers inyectan SQL diseñado para ejecutarse únicamente en las visitas posteriores. un ataque de inyección de SQL de segundo orden es una bomba de relojería.

**Efectos de las SQLI en las Personas**

Aunque los blancos de una SQLI no son las personas, si usted utiliza un sitio web donde se haya perpetrado un ataque de este tipo, el impacto podría ser considerable. Tener una cuenta en un sitio web que sufra un ataque o enviar datos personales a este sitio permitiría a los hackers hacer muchas cosas, no solo conseguir sus datos personales.

Los ataques de inyección de SQL pueden tener consecuencias graves para las personas, a saber:

* **Pérdida de Dinero:** un hacker puede usar una SQLI en la página de una entidad bancaria u otra institución financiera a fin de transferir dinero desde la cuenta de un usuario.
* **Robo de Identidad:** cuando un hacker controla una base de datos, puede hacerse con la información que contiene y venderla en la red oscura. Otros ciberdelincuentes pueden comprar estos datos y utilizarlos para robar identidades.

![enter image description here](https://www.avast.com/hs-fs/hubfs/New_Avast_Academy/SQL%20injection/What%20is%20a%20SQL%20injection.png?width=660&name=What%20is%20a%20SQL%20injection.png)

---

# **EL CROSS-SITE SCRIPTING** 

Es un ataque de seguridad que permite a los ciberdelincuentes ejecutar códigos maliciosos en sitios web legítimos. El objetivo de este ataque es robar datos confidenciales o secuestrar sesiones de los usuarios.
Para realizar un ataque XSS, los ciberdelincuentes inyectan secuencias de comandos maliciosas en el código de un sitio web. Esto se puede hacer de varias formas, por ejemplo, añadiendo el código al final de una URL o publicándolo en una página que muestre contenido generado por el usuario. 

![enter image description here](https://www.imperva.com/learn/wp-content/uploads/sites/13/2019/01/sorted-XSS.png.webp)

**Qué es Cross-Site Scripting**

se conoce como  XSS a un tipo de ataque en el cual actores maliciosos logran inyectar un script malicioso en un sitio web para luego ser procesado y ejecutado. Comúnmente, este proceso que se basa en la confianza que tiene el sitio sobre la entrada de los datos, consiste en enviar la URL con el payload precargado al usuario víctima con un objetivo determinado: robar datos personales del usuario, cookies de sesión, implementar técnicas de ingeniería social, entre otras.

**Reflected Cross-Site Scripting**

En un ataque de XSS reflejado el payload suele ser inyectado en un parámetro de la solicitud HTTP, para luego ser procesado por la aplicación web y finalmente desplegado en un punto determinado, sin algún tipo de validación o codificación de los caracteres. Se trata de la variedad de XSS más simple y el script malicioso que busca afectar el navegador de la víctima es fácilmente modificable, probablemente sin que el usuario note el ataque.

**Stored Cross-Site Scripting**

Esta variante tiene como característica que la aplicación web guarda el valor de entrada en un medio de almacenamiento y persiste el script inofensivo, hasta que el valor es recuperado por la aplicación y utilizado para conformar parte del documento HTML.
Los puntos de entrada más conocidos en los cuales se suele observar esta vulnerabilidad están en los comentarios de sitios web, entradas de blog, nombres de usuario, chats, formularios de contacto, detalle de alguna orden, etc. Y así como existen diversos valores de entrada, un XSS persistente podría llegar de distintos medios. La respuesta del protocolo HTTP es el más común, así como mensajes mediante SMTP, servicios de mensajería instantánea, notificaciones vía socket, por mencionar algunos

**DOM-based Cross-Site Scripting**

El Document Object Model (DOM) es una interfaz de programación para representar la estructura de un documento web y conectarlo con un lenguaje de scripting. En este sentido, el DOM facilita la estructura de documentos como HTML o XML y permite a los programas modificar la estructura, estilo y contenido del documento. En el caso de un ataque de XSS basado en DOM el payload malicioso es ejecutado como resultado de la modificación del entorno DOM en el navegador de la víctima. Esto lleva a que el usuario ejecute código desde el lado del cliente sin saber que lo está haciendo.

 ---

  **Zero (Posiblemente Zero-Day)**

![enter image description here](https://www.fortinet.com/content/dam/fortinet/images/cyberglossary/zero-day-threat.jpg)

En ciberseguridad, "Zero" suele ser una abreviatura para Zero-Day, que se refiere a una vulnerabilidad desconocida para los desarrolladores de software o los equipos de seguridad antes de que sea explotada por atacantes.

**Zero-Day Vulnerability** Una falla en el software o hardware que no ha sido descubierta ni parcheada.
**Zero-Day Exploit** Es un ataque que utiliza esta vulnerabilidad antes de que se haya publicado un parche.
**Amenaza clave** Dado que estas vulnerabilidades son desconocidas, las defensas tradicionales como antivirus o firewalls suelen ser ineficaces frente a los ataques Zero-Day.
**Defensa** Sistemas como la detección de anomalías, análisis de comportamiento, y el uso de inteligencia artificial son cruciales para identificar patrones que podrían ser indicativos de estos ataques.

**DNS (Domain Name System)**

El **DNS** (Sistema de Nombres de Dominio) es un protocolo fundamental de Internet que traduce nombres de dominio fáciles de recordar (como google.com) a direcciones IP que los ordenadores utilizan para comunicarse (como 142.250.190.14).

**En ciberseguridad, el DNS es crítico porque:**

**Ataques basados en DNS**
DNS Spoofing o Poisoning: Manipulación de la caché de DNS para redirigir a los usuarios a sitios maliciosos.
o	Ataques DDoS a DNS: Los servidores DNS pueden ser objetivo de ataques para deshabilitar el acceso a sitios web.
o	Tunneling DNS: Uso de peticiones DNS para transmitir datos (generalmente para exfiltración de información o comunicación C2 en malware).

**Defensas relacionadas con DNS**
o	DNSSEC (DNS Security Extensions): Asegura la integridad de las respuestas DNS mediante firmas criptográficas.
o	Firewalls de DNS: Bloquean accesos a dominios maliciosos conocidos.
o	Monitorización DNS: Detectar actividad sospechosa como consultas a dominios extraños (indicadores de malware o C2).

