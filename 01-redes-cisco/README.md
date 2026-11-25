# Proyecto 01: Infraestructura de Red Empresarial Multisede

## 1. Descripción general

Diseño e implementación de una infraestructura de red empresarial multisede para la empresa ficticia TechSecure Solutions, utilizando Cisco Packet Tracer y GNS3.

El proyecto contempla la interconexión de tres sedes corporativas, segmentación de redes mediante VLAN, direccionamiento IPv4, enrutamiento, servicios de red y mecanismos básicos de seguridad.

## 2. Objetivo general

Diseñar, implementar y validar una infraestructura de red empresarial que permita la comunicación entre las diferentes sedes, garantizando organización, escalabilidad, administración y seguridad de los recursos tecnológicos.

## 3. Objetivos específicos

- Diseñar la topología física y lógica de la infraestructura.
- Implementar direccionamiento IPv4 mediante subnetting y VLSM.
- Segmentar la red utilizando VLAN.
- Configurar switches y routers Cisco.
- Implementar enrutamiento entre redes y sedes.
- Configurar servicios DHCP y DNS.
- Implementar NAT, ACL y administración SSH.
- Realizar pruebas de conectividad y seguridad.
- Documentar configuraciones, evidencias y resultados.

## 4. Escenario empresarial

La infraestructura contempla tres sedes:

| Sede | Capacidad de usuarios |
|---|---:|
| Principal | 180 |
| Operaciones | 180 |
| Call Center | 180 |
| Total | 540 |

## 5. Requerimientos funcionales

- Comunicación entre dispositivos de una misma sede.
- Interconexión de las tres sedes.
- Segmentación por departamentos mediante VLAN.
- Enrutamiento entre VLAN y sedes.
- Asignación automática de direcciones IP mediante DHCP.
- Resolución de nombres mediante DNS.
- Acceso a servicios corporativos.
- Salida a redes externas mediante NAT.
- Administración remota mediante SSH.
- Control del tráfico mediante ACL.

## 6. Requerimientos no funcionales

- Seguridad de la infraestructura.
- Disponibilidad de los servicios.
- Escalabilidad.
- Rendimiento adecuado.
- Facilidad de administración.
- Documentación técnica.

## 7. Tecnologías y herramientas

- Cisco Packet Tracer.
- GNS3.
- Direccionamiento IPv4.
- VLAN y trunk 802.1Q.
- STP.
- Routing.
- DHCP y DNS.
- NAT.
- ACL.
- SSH.

## 8. Alcance

El proyecto comprende el diseño, configuración, implementación y validación de una infraestructura de red empresarial multisede de nivel intermedio.

El direccionamiento IPv6 y la implementación de VPN IPsec no forman parte del alcance inicial.

## 9. Metodología de trabajo

El desarrollo se dividirá en las siguientes etapas:

1. Análisis de requerimientos.
2. Diseño lógico.
3. Diseño físico.
4. Implementación en simuladores.
5. Configuración de infraestructura.
6. Implementación de servicios.
7. Seguridad de red.
8. Pruebas y validación.
9. Documentación técnica.

## 10. Estado del proyecto

Fase 1: Análisis de requerimientos — En desarrollo.

## 11. Validación de requerimientos

Se establece una infraestructura empresarial compuesta por tres sedes: Principal, Operaciones y Call Center.

Cada sede tendrá una capacidad inicial de 180 usuarios, alcanzando una capacidad corporativa de 540 usuarios.

### Arquitectura de servidores

Los servidores corporativos estarán centralizados en la Sede Principal. Las sedes remotas accederán a estos servicios mediante la infraestructura de interconexión WAN.

### Decisiones técnicas aprobadas

- Capacidad: 180 usuarios por sede.
- Capacidad corporativa: 540 usuarios.
- Centro de servidores: Sede Principal.
- Direccionamiento: IPv4.
- Segmentación: VLAN.
- Enrutamiento: comunicación entre VLAN y sedes.
- Servicios: DHCP y DNS.
- Seguridad: ACL y SSH.
- Traducción de direcciones: NAT.
- Simuladores: Cisco Packet Tracer y GNS3.
- Reserva de crecimiento propuesta: 20%.

### Criterios de aceptación

La infraestructura deberá demostrar conectividad, segmentación, enrutamiento, disponibilidad de servicios, administración remota y control de acceso.

### Resultado de la fase

Los requerimientos principales y la arquitectura inicial han sido validados como base para el diseño lógico de la infraestructura.

**Estado: Fase 1 completada.**
