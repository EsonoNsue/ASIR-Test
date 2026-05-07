## Preguntas tipo test - Redes

###BLOQUE A

###1. **¿Cuál es la capa del modelo OSI responsable de enrutar paquetes entre redes?**  
   - [ ] Enlace de datos  
   - [x] Red  
   - [ ] Transporte  
   - [ ] Aplicación 

###2. **En el modelo TCP/IP, ¿en qué capa se ubican TCP y UDP?**  
   - [ ] Acceso a la red  
   - [ ] Internet  
   - [x] Transporte  
   - [ ] Aplicación  

###3. **¿Qué protocolo se encarga de traducir una dirección IP a una dirección MAC en una LAN?**  
   - [ ] ICMP  
   - [ ] DNS  
   - [ ] DHCP  
   - [x] ARP  

###4. **¿Qué campo de una trama Ethernet se usa para detectar errores?**  
   - [ ] Tipo/Longitud  
   - [ ] Preamble  
   - [x] FCS (CRC)  
   - [ ] Dirección MAC origen  

###5. **¿Cuál es el tamaño clásico del campo de direcciones MAC en Ethernet?**  
   - [ ] 4 bytes  
   - [x] 6 bytes  
   - [ ] 8 bytes  
   - [ ] 16 bytes  

###6. **¿Cuál es la forma abreviada correcta y más compacta de la dirección IPv6 2001:0db8:0000:0000:0000:00a0:0000:1c20?**  
   - [ ] 2001:db8:0:0:a0:0:0:1c20  
   - [ ] 2001:db8::0a0::1c20  
   - [x] 2001:db8::a0:0:1c20  
   - [ ] 2001::db8:a0::1c20  

###7. **¿Qué estándar define Ethernet?**  
   - [ ] IEEE 802.11  
   - [x] IEEE 802.3  
   - [ ] IEEE 802.1Q  
   - [ ] IEEE 802.1D  

###8. **¿Qué método de acceso al medio describía Ethernet clásico?**  
   - [ ] CSMA/CA  
   - [ ] Token Passing  
   - [x] CSMA/CD  
   - [ ] TDMA  

###9. **¿Qué cable usarías para conectar un PC a un switch en redes actuales?**  
   - [ ] Cruzado (cross-over)  
   - [x] Directo (straight-through)  
   - [ ] Serial DCE  
   - [ ] Coaxial  

###10. **¿Qué tecnología hace innecesario, en muchos casos, distinguir entre cable directo y cruzado?**  
   - [ ] PortFast  
   - [x] Auto-MDI/MDIX  
   - [ ] LACP  
   - [ ] VTP pruning  

###11. **¿Cuál de estas categorías de cobre soporta 10 Gbps hasta 100 m de forma típica en entornos controlados?**  
   - [ ] Cat 5e  
   - [ ] Cat 6 (≤55 m)  
   - [x] Cat 6A  
   - [ ] Cat 3  

###12. **¿Qué tipo de fibra se recomienda para distancias de decenas de kilómetros?**  
   - [ ] Multimodo (MMF)  
   - [x] Monomodo (SMF)  
   - [ ] UTP  
   - [ ] STP  

###13. **¿Qué conector de fibra es pequeño y muy usado en alta densidad?**  
   - [ ] BNC  
   - [x] LC  
   - [ ] RJ-11  
   - [ ] VGA  

###14. **En una topología en estrella, el dispositivo central suele ser:**  
   - [x] Un hub o switch  
   - [ ] Un router exclusivamente  
   - [ ] Un repetidor  
   - [ ] Un módem  

###15. **¿Qué topología proporciona mayor redundancia de caminos?**  
   - [ ] Bus  
   - [ ] Anillo  
   - [ ] Árbol  
   - [x] Malla  

###16. **¿Qué dispositivo reduce dominios de colisión creando uno por puerto?**  
   - [ ] Hub  
   - [x] Switch  
   - [ ] Repetidor  
   - [ ] Punto de acceso (AP)  

