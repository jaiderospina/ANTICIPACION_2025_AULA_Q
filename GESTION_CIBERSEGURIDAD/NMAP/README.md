## **Taller en Clase**

1. Realizar según las indicaciones de clase el ejercicio desarrollado en:

- https://github.com/SabyasachiRana/WebMap

2. 

**Manual de Nmap: Técnicas y Ejemplos Prácticos**  
*Objetivo de ejemplo: scanme.nmap.org*  

---

### **1. Introducción a Nmap**  

**Nmap** (Network Mapper) es una herramienta de código abierto para exploración de redes y auditorías de seguridad. Permite descubrir dispositivos en una red, identificar puertos abiertos, servicios en ejecución, sistemas operativos y vulnerabilidades. Es utilizado por administradores de redes, pentesters y entusiastas de la ciberseguridad.  

**Nota importante**:  
El sitio `scanme.nmap.org` es un servidor de prueba proporcionado por los desarrolladores de Nmap para experimentar. Evita escanear otros sitios sin autorización explícita, ya que podría ser ilegal.

---

### **2. Técnicas Principales de Nmap**  

#### **2.1 Tipos de Escaneo**  
- **TCP SYN Scan (`-sS`)**:  
  Envía paquetes SYN para determinar puertos abiertos sin completar la conexión. Rápido y sigiloso.  
  *Requiere privilegios de root*.  

- **TCP Connect Scan (`-sT`)**:  
  Completa la conexión TCP (handshake de 3 vías). Útil si no hay permisos de root.  

- **UDP Scan (`-sU`)**:  
  Escanea puertos UDP. Es más lento debido a la falta de respuestas en protocolos UDP.  

- **Escaneo de Ping (`-sn`)**:  
  Descubre hosts activos sin escanear puertos.  

#### **2.2 Detección de Servicios y SO**  
- **Detección de Versiones (`-sV`)**:  
  Identifica la versión de los servicios en puertos abiertos.  

- **Detección de SO (`-O`)**:  
  Determina el sistema operativo del host objetivo.  

#### **2.3 Uso de Scripts (NSE)**  
- **Nmap Scripting Engine (NSE)**:  
  Ejecuta scripts para tareas avanzadas (vulnerabilidades, recolección de información, etc.).  
  Ejemplo: `--script http-title` para obtener el título de una página web.  

#### **2.4 Opciones de Temporización**  
- **Modos de Velocidad (`-T0` a `-T5`)**:  
  Controla la agresividad del escaneo. `-T4` es rápido; `-T1` es sigiloso.  

---

### **3. Ejemplos Prácticos**  
*Objetivo: scanme.nmap.org*  

#### **3.1 Escaneo Básico**  
```bash  
nmap scanme.nmap.org  
```  
- **Resultado**: Muestra puertos abiertos y servicios básicos.  

#### **3.2 Escaneo con Detección de Versiones**  
```bash  
nmap -sV scanme.nmap.org  
```  
- **Detalles**: Identifica versiones de servicios (Ej: Apache 2.4.7).  

#### **3.3 Detección de Sistema Operativo**  
```bash  
sudo nmap -O scanme.nmap.org  
```  
- **Nota**: Requiere permisos de root (`sudo`).  

#### **3.4 Escaneo UDP**  
```bash  
sudo nmap -sU scanme.nmap.org  
```  
- **Uso típico**: Para servicios como DNS o DHCP.  

#### **3.5 Uso de Scripts NSE**  
```bash  
nmap --script http-title scanme.nmap.org  
```  
- **Salida**: Muestra el título de la página web alojada.  

#### **3.6 Escaneo Agresivo**  
```bash  
nmap -A scanme.nmap.org  
```  
- **Combina**: Detección de SO, versiones, scripts comunes y traceroute.  

#### **3.7 Guardar Resultados**  
```bash  
nmap -oN resultado.txt scanme.nmap.org  
```  
- **Formatos**: `-oN` (texto), `-oX` (XML), `-oG` (grepable).  

