# Fundamentos de la nube

Este módulo introduce los conceptos esenciales de **Cloud Computing y AWS**.  
Es el punto de partida para entender cómo funcionan los servicios cloud y cómo se utilizan en la práctica.

El objetivo es que el alumno comprenda **los principios básicos de la nube antes de empezar a trabajar con servicios específicos de AWS**.

---

# Objetivos del módulo

Al finalizar este módulo el alumno debería ser capaz de:

- explicar qué es **cloud computing**
- entender las **ventajas del modelo cloud**
- comprender cómo se organiza la **infraestructura global de AWS**
- identificar las principales **categorías de servicios**
- conocer los servicios básicos **Amazon EC2 y Amazon S3**
- entender el **modelo de responsabilidad compartida**
- reconocer conceptos clave que aparecen en el examen **AWS Certified Cloud Practitioner**

---

# Contenido del módulo

1. [Qué es Cloud Computing](01-que-es-cloud.md)
2. [Ventajas del Cloud](02-ventajas-del-cloud.md)
3. [Infraestructura global de AWS](03-infraestructura-global-aws.md)
4. [Categorías de servicios AWS](04-categorias-servicios-aws.md)
5. [Amazon EC2](05-amazon-ec2.md)
6. [Amazon S3](06-amazon-s3.md)
7. [Modelo de responsabilidad compartida](07-modelo-responsabilidad-compartida.md)

---

# Conceptos clave que debes recordar

Estos conceptos son fundamentales para entender cloud computing:

| Concepto | Explicación |
|--------|--------|
| Cloud Computing | Uso de recursos informáticos a través de internet |
| Pay-as-you-go | Pago solo por lo que se utiliza |
| Elasticidad | Ajustar recursos automáticamente según demanda |
| Escalabilidad | Aumentar capacidad de un sistema |
| Alta disponibilidad | Diseñar sistemas que sigan funcionando aunque haya fallos |

---

# Infraestructura global de AWS

AWS organiza su infraestructura en tres niveles principales.

## Regions

Una **Region** es un área geográfica donde AWS tiene centros de datos.

Ejemplos:

- eu-west-1 (Irlanda)
- eu-central-1 (Frankfurt)
- us-east-1 (Virginia)

---

## Availability Zones

Cada región contiene varias **Availability Zones (AZ)**.

Cada AZ es un **datacenter independiente**.

Se utilizan para:

- alta disponibilidad
- resiliencia
- tolerancia a fallos

---

## Edge Locations

Son servidores distribuidos globalmente para reducir latencia.

Se utilizan en servicios como:

- Amazon CloudFront
- Amazon Route 53

---

# Servicios AWS que se introducen en este módulo

Este módulo presenta dos de los servicios más importantes de AWS.

## Amazon EC2

Servicio de **cómputo** que permite lanzar **máquinas virtuales en la nube**.

Se usa para:

- servidores web
- aplicaciones
- desarrollo
- testing

---

## Amazon S3

Servicio de **almacenamiento de objetos**.

Se usa para:

- almacenamiento de archivos
- backups
- hosting web estático
- almacenamiento de logs

---

# Modelo de responsabilidad compartida

AWS y el cliente comparten responsabilidades de seguridad.

## AWS es responsable de

La **seguridad de la nube**.

Incluye:

- centros de datos
- hardware
- red global
- infraestructura física

---

## El cliente es responsable de

La **seguridad en la nube**.

Incluye:

- usuarios
- permisos
- configuración de servicios
- sistemas operativos
- aplicaciones
- datos

---

# Relación con el examen Cloud Practitioner

Este módulo cubre principalmente el dominio:

**Cloud Concepts**

Conceptos importantes para el examen:

- Elasticity
- Scalability
- High Availability
- Regions
- Availability Zones
- Pay-as-you-go
- Shared Responsibility Model

---

# Cómo estudiar este módulo

1. Leer cada documento en orden
2. Comprender los conceptos antes de memorizar
3. Relacionar cada servicio con su caso de uso
4. Repasar los conceptos clave
5. Practicar preguntas tipo examen

---

# Preguntas de práctica

Puedes practicar con las preguntas del módulo en:

preguntas/

---

# Resultado esperado

Al finalizar este módulo deberías poder explicar:

- qué es cloud computing
- por qué las empresas usan cloud
- cómo se organiza AWS globalmente
- qué hacen servicios como EC2 y S3
- cómo funciona el modelo de responsabilidad compartida