###17. **¿Qué dispositivo separa dominios de broadcast?**  
   - [ ] Switch capa 2  
   - [ ] Hub  
   - [x] Router  
   - [ ] Bridge  

###18. **¿Cuál es una dirección IPv4 privada clase A?**  
   - [ ] 172.31.0.0/16  
   - [ ] 192.168.0.0/24  
   - [x] 10.0.0.0/8  
   - [ ] 169.254.0.0/16  

###19. **¿Cuál es la dirección de loopback en IPv4?**  
   - [ ] 0.0.0.0  
   - [ ] 255.255.255.255  
   - [x] 127.0.0.1  
   - [ ] 224.0.0.1  

###20. **¿Qué clase IPv4 tiene máscara por defecto 255.255.0.0?**  
   - [ ] Clase A  
   - [x] Clase B  
   - [ ] Clase C  
   - [ ] Clase D  

---
###BLOQUE B

###1. **¿Qué significa 0.0.0.0 en una tabla de rutas?**  
   - [ ] Broadcast limitado  
   - [x] Ruta por defecto  
   - [ ] Loopback  
   - [ ] Multicast  

###2. **¿Cuál es el rango de red privada clase B?**  
   - [x] 172.16.0.0 – 172.31.255.255  
   - [ ] 10.0.0.0 – 10.255.255.255  
   - [ ] 192.168.0.0 – 192.168.255.255  
   - [ ] 100.64.0.0 – 100.127.255.255  

###3. **¿Qué máscara por defecto corresponde a una red clase C?**  
   - [ ] 255.0.0.0  
   - [ ] 255.255.0.0  
   - [x] 255.255.255.0  
   - [ ] 255.255.255.128  

###4. **La dirección de broadcast de una subred se obtiene:**  
   - [ ] AND IP con máscara  
   - [x] OR IP con inverso (NOT) de la máscara  
   - [ ] XOR IP con máscara  
   - [ ] Sumando 1 a la IP de red  

###5. **En IPv6, ¿qué notación permite abreviar ceros consecutivos una única vez?**  
   - [ ] :0:  
   - [x] ::  
   - [ ] :00:  
   - [ ] :ffff:  

###6. **¿Qué prefijo identifica direcciones unicast globales en IPv6?**  
   - [ ] fc00::/7  
   - [ ] fe80::/10  
   - [ ] ff00::/8  
   - [x] 2000::/3  

###7. **¿Qué tipo de dirección IPv6 es fe80::/10?**  
   - [ ] Unicast global  
   - [ ] Multicast  
   - [x] Link-local (local de enlace)  
   - [ ] Unique local (local único)  

###8. **¿Cuál es el tipo de dirección IPv6 destinada a múltiples receptores específicos?**  
   - [ ] Anycast  
   - [x] Multicast  
   - [ ] Unicast  
   - [ ] Broadcast  

###9. **En Wi-Fi, ¿qué banda suele ofrecer mayor alcance pero más interferencias?**  
   - [ ] 5 GHz  
   - [x] 2.4 GHz  
   - [ ] 6 GHz  
   - [ ] 60 GHz  

###10. **¿Cuál es el estándar comercialmente llamado Wi-Fi 6?**  
   - [ ] 802.11ac  
   - [ ] 802.11n  
   - [x] 802.11ax  
   - [ ] 802.11be  

###11. Seguridad Wi-Fi
    **¿Qué protocolo de seguridad Wi‑Fi es el recomendado actualmente para redes personales?**
   - [ ] WEP
   - [ ] WPA
   - [ ] WPA2-PSK
   - [x] **WPA3-Personal**

###12. Configuración de AP
**¿Cuál de las siguientes es una buena práctica al configurar un AP doméstico?**
   - [ ] Usar WEP por compatibilidad
   - [ ] Ocultar SSID siempre
   - [x] **Usar WPA3 si es posible**
   - [ ] Canales aleatorios diarios

###13. Conceptos de VLAN
**¿Qué es una VLAN?**
   - [ ] Una red física independiente
   - [x] **Una red lógica dentro de una LAN física**
   - [ ] Un protocolo de routing
   - [ ] Un tipo de cableado