---

### **4. Mejores Prácticas y Consideraciones Éticas**  
- **Permisos**: Siempre obtén autorización antes de escanear redes ajenas.  
- **Límites**: No abuses de `scanme.nmap.org`. Está destinado a pruebas puntuales.  
- **Legalidad**: Escanear sin consentimiento puede violar leyes como la CFAA (EE.UU.) o GDPR (UE).  

---

### **5. Conclusión**  
Nmap es una herramienta poderosa para diagnóstico de redes y seguridad. Dominar sus técnicas permite identificar riesgos y fortalecer infraestructuras. Úsala con responsabilidad y ética.  

```markdown
# Recursos Adicionales  
- Documentación Oficial: https://nmap.org/docs.html  
- Guía de NSE: https://nmap.org/book/nse.html
- https://raul-profesor.github.io/Curso-especialista-ciberseguridad/segof/nmap101/

```


3. **Cuestionario sobre Nmap: Técnicas y Uso**  
*(Respuestas al final)*  

---

### **Preguntas**  
1. ¿Qué es Nmap y cuál es su propósito principal?  
2. Describe cómo funciona el **escaneo TCP SYN** (`-sS`) y menciona por qué requiere privilegios de root.  
3. Explica la diferencia entre un **escaneo TCP Connect** (`-sT`) y un **escaneo TCP SYN** (`-sS`).  
4. ¿Por qué el **escaneo UDP** (`-sU`) es considerado más lento que otros tipos de escaneo?  
5. ¿Qué comando usarías para detectar la versión de los servicios en puertos abiertos de un objetivo?  
6. ¿Cómo se realiza la detección del sistema operativo de un host con Nmap? Proporciona un ejemplo de comando.  
7. Menciona dos scripts comunes de **NSE (Nmap Scripting Engine)** y su utilidad.  
8. ¿Qué significa el modo de temporización `-T4` en Nmap y en qué situaciones se recomienda usarlo?  
9. ¿Cómo guardarías los resultados de un escaneo en formato de texto con el nombre `resultado.txt`?  
10. ¿Por qué es importante obtener autorización antes de usar Nmap en una red ajena?  

