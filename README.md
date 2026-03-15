# Alke Wallet Database

Proyecto académico orientado al diseño e implementación de una base de datos relacional para una billetera virtual llamada **Alke Wallet**.

## Descripción del proyecto

Este proyecto presenta la arquitectura de base de datos para una plataforma de billetera digital, enfocada en la gestión de usuarios, monedas y transacciones financieras. El desarrollo considera tanto el modelado conceptual como la definición física de la base de datos, incluyendo sentencias SQL, integridad referencial y análisis transaccional.

## Objetivo general

Diseñar una solución de persistencia de datos confiable para una billetera virtual, capaz de registrar operaciones financieras y mantener la integridad de la información.

## Objetivos específicos

- Identificar entidades, atributos y relaciones del sistema.
- Construir un modelo entidad-relación (ERD).
- Implementar la estructura relacional mediante SQL.
- Aplicar restricciones de integridad con claves primarias y foráneas.
- Analizar el comportamiento de las transacciones según las propiedades ACID.
- Desarrollar consultas para recuperación y análisis de información.

## Alcance del proyecto

La propuesta contempla tres entidades principales:

- **Usuario**: almacena la información de los clientes y su saldo.
- **Moneda**: define las divisas disponibles en el sistema.
- **Transacción**: registra el envío y recepción de fondos entre usuarios.

## Contenido del repositorio

- `docs/alke-wallet-database-report.docx`  
  Documento principal del proyecto, que incluye:
  - diseño conceptual
  - sentencias SQL
  - inserción de datos
  - consultas
  - evidencias de implementación
  - conclusiones y reflexión

## Tecnologías y conceptos aplicados

- SQL
- MySQL / MariaDB
- Modelo Entidad-Relación (ERD)
- Normalización en 3FN
- DDL y DML
- Claves primarias y foráneas
- JOINs y vistas
- Transacciones
- Propiedades ACID

## Consideraciones técnicas

Durante el desarrollo se presentaron inconvenientes con el entorno de ejecución en **MySQL Workbench**, por lo que parte de la implementación fue documentada directamente en el informe académico. Aun así, el proyecto mantiene la lógica estructural de una implementación real de base de datos relacional.

## Proyección de portafolio

Este proyecto evidencia competencias en:

- diseño de modelos relacionales
- construcción de esquemas SQL
- consultas y recuperación de información
- análisis de integridad y transaccionalidad
- documentación técnica de soluciones de software

## Referencias

1. MySQL (2026). *MySQL 8.4 Reference Manual*. Oracle Documentation.  
2. ISO/IEC 9075-1:2023. *Information technology — Database languages — SQL*.  
3. Dbdiagram.io. *Visual Design for Database Schemas*.  
4. W3Schools. *SQL Tutorial and Key Constraints Reference*.  
5. Documentación del curso Desarrollo de Aplicaciones Móviles Android Trainee.  
6. Clases grabadas del curso.  
7. Uso de herramientas de Inteligencia Artificial para apoyo en organización del proyecto.

## Autor

**Camila Torres Reyes**

## Contexto académico

Proyecto correspondiente al **módulo 3** del curso **Desarrollo de Aplicaciones Móviles Android Trainee**.
