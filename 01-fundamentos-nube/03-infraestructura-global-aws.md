# Infraestructura global de AWS

AWS dispone de una red global de centros de datos.

Esta infraestructura se organiza en tres niveles.

## Regiones

Una **Region** es un área geográfica donde AWS tiene centros de datos.

Ejemplos:

- eu-west-1 (Irlanda)
- eu-central-1 (Frankfurt)
- us-east-1 (Virginia)

Las regiones están aisladas entre sí.

---

## Availability Zones

Cada región contiene varias **Availability Zones (AZ)**.

Cada AZ es:

- un datacenter independiente
- con energía y red separadas

Se utilizan para:

- alta disponibilidad
- resiliencia

Ejemplo de arquitectura:

Aplicación desplegada en **3 AZ**.

---

## Edge Locations

Son ubicaciones distribuidas por todo el mundo.

Se utilizan para:

- entregar contenido rápidamente
- reducir latencia

Servicios que usan Edge Locations:

- CloudFront
- Route 53
