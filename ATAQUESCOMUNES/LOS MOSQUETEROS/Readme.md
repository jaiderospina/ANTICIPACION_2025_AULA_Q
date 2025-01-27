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

![enter image description here]![enter image description here](data:image/jpeg;base64,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)# Welcome to StackEdit!



