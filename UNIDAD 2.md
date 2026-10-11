## Actividad 1
#### Que es clasificar poor alcance?
Una forma comun de clasificar redes es por el tamaño del area que cubren: de un dispositivo personal una red que conecta ciudades enteras.

#### Que es una PAN?
Una pan conecta dispositivos dentro de un especio fisico unico: una casa

#### Que es una LAN?
LAN conecta dispositivos dentro de un espacio fisico unico: una casa, una oficina, un salon de clases o un solo edificio.

#### Caracteristicas LAN: 
Es la red que una sopla organizacion controla y administra por completo; suele tener alta velocidad y bajo costo por su alcance limitado.

#### Que es una WLAN?
Es una LAN que usa el espectro radioelectronico en lugar de cables para conectar los dispositivos dentro del mismo espacio.

##### Caracteristicas WLAN:
El acceso se hace a traves de uno o mas puntos de acceso (AP); a c a,mbio de movilidad, el medio es compartiod y mas sensible a interferencia.

#### Que es una WAN?
Conecta redes que estan geograficamente distantes, a veces en distintas ciudades, paises, continentes.

##### Caracteristicas:
Ya no la administra una sola organizacion: suele depender de proveedores de telecomunicaciones, y su costo y latencia son mayores que una LAN.

Comparacion por alcance de menor a mayor cbertura: PAN(una persona) -> LAN/WLAN (un edificio) -> Campues area network (varios edificios de una organizacion) -> WAN (distintas ciudades o paises).

La pregunta que las distingue no es la tecnologia que usan es quien la maneja y que alcance tiene.

## Actividad 2

9-29-2026
![[analiarredes]]
#### INTERNET

Es la red de redes: millones de WAN, LAN y redes de proveedores distintos, interconectadas y funcionando bajo mismo conjunto de protocolos.

##### Que es?
Ninguna empresa ni gobierno aministra internet como un todo; cada red que la compone es aministrada de forma independiente y se conecta a las demas por acuerdo mutuo.

##### Que lo hace funcionar?
TCP/IP: Protocolo que dice como tienen que 

##### Como se conectan las redes entre si?
A traves de proveedores de internet (ISP) organizados en niveles: los ISP locales se conectan a otros mas grandes y estos entre si hasta formar la red global.

Puntos de intercambio (IXP) sitios fisicos donde distintos ISP conetan su trafico directamente entre si en lugar de enviarlo por una ruta mas larga reducen latencia y costo de trafico.

##### ¿Por qué el Internet es considerado una infraestructura?
Porque funciona como la base fundamental y el soporte técnico que permite la presentación de servicios esenciales en la sociedad moderna. Es una red física y lógica que sostiene la actividad económica social y gubernamental de un país.

##### Backbone
También conocida como red troncal, es la infraestructura principal de alta capacidad y velocidad que interconecta redes más pequeñas y transporta datos a través de ciudades, países y continentes.

![[Pasted image 20261001161407.png]]
![[Pasted image 20261001162606.png]]

##### Servicios que corren sobre internet
Internet es la infraestructura; la Web, el correo electrónico, el streaming y la mensajería son aplicaciones que se ejecutan sobre ella, no la red misma.

*¿El Internet es la WAN más grande del mundo?*
Sí.

### Protocolo TCP-IP

![[Pasted image 20261006192427.png]]![[Pasted image 20261006192455.png]]

Modelo de cuatro capas que describe cómo se comunican los dispositivos en una red real; a diferencia de OSI, sí se implementa tal cual en Internet y en la mayoría de las redes actuales.

Nació del proyecto ARPANET en los años setenta, antes que el modelo OSI; por eso es el modelo práctico, construido desde la implementación y no desde la teoría.

##### Capa de Aplicación
Es donde viven los programas y servicios que el usuario reconoce: navegación web, correo, mensajería. Agrupa lo que en OSI son tres capas separadas: aplicación, presentación y sesión.

##### Capa de Transporte
Divide el mensaje en segmentos, agrega número de puerto de origen y destino, y decide si la entrega necesita confirmación (TCP) o no (UDP).

##### Capa de Internet
Agrega las direcciones IP de origen y destino y es responsable de que el paquete encuentre su ruta entre redes distintas; aquí vive el protocolo IP.

##### Capa de Acceso a la red
Agrega la dirección MAC del siguiente salto y convierte los datos en señal para el medio físico; agrupa lo que en OSI son las capas de enlace y física.