###14. Puertos de Switch
**Un puerto configurado como *access* en un switch:**
   - [ ] Transporta múltiples VLAN con etiquetas
   - [x] **Pertenece a una sola VLAN y envía tráfico sin etiquetar**
   - [ ] Es únicamente para uplinks
   - [ ] Solo admite VLAN de voz

###15. Troncales (Trunks)
**Un enlace *trunk* 802.1Q:**
   - [ ] Bloquea el tráfico de gestión
   - [x] **Transporta varias VLAN etiquetadas**
   - [ ] Solo sirve para VLAN nativa
   - [ ] No se usa entre switches

###16. VLAN Nativa
**La VLAN nativa en 802.1Q se usa para:**
   - [ ] Tráfico etiquetado de control
   - [x] **Tráfico sin etiquetar en el trunk**
   - [ ] Tráfico de voz únicamente
   - [ ] Bloquear BPDUs

###17. Inter-VLAN Routing
**¿Qué permite comunicar VLANs distintas sin usar un router externo?**
   - [ ] Switch capa 2
   - [x] **Switch capa 3 con SVI**
   - [ ] Hub
   - [ ] Bridge

###18. Router-on-a-stick
**Router-on-a-stick requiere:**
   - [ ] Interfaz física por VLAN
   - [x] **Subinterfaces y encapsulation dot1Q**
   - [ ] STP deshabilitado
   - [ ] NAT en el mismo enlace
 
###19. Protocolo OSPF
**Un ABR (*Area Border Router*) en OSPF:**
   - [x] **Conecta distintas áreas OSPF**
   - [ ] Redistribuye rutas externas
   - [ ] Es siempre el DR
   - [ ] Solo enruta tráfico multicast

###20. Capa de Enlace
**¿Qué protocolo evita bucles en redes conmutadas con enlaces redundantes?**
   - [ ] LACP
   - [x] **STP (Spanning Tree Protocol)**
   - [ ] VTP
   - [ ] HSRP

---
### BLOQUE C


###1. Spanning Tree Protocol (STP)
**El switch que sirve de referencia en STP se llama:**
   - [ ] Designated Switch
   - [ ] Backup Bridge
   - [x] **Root Bridge**
   - [ ] Master Switch

### 2. Roles de Puerto en STP
**En STP, ¿qué puerto reenvía tráfico hacia/desde un segmento?**
   - [ ] Root Port
   - [x] **Designated Port**
   - [ ] Blocked Port
   - [ ] Alternate Port

### 3. Evolución de STP
**¿Qué versión proporciona convergencia más rápida que STP clásico?**
   - [ ] PVST+ (802.1D)
   - [x] **RSTP (802.1w)**
   - [ ] MSTP (802.1s)
   - [ ] VTP v3

### 4. Gestión de VLAN (VTP)
**¿Para qué sirve VTP?**
   - [ ] Propagar rutas entre switches
   - [x] **Centralizar gestión de VLANs entre switches Cisco**
   - [ ] Balancear carga por enlaces
   - [ ] Evitar bucles de capa 2

### 5. Modos de VTP
**En VTP, ¿qué modo permite crear y borrar VLANs que se propagan?**
   - [ ] Client
   - [ ] Transparent
   - [x] **Server**
   - [ ] Off

### 6. Optimización de VTP
**¿Qué opción de VTP reduce la difusión de broadcast a VLAN presentes en los enlaces?**
   - [ ] VTP hashing
   - [x] **VTP pruning**
   - [ ] VTP relay
   - [ ] VTP mirror

### 7. Protocolo DHCP
**El proceso DHCP se recuerda por ‘DORA’. ¿Qué significa la ‘O’?**
   - [x] **Offer**
   - [ ] Open
   - [ ] Operate
   - [ ] Override

### 8. Capa de Transporte
**DHCP opera, a nivel de transporte, sobre:**
   - [ ] TCP
   - [x] **UDP**
   - [ ] SCTP
   - [ ] ICMP

