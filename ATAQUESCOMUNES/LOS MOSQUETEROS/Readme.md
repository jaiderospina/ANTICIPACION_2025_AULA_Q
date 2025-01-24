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

![ description here](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASgAAACqCAMAAAAp1iJMAAABg1BMVEX///8AqON1wEQvGkXvN0L39/dtbW2zs7P8/Pyvr68ApOLS0tLz8/Pw8PDr6+vBwcHm5ua7u7vMzMzr6O0YADajo6Pg4OCcnJwzG0rQ0NCenp5nVWpDL0yqqqqVlZWa2vgAAAC13vPX1Nt+fn4rFEKJiYkAn+BUPVh5eXlvXXJmZmYQADBaWlqNjY2EhITBvMZSUlI2NjZBQUH5OUJXiD4AACJLS0sAACl5yEQoAEWXkKBZRGx7bokTADIZGRkbADcIACxgl0AkJCQrKyv/7/AAFkVzu0ROuOiknqzZ8/0RERGxrLgAACTtECLuIC7U8cJWHkS+L0N2I0QfGEUsDEXcNUN7zUQnIjg3JEtbTWrj8fpGNVpOSWNvboJ/fpBoWXf/yMr/z9Dr+uLt9+f3en77lJiW1HCv4JP0ZGqOh5eKJkRSdERrq0SaKkOAgI5DUEVMaEW65aLM7bm2LkN9JUTySFD6i4+HzFs5OEVMHUVBTkX+q65Qb0XY4tRsM0qoypQAABOA6bPTAAAWZElEQVR4nO1dCWPbNpbGxgEBDkiCgEwwZEuMR7SmDEVSh1sf2chy4ySbxmmSNk7GWedoO21n3KTHnN2ZPWZ++oKULMu33NgSO9EXReYhUcDHh/c+gDgAmGKKKaaYYooppphiiimm2AWunAQ46eSVBo357uyx6HY3NyadwJLAqM9vvXMsZmbm1yqTTmI5UK3PX/3ol8fgo/fmZ2Ybk05iOZAT9ctf/+JI/PpXU6IGKIj6xb8diV9MidrDlKgRMSVqREyJGhFTokbElKjjIcjQTrW+WRB1SBtMiQJGs7a3U62/lxP1H3gPsADuETX/FhMFAG0PjKq61XgnJwo0qqJRqTZEo9qvBxdEbW13+kSxMFMIXYdyMYk0jws2CdIwabYLNJtztH+8OtMnaufl08bL63euvnypjmLQI+rdRuODxu4FClCmp9piK0m5NaGcXBwgT5vtROrcMo2iVAGvpe+eHBBVbeyAaxuVjepGo1HNmwxO8lHYpHJxMSVHnPq5AurNVm3/3cdhYg52qvWtwkd9dAinOnPIoxs1+wLTfh6wiSfw6R/jScs5VEQIG9rZjXq/PoSRoh5N2vSk8xOGwXQFdIpTxXorPNXvvrGOsrJ1dvInJgeIetBPtHt0Q47QjnsmoqwjnZKRtfjZMjAucB1xCImO0PGfITdqIxTNsxHlrx9zZ8y4aZwpB2NCYU3E0pF+XIjGUXPE6D06UWTxpPuyesLJiSFQRDFMjy974sbIyR6ZKDLXihMtDfgxthPFI1nwWKHKHIJU0XWMRQXr5pHHj8LoFsXaHhQE1ZLVxDkqRtC7pZMKHCFiGHnRO/K0Fp3hWr0282Ow30fBJOttWExbDQ/7dXP1JKVgmON/RGgok8rlgX7UjcWLzlmuVV2bv/rRr47BfyqiOkNRD+2xQ6KWe7AQ4uaxPy1UghEdO1W2rhf+/IhTuHU2AYi7mzPvHov5+fnOcVEB6q3oIFXJMUypOF0keexMQUIpP8oR4fWzCmXx9MpJeK96wnf5enjAgyf+kb+hrMmyVPQpj4ofd4WC3TjgJ+OjbEpRxFihZ0aPMhcLLRj3L+JscX/ZXDx8q3BRizhJz4wbMpzAj5LVfXU9vHqIjJwoFHConwdRPBg2BqsXz0TfWeL8XNBzB8UNM+zgCB/LF3/ij1smEMDOPa1blA2Ynunr8T49Yt445LKVLRELKk+lv3lNx4cZkRJJVAsNWaMZy0TgywD5OpIG9qXjOLZMrRpb9DIGUC1II5zur87B1Z8aVKhmz4G2BQ3QFhBAE9swhmB0f+I3hxNCk4PnbT13Uvq5OPPAYRIFrsksHvoO50wQP9RhBDJlO7AmQSp9x5EWCEFKgUeQ6dJ0v1k1f3Id3myjFm1b64skSe6SG5po0TmUxc2RL8DWh5kKD3lKrhf10/OQB8rmufQck6WRyKidBsJBMQ8kSx1FVJaCTHopJZJogmjArvmWFOG+G8S0n/7rzTaPI9ROZBNGNIrtNm6Bu+Hc6Bcgd4c5WD3kF0TegsbPozaYXwNCrMQvBqoIqC1gYGCof/kZrA5GOD8OsSoZID+v/g2XeLj+BsmQc2AO2a1MLGqrPFsn63iORdpZPBVZH2JKHOEs88ydJ469HDwlYIRv0s4ILWBjFUKwZVlAqB2Q/z1TiOLtoZ2ojI0uPdg/NeKdG9CQD8c3LrDNBRa+mA9VslUl8mCYIERV8MgR0iCZ/KOjTO5to9rwGYscNE7WI9Kk+f88x71cm+AkxSwMCglnMEaYUU5jk3nFMY/GXoQsYKhKu6HrjGJEEBdE91S1CRNA6J6BH+UVxo5Fb297n5gKORSBwVXQoyx/MZrpHNjCopwgmycU6JGBlKG0ScIERsfcdIHu0jSOaGq7muF4OpOt4ljgpiAyXEVUDIREXs1AGmNBBnTmkEACGe/dp3jyBqWiz+pegaPZ0ImaSxKgxRTYTY3SRSZBaCfADCV1EqJyrT7OAy8TIAYJjn25fswPtOiqJ4ERCh3ELnFyQnGL37VlBiSUILI0IAIq/ExEBVGBIkpP7RRou2XQah9z6fFiWGreGArJoQ0UUZoB7BB4MkQqTzDJW49tCTTk50QxPScqUf9i99hnbMoWlco3kA4RJwayECuOYUI4UUVM6BSYQpjE1qkQNtGJqQodRYQNAl1WkvaLZE/zoiFxwVUVKTByX0R1EzHIGMc0739kKPdhEsFUJc3MZbvHKaBYv7DcKHlYDsDVve1W+R42ACZP/8x44O813MkLfoA8CP34iJr2Pl1gDG5ZsyTNPAp7At085Ddhcc7CBw7sIa+WA+O0FgacV1AAREqcmwhgXziq3gKhnl+PirwuYwCtYMfIKzkY+nb/J0tT8hTQnnHv3b68vqWUUu57IUZGqhIP8vofQ7jYVP+LzDcFAVApRaP4hnFM2Y2pyIhGI68Woho0Y6KlgkckNIyIu0wyqSJfLaMmqCFEfB7SwIn7iTuyoXpC2JMIew4hoZFkvoZqGg1JRBORRYpEX7JME5kKiW20KKmXkpgzjSIW6UyFvwwdU05IpuJiDYQe4YFy+6mJSBBGRM8DiG4kVISOnll5pKUk9F0HOLDfCyMpU+e3YO+uDQxdamnsuDwgAZF+RHJ7UElGlHLHidStT5Q08jXJYu5mAAWRkhIqU8kxMoHWREZdkJIoMyIDRJwRJGMrtDDLiB8EpKbsikgCfJ2kNZ46OvQLovBx+mwyuDHYSnZNgmdMmiHjtVBlqWbGIgwsVfvIEA9EiJRHMVMRhCmPOK05lEtJfD9i8pT2NeqdfP4QyFmeDF88wkH+0AmPYskEesy6JVGbfYiBPLdGbyIdC0bt4TMutAeN7a0L6DWVW6lv9Zwz2S8v6CEi3OLVBy5HPW8P/qBRo7bfi5Dc9G2odMHgEBaiXx56tXpxskpFGOkqIrAsUHGfugELLKAHlhuIgDs6tx0JUxUSLUkC10SuVfOEUgjEKRpv7Phcsnd+sAcljvYFAlJ5QSxjJA145ACbOwFWJy1H1zVPVWApknbbDlzoZkd30NkF0WWNS5ghIwKhivn5dSRDbo2mZubpCNl6CjKQYVOCWIIsikCmUZkWN4OWSUUVaO+WiF0nlbokD+eUxir5FiBO3lSMak6kKskkiDJLb5LITFz1uVMedS/yCIo0QyQTmVSqNGAASj+wsIiw5lDJqBJYIOBC6Q31qvl2mFkWjvJCKcvlyxVqg7jX9wq260RWzaKsKSKfA+LasY2TIEgsLrnSQETGIjZiU0TBKUTZwLY4tLGHOVSZF17e6KteFjc8YWKb5J8AwLMsDkye79iYW70Qq5XMl+eyaXerr6RUzcQmFjZgk2DsAVikXAhD5YbYpsqx2hd53oS4wF4cFxFa3gx74eWgZjyrRDxXlKhGvIsBUaxE/hOXTNXliHZb8MtUaSidOgC5HOhv4EP9NSYHMok+UadgYEhlainjpWkG3gMcuIMSEUXL+Jh/8GChRA6UlZGoxV3JEpdH5DllHC03EMFaeQZql5Ko2q4+yCYqMfehlES5u4lKyzPksZREDeq2JUpdiZKyh17TDwyBQ0FZBHEpieK9BtiQBtw502CvC0QpiRJ9Fdx2/dIoqXIS1e/z483NlaZbhFtGwQkHOqqEFawppphiiimm+NdGpbFx585GdcSHYZDw4fnpoNo2j2kGwYc7+JPd/gFnSF1jozFq4i4Q1Z2ttR4623dGSA7Ri9kHep+MgY88i9hcE9ADpq3ZxFRMQpMAISCxECDQEIpG6GH1xyKgiS0dkJGz3bi+uVYvsH1tolOiV553Omvzz56/ePH8Wade37x22uhKkY/CZLuzNCAeC5kI7jSNWKSZhCkzQUwtzfU1oXE7dLmGnMgGsSCpSyNG48iM9WDEGklju9PpXHn68vrL7c1Op3t9clRtdLr3nnPz5mefffb5zUrj2b3O1klTOYBi6hvdA+qtaCIyEikckfAgH1WRpJaq6jNgaiwWkMY4QlkE4sCTAjQBZzSVtmzHQEvpSC2W8Gp9dvNa1fjiiwdf/LbSeNmZXZnUigTPl+rPKp9/ef/j+wofX/7qJt/qfnBiYqx8ALRZTGZW7NdsG+m+UPX7vL+xBahDAPItB3HdUduBkIgLZAPm21IC34VSMNcaqZd95cps9xp+8PWTZYUny7/7ovKyXr9+Htk+M553ljZu/v7jhcs51Pv9j7/Cz+tLd074ip0PpudYlb2TuyC9OcR8d7vyYHn50qVLxdul5a9/u9HtTIKpnc49/vn9nKaFhceffPM4p+ovN6+tLZ0wcV9uUbYNvAsnytjqPoW/K2j68NWr1z2qHjRmO9cu9nePQGPpXuOzjwtj+nbm1q1Htx7n2/dvfje7dkLPltxHIXvXR10cXs5u468Lnr5f2VxZ+b5g6smDRr0+7lmH8Xzn2uc9nh7emsnxqCiC9/Gz7tXjv1ZEvcHcRPuHBeRy6kjv0++kdoZx2I21lUphT5dur+RpW/n+SWFTX1ybvTLyRc4Hdzrvwp5z+qTH08ytT4rdLytr9RNCX66j0K6OynvCAyEpdfNZOdwQmi2RSuXP0xCmmUhoknq6T9skimxHT1MiJY9H6du33bnzoFfcftgsErfy+lKxi9WZ8yFgROCtpcZX93sF79EuUYVb//jzF53nJ3zTJJTvzgcrSYSAHRMlECKYqOIIYxgBDTjCTTOHuUqRhk3GYiUeqKs5IjIyZxTn1qhfgZd66KVtZuX9Hm9/aNS3ziP/I6OxtnWz4Ony5YeffvrpQ/X28Jte/Pt95d7miNJZEp4A4UU+EzFs0gyDpqUFCARSsyMuJFgPUMaVYE+AElfUZ06EdPP0WZeudu78cblH1G/me0R92Ntfhttrp0i988VOfeezXaIuf/unhYVvv738sEfU/Ztbo3pMjC0MsKXMLB/7Bsx8yBtWJPtUbZkAg0WYD63DBgRYnTTVJ/I54U+7LJypV37sW1T7AFEPdjo7b5r5s+DpEv+yL6AeXv7mz48ff/qnx32Luv/ZztobBuHBtAs/7aFAdfbKb/sG9XqlV/Q2f+gf+F1j7embJe5MgFv3Kn+53HfmM998O/Pw2z/PPO4f+OvG0v64h7XxPqRp1F9+0efldp+olVf9Az9WOltjnA3QnF+rXO5j4dEj5c4fPfrzQn//99WlfTeNjnu644369Qd9XpbfL5ia/6/+/qVlc3Z+jG0ulfn6zYVdor4pwt6tx7vM7SfKiCOjv9TEheHAcNY79Z0/DoiZmS9c1KXdfaM7aqg5Dwxb1OWFGcXUrU8HxH3Jh4myV+dC7WIRH3iqOGRRuZfanF/5YbB7SVnUGPvE4z0fVQS+R4++WRjw9tXG0r66p0zG3Fu/UX/6xYCZ5dc/fP/+Hk8/Vurb45wL4elSoxf1FhTypoOFfKsf9b47EPVEe7xOSszO96Le8qXbr2/nuPT69e3l3aj3cpxp2al/V+iohT8psVm0IDz+28NPC21+/+bMIR01XpOCW/Xq1zlPr7ZWVl7dXll5//XKyubfc6qWH7wYr46qrs0bipXHKtrNPPrb44XLn+SR79bDIujdm5nwyJjrnWvKSS23VcSb//uT77eevFJbmyuv1TF4ZbzKHG+vbfz3/cv9at6j4pVvPFz4+ObzzotxJuUINOrz8Mfl/+kpg+Xbr5/8fb67srmyeenJHzaWtseblo36FuwLg2Hc+uSv1aX6xNeAfW/22oMnPa25cvuHmSdb3WtVBfG/lnof87rHW93nNz84yNNM9//Au91JG1Teqtit/KPTr+X9MKPcVHWtWPO43pnt1JfGWYkB1aW1DeWpDvD0Lnze7ZZgKqLrs1vw+mxRy3v1/eaHK5vV3xRPGQp8+O9jTcudtaWG2OoO81R/B343O15neQzgdnfb2Omo+zjfbm/+sLlS/c2eshozUWBnaWkHv/ig27eq+c69DfjO7AfjbpQ+GpUr3S1R3apvzm9tzbw73x0i6tK4iQLXlma3qpVr73aW1tbWuk834MZatxT2lMPcnq3vGNXrW7OdTr27PVGiQGNmdu3ZRqWSR5RK9c5WvfNs4gFvAPyiM7v5ompVikA3WaKAsTNbX1vbevr86rOZpXp9ZlLPrI9G9Wm9U9987+XLp9t1RdSknHkPxsbLlTVFVn3tyvVyeKdhVHe2lRpYWqt3q533B3g1CaIUYLXaaFQrJRAFR6GSJ04AeH0I5TL8MsF8sXNtGDvjfbj380Hlnx8UuPriSv7n3j8n063lZwCzsh8l9RNvLehxky5OsR9zbA4KAoRlC2Lms+RogWET6NmgzYtJc+zyjAufKFbFKm9rTFvkc7LNmwltpWROEm3Om9P1pOk12xMbF+4C3bLz5616byxjze43PqlC4AT5iWiMa+zdCAm90fQ1AeZAK2stBpotEhCxtmiBkFOZTK5k3oWrjhNYjqFHCIjA9qyWDxgFIEiNli3sQHCjLfMZLfgYlmOfw8BsayQheG4xttqanbVoE0SLd+3FhKyvWpMzKBA6mqaJVbrI4shpSTvxVmkQaQyYLeYHQasm2naLoTjzk3HORQvnxvdbo4HeYEnLnIu1wGWpiJ3YvgHkeqLKXNKyAseOnUVjEcrAi+Jxmj0u0RxWPZhzptSA25Q0aYmoTTURLdrN3HhQG+i6OpIYWctcbFlxeebXmGKKKaa4eJjW+BdB/hmC5Ks29xdBDoLhQEGGVrnsnaZlWGloQqD60ECDEGTM5xGt+Tr3mcYiyl3SFKm0lKCzZUJ5qgtJpKTUY64kGXMpsEozL8pFIl9alFqov25mHNgJZTUQgTSmuo8zELg0swLopqpSBXREJY0UM4aTpr4uuWdFAhD9DRZx/NmAKYpgscJv3pEnyqfoFxmI80UJhM9rQHNYKKJAbQEaxIgJDSESBp6v7MqjHJIIZLwsUxJdJIJ8CGJBVF4vysufDSHQTAwsiK1i7VdsQKs4YxkYWoY6ofaxqgxaGEM772//NsSCnCjWWzN66Oi01e4Q8mHSDOREvQ1m8QYohtehA+MQC8cu+g1iu+rgiMF0wwvdWgJgyskY28zGjP4iyMVqmZZNILERSBDkTPDEooq+BJkCCctgVr5InSJUIAtwQDwgpMUQ4BQyQanIKKCS5wtIev+aT0BELjh72hIrpZTGuoygTGxKXRHGNogNKXxHOr5QW6GiTugpcOwsA9IhDkVaqPaV4tI5q/mO51OvRJNmny/2hn01UZsoUaTBFEQOTUkAMIiwjAlKQ0oi7MvMALFIgdUWEa75hBFHApG/M91jNdchKUhKtzrD+YMaDJPARoHJmLDzMdQYUOzRQAgiLIp5qkjigQeADkjAiS1sm+qWwIFuBzrmHjED422Qn6fCCU5tNeRvgUFNMToOR3fj0PgNY+ivcfDg2wEHFjNb4vwxIu6/VAwrFmDBg2M0/4PyT+FiW0E3aP/kWwG4KJoupynTLJAGrBkEquab6I7L3VAiG0RMhDxCGYtCqhk4lUHoijQSoRdT1w98GbwtjjwC0nQyyYJ8QU2RgXxughqo+VJndiYAqTlEmVfKiKc+gqUPMgdJ6guQQjcDoQTpW2JToedaTi3yQhvIQNSADFMa+8glihufAp7ykKZAUi00NBNLB+fLW+lmSB3kID9wgXxLiBoRewoAJ1NmpphiiimmmGKKKaaYYopzxP8DBbvO8vKPIM8AAAAASUVORK5CYII=)

**Qué es Cross-Site Scripting**

se conoce como  XSS a un tipo de ataque en el cual actores maliciosos logran inyectar un script malicioso en un sitio web para luego ser procesado y ejecutado. Comúnmente, este proceso que se basa en la confianza que tiene el sitio sobre la entrada de los datos, consiste en enviar la URL con el payload precargado al usuario víctima con un objetivo determinado: robar datos personales del usuario, cookies de sesión, implementar técnicas de ingeniería social, entre otras.

**Reflected Cross-Site Scripting**

En un ataque de XSS reflejado el payload suele ser inyectado en un parámetro de la solicitud HTTP, para luego ser procesado por la aplicación web y finalmente desplegado en un punto determinado, sin algún tipo de validación o codificación de los caracteres. Se trata de la variedad de XSS más simple y el script malicioso que busca afectar el navegador de la víctima es fácilmente modificable, probablemente sin que el usuario note el ataque.

**Stored Cross-Site Scripting**

Esta variante tiene como característica que la aplicación web guarda el valor de entrada en un medio de almacenamiento y persiste el script inofensivo, hasta que el valor es recuperado por la aplicación y utilizado para conformar parte del documento HTML.
Los puntos de entrada más conocidos en los cuales se suele observar esta vulnerabilidad están en los comentarios de sitios web, entradas de blog, nombres de usuario, chats, formularios de contacto, detalle de alguna orden, etc. Y así como existen diversos valores de entrada, un XSS persistente podría llegar de distintos medios. La respuesta del protocolo HTTP es el más común, así como mensajes mediante SMTP, servicios de mensajería instantánea, notificaciones vía socket, por mencionar algunos

**DOM-based Cross-Site Scripting**

El Document Object Model (DOM) es una interfaz de programación para representar la estructura de un documento web y conectarlo con un lenguaje de scripting. En este sentido, el DOM facilita la estructura de documentos como HTML o XML y permite a los programas modificar la estructura, estilo y contenido del documento. En el caso de un ataque de XSS basado en DOM el payload malicioso es ejecutado como resultado de la modificación del entorno DOM en el navegador de la víctima. Esto lleva a que el usuario ejecute código desde el lado del cliente sin saber que lo está haciendo.
