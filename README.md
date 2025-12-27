# Diseño e Implementación de Infraestructura de Red para SENASA – Arequipa

## Descripción
Este proyecto consiste en el diseño y simulación de una infraestructura de red para el Servicio Nacional de Sanidad Agraria (SENASA) en la región de Arequipa, utilizando la herramienta Cisco Packet Tracer. El objetivo principal es proponer una solución de conectividad eficiente que permita la intercomunicación entre cinco sedes regionales, facilitando el intercambio de información, la coordinación operativa y la gestión de datos a nivel regional.

La propuesta surge a partir del análisis de la situación actual de las sedes de SENASA en Arequipa, las cuales presentan una infraestructura de red no consolidada, dificultando la comunicación fluida entre ellas y con la sede central ubicada en Lima. Mediante este proyecto se plantea una red estructurada, escalable y funcional que mejora la conectividad regional.

---

## Entidad
El Servicio Nacional de Sanidad Agraria (SENASA) es un organismo público encargado de proteger y mejorar la sanidad agraria del país. Sus funciones incluyen el control de plagas y enfermedades, la supervisión del uso de productos agroquímicos y la certificación sanitaria para la importación y exportación de productos agropecuarios. Para cumplir estas funciones, SENASA cuenta con múltiples sedes distribuidas estratégicamente a nivel nacional.

---

## Sedes consideradas en el proyecto
El diseño de la red abarca las siguientes sedes ubicadas en el departamento de Arequipa:

- SENASA Arequipa – Cerro Colorado  
- Puesto de Control SENASA Cabrerías  
- Oficina SENASA Majes  
- Puesto de Control Cuarentenario Interno Talamolle  
- Puesto Policial / Puesto de Control SENASA Chiguata  

Cada sede fue analizada considerando su ubicación geográfica, cantidad de equipos y necesidades de conectividad.

---

## Análisis de la situación actual
SENASA cuenta con una sede central en Lima que concentra la información a nivel nacional. Sin embargo, las sedes de Arequipa presentan limitaciones en su infraestructura de red, lo que dificulta el intercambio de información y la coordinación regional.

A nivel de hardware, se identificó que la región Arequipa dispone de aproximadamente 54 computadoras de escritorio y 5 laptops, distribuidas entre las distintas sedes. Esta infraestructura requiere una red que garantice conectividad confiable, organizada y segura.

---

## Problema identificado
La principal problemática detectada es la **limitada conectividad entre las sedes de SENASA en Arequipa**, lo cual impide una comunicación eficiente y oportuna entre ellas. Esta situación afecta la colaboración regional, la actualización de información crítica y la coordinación de actividades operativas.

---

## Objetivos

### Objetivo general
Diseñar e implementar una red eficiente que permita la conectividad entre las cinco sedes de SENASA en la región de Arequipa, mejorando la comunicación y el intercambio de datos.

### Objetivos específicos
- Seleccionar una topología de red adecuada para la interconexión de las sedes.
- Diseñar un esquema de direccionamiento IP eficiente mediante subneteo.
- Configurar los dispositivos de red (routers, switches, PCs y laptops).
- Simular el funcionamiento de la red utilizando Cisco Packet Tracer.

---

## Marco teórico

### Redes de computadoras
Una red de computadoras es un conjunto de dispositivos interconectados que permiten compartir información, recursos y servicios. Según su alcance, las redes pueden clasificarse como LAN, MAN o WAN.

### Topologías de red
La topología define la forma en que los dispositivos están interconectados. Entre las principales topologías se encuentran estrella, bus, anillo, malla e híbrida. Para este proyecto se optó por una topología que garantice facilidad de administración y escalabilidad.

### Cableado estructurado
El cableado estructurado permite la transmisión eficiente de datos, voz y video. Incluye el uso de cables UTP, fibra óptica, racks y patch panels para una correcta organización de la infraestructura.

### Direccionamiento IP y subneteo
El direccionamiento IP permite identificar de manera única a cada dispositivo en la red. Se empleó IPv4 junto con técnicas de subneteo para optimizar el uso de direcciones IP y segmentar la red de manera adecuada.

### Equipos de red
Se utilizaron dispositivos como routers, switches y routers inalámbricos para garantizar la interconexión entre las distintas sedes y los dispositivos finales.

### Protocolos de enrutamiento
Los protocolos de enrutamiento permiten el intercambio de información de rutas entre routers. En el diseño se consideraron protocolos como RIP, EIGRP y OSPF, seleccionando el más adecuado para el escenario simulado.

### Simulación de redes
La simulación mediante Cisco Packet Tracer permite validar el diseño de la red antes de su implementación física, verificando conectividad, enrutamiento y funcionamiento general.

---

## Diseño de la red

### Topología general
Se diseñó una topología lógica y física que interconecta las cinco sedes de SENASA en Arequipa, garantizando comunicación entre ellas mediante routers y enlaces WAN simulados.

### Diagramas
El proyecto incluye:
- Diagrama lógico general de la red.
- Diagramas lógicos individuales para cada sede.
- Diagrama físico general.
- Diagramas físicos por sede.
- Esquemas físicos de distribución interna de dispositivos.

Todos los diagramas fueron elaborados utilizando Cisco Packet Tracer.

---

## Tecnologías usadas
- Herramienta de simulación: Cisco Packet Tracer
- Protocolos: TCP/IP
- Direccionamiento: IPv4
- Dispositivos: Routers, Switches, PCs, Laptops
- Conceptos aplicados: Subneteo, topologías de red, enrutamiento, conectividad LAN y WAN

---

## Cómo ejecutar el proyecto
1. Instalar Cisco Packet Tracer.
2. Abrir el archivo del proyecto con extensión `.pkt`.
3. Analizar la topología lógica y física de la red.
4. Ejecutar pruebas de conectividad utilizando comandos como `ping`.
5. Verificar la comunicación entre todas las sedes simuladas.

---

## Resultados
La simulación demostró que la red diseñada permite la conectividad entre las cinco sedes de SENASA en Arequipa, logrando una comunicación estable y organizada. El diseño propuesto mejora la coordinación regional y facilita el intercambio de información en tiempo real.

---

## Autor
Pedro Aquino