### 9. Mensajería de Red
  **ICMP se utiliza para:**
   - [ ] Transferir archivos
   - [x] **Diagnóstico y mensajes de error**
   - [ ] Autenticación de usuarios
   - [ ] Cifrado de datos

### 10. Seguridad en Capa 2
  **El ataque que falsifica respuestas ARP para realizar MITM se denomina:**
   - [ ] ARP Split
   - [ ] ARP Snooping
   - [x] **ARP Spoofing/Poisoning**
   - [ ] ARP Tunneling

### 11. Seguridad ARP
**¿Cuál NO es una medida contra ARP Spoofing?**
   - [ ] Dynamic ARP Inspection
   - [ ] DHCP Snooping
   - [ ] ARP estático
   - [x] **Usar Telnet en lugar de SSH**

### 12. NAT/PAT
**NAT/PAT permite:**
   - [x] **Asignar una IP pública única a múltiples hosts internos mediante puertos**
   - [ ] Evitar el uso de ACLs
   - [ ] Sustituir el routing dinámico
   - [ ] Cifrado extremo a extremo

### 13. Tipos de NAT
**¿Qué tipo de NAT cambia la dirección de destino (primer paquete)?**
   - [ ] SNAT
   - [x] **DNAT**
   - [ ] PAT
   - [ ] NAT64

### 14. Conceptos Cisco NAT
**En Cisco IOS, el término *overload* en NAT se refiere a:**
   - [ ] NAT estático
   - [ ] NAT dinámico sin puertos
   - [x] **PAT (traducción por puertos)**
   - [ ] Deshabilitar NAT

### 15. Puertos de Red
**Los puertos bien conocidos (*well-known*) abarcan el rango:**
   - [x] **0–1023**
   - [ ] 1024–49151
   - [ ] 49152–65535
   - [ ] 10000–20000

### 16. Protocolos Web
**El puerto TCP estándar para HTTPS es:**
   - [ ] 80
   - [ ] 21
   - [ ] 22
   - [x] **443**

### 17. Herramientas de Diagnóstico
**¿Qué comando en Windows muestra conexiones y puertos abiertos?**
   - [ ] route print
   - [ ] ipconfig /all
   - [x] **netstat -na**
   - [ ] arp -a

### 18. Acceso Remoto Seguro
**SSH frente a Telnet:**
   - [ ] Ambos cifran igual
   - [x] **SSH cifra, Telnet no**
   - [ ] Telnet cifra, SSH no
   - [ ] Ninguno cifra

### 19. Configuración en Cisco
**Para habilitar SSH en equipos Cisco es necesario, entre otros pasos:**
   - [x] **Configurar hostname y dominio, y generar claves RSA**
   - [ ] Activar Telnet en VTY
   - [ ] Desactivar AAA
   - [ ] Usar puerto 23 obligado

### 20. Sistema de Archivos Cisco IOS
**¿Cuál NO es un archivo típico en Cisco IOS?**
   - [ ] running-config
   - [ ] startup-config
   - [ ] IOS image
   - [x] **boot.ini**
---

###BLOQUE D

### 1. Proceso de Arranque Cisco
**¿Cuál es el orden típico de arranque en un router Cisco?**
   - [ ] IOS → POST → Bootstrap → Config
   - [x] **POST → Bootstrap → IOS → Config**
   - [ ] Bootstrap → POST → IOS → Config
   - [ ] POST → IOS → Bootstrap → Config

### 2. Routing Estático
**Una ruta estática por defecto en Cisco se configura con:**
   - [x] **ip route 0.0.0.0 0.0.0.0 <next-hop>**
   - [ ] default-route enable
   - [ ] ip default-network <red>
   - [ ] route add 0.0.0.0/0 gw <ip>

### 3. Protocolo RIP
**RIP utiliza como métrica:**
   - [ ] Ancho de banda
   - [ ] Retardo
   - [x] **Saltos (hops)**
   - [ ] Costo acumulado SPF

### 4. Protocolo OSPF
**OSPF es un protocolo de:**
   - [ ] Vector distancia
   - [x] **Estado de enlace (link-state)**
   - [ ] Path-vector
   - [ ] Inundación pura

