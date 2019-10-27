# Kali-Linux
Estudio de Kali-Linux

## Índice
Aquí trataremos de los siguientes apartados
1. Descripción de Kali-Linux
2. Sistema Operativo en el que esta basado Kali-Linux
3. Herramientas de Kali-Linux
3.1 Wireshark
3.2 Armitage

## 1.Descripción
Kali Linux es una distribución basada en Debian GNU/Linux diseñada principalmente para la auditoría y seguridad informática en general. Fue fundada y es mantenida por Offensive Security Ltd. Mati Aharoni y Devon Kearns, ambos pertenecientes al equipo de Offensive Security, desarrollaron la distribución a partir de la reescritura de BackTrack, que se podría denominar como la antecesora de Kali Linux.

Kali Linux trae preinstalados más de 600 programas incluyendo Nmap (un escáner de puertos), Wireshark (un sniffer), John the Ripper (un crackeador de passwords) y la suite Aircrack-ng (software para pruebas de seguridad en redes inalámbricas). Kali puede ser usado desde un Live CD, live-usb y también puede ser instalada como sistema operativo principal.

Kali es desarrollado en un entorno seguro; el equipo de Kali está compuesto por un grupo pequeño de personas de confianza quienes son los que tienen permitido modificar paquetes e interactuar con los repositorios oficiales. Todos los paquetes de Kali están firmados por cada desarrollador que lo compiló y publicó. A su vez, los encargados de mantener los repositorios también firman posteriormente los paquetes utilizando GNU Privacy Guard.

Kali se distribuye en imágenes ISO compiladas para diferentes arquitecturas (32/64 bits y ARM).

## 2.Sistema Operativo en el que está basado
Debian GNU/Linux es un sistema operativo libre, desarrollado por miles de voluntarios de todo el mundo, que colaboran a través de Internet.

La dedicación de Debian al software libre, su base de voluntarios, su naturaleza no comercial y su modelo de desarrollo abierto la distingue de otras distribuciones del sistema operativo GNU. Todos estos aspectos y más se recogen en el llamado Contrato Social de Debian.

Nació en el año 1993, de la mano del proyecto Debian, con la idea de crear un sistema GNU usando Linux como núcleo ya que el proyecto Debian, organización responsable de su mantenimiento en la actualidad, también desarrolla sistemas GNU basados en otros núcleos (Debian GNU/Hurd, Debian GNU/NetBSD y Debian GNU/kFreeBSD).

Uno de sus principales objetivos es separar en sus versiones el software libre del software no libre. El modelo de desarrollo es independiente a empresas, creado por los propios usuarios, sin depender de ninguna manera de necesidades comerciales. Debian no vende directamente su software, lo pone a disposición de cualquiera en Internet, aunque sí permite a personas o empresas distribuir comercialmente este software mientras se respete su licencia.

Debian GNU/Linux puede instalarse utilizando distintos mecanismos de instalación, como DVD, CD, USB, e incluso directamente desde la red (Este último depende de la velocidad de la red del usuario).

## 3. Herramientas de Kali-Linux
### 3.1 Wireshark (https://www.wireshark.org/)
Este programa es todo un clásico en el mundo de la seguridad informática y no podía faltar en Kali Linux. Este programa se encarga de analizar paquetes de tu red, los cuales luego puedes abrir y ver de manera detallada lo que significa. Por ejemplo si alguien ha metido su usuario y su contraseña en una web(que no esté cifrada), podrás ver ese usuario y esa contraseña analizando el paquete.

### 3.2  Armitage (https://www.dragonjar.org/manual-de-armitage-en-espanol.xhtml)
Este programa es una GUI de ataques Metasploit, la cual te permitirá hacer estos ataques de una forma visual e intuitiva. Con esta aplicación, podremos comprobar si nuestros equipos son vulnerables o no a sploits. Además de poder ejecutar ataques metasploit sin saber comandos, también podremos hacer análisis de Nmap e incluso hacer ataques de fuerza bruta.

## Referencias
[1.Descripción] (https://es.wikipedia.org/wiki/Kali_Linux)

[2. Sistema Operativo basado ] (https://es.wikipedia.org/wiki/Debian_GNU/Linux)

[3. Herramientas] (https://www.linuxadictos.com/las-5-mejores-herramientas-encontraremos-kali-linux.html)