---
**Nota:**  
- Practica siempre en entornos autorizados (como `scanme.nmap.org`).  
- Revisa la documentación oficial (**https://nmap.org**) para profundizar en técnicas avanzadas.

### **NMAP EJEMPLO USO DE SCRIPT'S**

**Script ssh-hostkey**

**ssh-hostkey** es una herramienta poderosa para obtener información sobre las **claves de host SSH** de un servidor objetivo. 

## **Funcionamiento y ejemplo práctico aplicado a la cibersegurida**.

---

### **¿Qué hace el script `ssh-hostkey` de nmap?**
Este script se conecta al servicio SSH (puerto 22 por defecto) y extrae:
- Las **claves públicas del host** (RSA, ECDSA, Ed25519, etc.).
- **Huellas digitales** (fingerprints) de las claves (en formatos MD5, SHA1, SHA256).
- Detalles como el **tipo de algoritmo**, tamaño de clave (bits), y en algunos casos, si las claves son **predeterminadas** (p. ej., claves generadas durante la instalación de OpenSSH).

---

### **¿Para qué sirve en hacking ético?**
1. **Reconocimiento inicial**: Identificar servidores SSH expuestos y su configuración.
2. **Fingerprinting**: Determinar la "identidad única" del servidor (las claves son como su huella digital).
3. **Detectar vulnerabilidades**:
   - Claves SSH **débiles** (ej: RSA de 1024 bits).
   - Claves **predeterminadas** (usadas en dispositivos IoT o imágenes de servidor no personalizadas).
   - Algoritmos **obsoletos** (ej: DSA).
4. **Identificar suplantación (spoofing)**: Si la clave del host cambió repentinamente, podría indicar un ataque MITM o un servidor malicioso.

---

### **Uso práctico con nmap**
#### **Comando básico**:
```bash
nmap -p 22 --script ssh-hostkey <target_ip_or_domain>
```

#### **Ejemplo de salida**:
```
Host script results:
| ssh-hostkey: 
|   2048 SHA256:Abc123...xyz (RSA)
|   256  SHA256:Def456...uvw (ECDSA)
|_  256  SHA256:Ghi789...rst (ED25519)
```

#### **Opciones avanzadas**:
- **Mostrar todos los formatos de huella**:
  ```bash
  nmap -p 22 --script ssh-hostkey --script-args ssh-hostkey=all <target>
  ```
- **Comparar con claves conocidas**:
  ```bash
  nmap -p 22 --script ssh-hostkey --script-args ssh-hostkey=known <target>
  ```

---

### **Casos de uso en hacking ético**
#### 1. **Auditar seguridad de claves SSH**
   - **Objetivo**: Encontrar claves RSA de 1024 bits (débiles) o algoritmos inseguros.
   - **Acción ética**: Reportar al administrador para actualizar a Ed25519 o RSA-4096.

#### 2. **Identificar dispositivos por claves predeterminadas**
   - **Ejemplo**: Muchos routers, cámaras IP o dispositivos IoT usan claves SSH predeterminadas.
   - **Comando**:
     ```bash
     nmap -p 22 --script ssh-hostkey --script-args ssh-hostkey=full <target>
     ```
   - **Acción ética**: Si se detectan claves predeterminadas, recomendar regenerarlas.

#### 3. **Detectar servidores no autorizados**
   - **Ejemplo**: En una red corporativa, escanear todos los hosts para encontrar servicios SSH no documentados.
   - **Comando**:
     ```bash
     nmap -p 22 --script ssh-hostkey 192.168.1.0/24
     ```

#### 4. **Verificar si un servidor ha sido comprometido**
   - **Indicio**: Si la clave SSH del host cambió sin autorización, podría ser una señal de intrusión.
   - **Acción ética**: Comparar la huella SHA256 actual con un registro previo.

---

### **Ejemplo práctico completo**
**Escenario**: Auditoría de seguridad en una red interna.
1. **Escaneo de hosts con SSH activo**:
   ```bash
   nmap -p 22 -sV 192.168.1.0/24
   ```
2. **Ejecutar `ssh-hostkey` en los hosts encontrados**:
   ```bash
   nmap -p 22 --script ssh-hostkey --script-args ssh-hostkey=all 192.168.1.10
   ```
3. **Analizar resultados**:
   - Si se detecta una clave RSA de 1024 bits:
     - **Riesgo**: Vulnerable a ataques de fuerza bruta o robo de clave.
     - **Recomendación en el informe**: Migrar a Ed25519 o RSA-4096.

---

### **Consideraciones éticas**
- **Permiso explícito**: Solo usa este script en redes o sistemas donde tengas autorización por escrito.
- **No alterar el sistema**: El script es pasivo (solo lee información), pero asegúrate de no violar políticas de uso.
- **Proteger la información**: Las claves públicas no son sensibles, pero guárdalas de forma segura para evitar ingeniería inversa.

---

### **Herramientas complementarias**
- **ssh-audit**: Herramienta especializada para auditar configuraciones SSH (recomendada para análisis profundos).
- **Metasploit**: Módulos como `auxiliary/scanner/ssh/ssh_version` para obtener detalles de SSH.

---

### **Conclusión**
El script `ssh-hostkey` de nmap es una **primera línea de reconocimiento** útil para:
- Identificar configuraciones SSH inseguras.
- Detectar dispositivos con claves predeterminadas.
- Generar un inventario de servicios SSH en la red.

En un pentest ético, esta información se usa para **priorizar vulnerabilidades** y recomendar hardening (ej: deshabilitar algoritmos obsoletos). ¿Quieres profundizar en algún punto? 