### 5. Protocolo EIGRP
**EIGRP es:**
   - [ ] Un IGP abierto de estado de enlace
   - [x] **Propietario de Cisco, híbrido con DUAL**
   - [ ] Un EGP de backbone
   - [ ] Equivalente a BGP

### 6. Protocolo BGP
**BGP intercambia rutas sobre:**
   - [ ] UDP 520
   - [x] **TCP 179**
   - [ ] TCP 22
   - [ ] UDP 67/68

### 7. Atributos BGP
**¿Cuál NO es un atributo típico de BGP?**
   - [ ] AS-PATH
   - [ ] LOCAL_PREF
   - [ ] MED
   - [x] **Hop Count**

### 8. Comandos de Verificación
**¿Qué comando muestra la tabla de rutas en un router Cisco?**
   - [ ] show interfaces
   - [x] **show ip route**
   - [ ] show ip protocols
   - [ ] show arp

### 9. Áreas OSPF
**En OSPF, el área backbone es:**
   - [ ] Área 1
   - [ ] Área 10
   - [x] **Área 0**
   - [ ] Cualquier área con DR/BDR

### 10. Funcionamiento de OSPF
**En OSPF, ¿quién mantiene una base de datos de estado de enlace (LSDB)?**
   - [ ] Solo el DR
   - [x] **Cada router dentro del área**
   - [ ] Solo ABR
   - [ ] Solo ASBR

### 11. Algoritmos de Routing
**En EIGRP, ¿qué algoritmo elige rutas libres de bucles y rápidas en converger?**
   - [ ] SPF (Dijkstra)
   - [ ] Bellman-Ford
   - [x] **DUAL**
   - [ ] Floyd–Warshall

### 12. ACL Estándar
**Una ACL estándar en Cisco filtra basándose en:**
   - [x] **IP origen únicamente**
   - [ ] IP origen y destino
   - [ ] Protocolo y puertos
   - [ ] Dirección MAC

### 13. ACL Extendida
**Una ACL extendida puede filtrar por:**
   - [ ] Solo IP origen
   - [x] **IP origen/destino, protocolo y puerto**
   - [ ] Solo MAC destino
   - [ ] Solo ICMP

### 14. Aplicación de ACL
**¿Dónde se aplican las ACL en Cisco?**
   - [x] **En interfaces, dirección in/out**
   - [ ] Solo en VTY
   - [ ] Solo en consola
   - [ ] En el plano de control exclusivamente

### 15. Seguridad en ACL
**La política implícita al final de una ACL es:**
   - [ ] permit ip any any
   - [x] **deny ip any any**
   - [ ] permit tcp any any
   - [ ] deny icmp any any

### 16. Registros DNS (IPv4)
**El registro DNS que asocia un nombre a IPv4 es:**
   - [ ] AAAA
   - [ ] MX
   - [x] **A**
   - [ ] CNAME

### 17. Servidores DNS
**¿Qué registro DNS define el servidor autoritativo de una zona?**
   - [x] **SOA y NS**
   - [ ] TXT
   - [ ] PTR
   - [ ] SRV

### 18. DNS Inverso
**El dominio inverso para IPv4 se gestiona bajo:**
   - [x] **in-addr.arpa**
   - [ ] ip6.arpa
   - [ ] arpa.in-addr
   - [ ] reverse.dns

### 19. Jerarquía DNS
**¿Cuál es el orden jerárquico de DNS?**
   - [ ] Zona → Dominio raíz → TLD
   - [x] **Dominio raíz → TLD → dominios de segundo nivel**
   - [ ] TLD → Dominio raíz → Subdominio
   - [ ] Autoritativo → Recursivo → Cliente

---

### 20. Cableado Estructurado
**En cableado estructurado, ¿cuál NO es un subsistema ISO/IEC 11801?**
   - [ ] Entrada de edificio
   - [ ] Backbone vertical
   - [ ] Área de trabajo
   - [x] **Capa de aplicación**


