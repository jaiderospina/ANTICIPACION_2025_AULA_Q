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

(data:image/png;base64,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)


