# **LOS MOSQUETEROS** 
## **VICTOR ALFONSO GOMEZ GUZMAN**
## MIGUEL ANGEL GARNICA TORRES 
## RUBEN EDUARDO RINCON SOLANO 
## JHON VARGAS MARTINEZ JHON 
---


# PHISING ATTAK
---


# Phishing Attack

![Phishing Attack]([https://via.placeholder.com/1000x200/0000FF/FFFFFF?text=Phishing+Attack](https://www.incibe.es/sites/default/files/images/ransomware/cabecera-ransomeware.png)

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

**Ejemplos de código:**

* **Script de Python para simular una inundación SYN:**

```python
import socket
import random

def syn_flood(target_ip, target_port):
  # Crea un socket TCP
  s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)

  # Genera un número de secuencia aleatorio
  seq_num = random.randint(0, 4294967295)

  # Crea un paquete SYN
  ip_header = IP(dst=target_ip)
  tcp_header = TCP(dport=target_port, flags='S', seq=seq_num)
  packet = ip_header / tcp_header

  # Envía el paquete
  s.sendto(packet, (target_ip, target_port))

# Dirección IP del objetivo
target_ip = '192.168.1.100'

# Puerto del objetivo
target_port = 80

# Número de paquetes a enviar
num_packets = 1000

# Envía los paquetes
for i in range(num_packets):
  syn_flood(target_ip, target_port)

# man-in-the-middle (MitM)
