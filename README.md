# SgOVI - Sistema de Gestión de la Oficina por la Vida Independiente

## 📖 Descripción del Proyecto
Este proyecto consiste en la implementación interactiva de una aplicación web denominada **SgOVI**, diseñada para la Oficina por la Vida Independiente "Sole Arnau Ripollés" de Castelló (OVI). 

El sistema nace de la necesidad de digitalizar la operativa diaria de la OVI, facilitando la gestión de datos sensibles de forma segura y permitiendo ofrecer trámites en línea a las personas usuarias. SgOVI da soporte a las operaciones clave, englobando la gestión de datos personales, la coordinación de los servicios de asistencia y la interacción entre usuarios y profesionales. Además, su desarrollo busca la familiarización con un proyecto real y la aplicación de tecnologías de diseño actuales.

## 👥 Roles y Funcionalidades
El sistema está dividido por controles de acceso según el tipo de usuario, ofreciendo funcionalidades específicas para cada uno:

*   **Técnico**: Se encarga de revisar y validar las solicitudes de registro al sistema (nuevos usuarios, profesionales y tutores). Puede gestionar listados de usuarios, consultar contratos, supervisar solicitudes de asignación en negociación y vincular menores a sus respectivos tutores.
*   **Usuario OVI y Tutor**: Ambos pueden realizar solicitudes de asignación, seleccionar a los candidatos propuestos que mejor encajen, comunicarse con ellos mediante el sistema y subir los contratos formales. La principal diferencia es que el tutor gestiona toda la información y flujos en nombre de los menores a su cargo, ya que los usuarios menores de edad tienen permisos de solo lectura.
*   **PAP / PATI (Asistentes Personales y Terapéuticos Infantiles)**: Disponen de herramientas para consultar sus contratos, revisar las solicitudes de asignación en las que han sido propuestos y entablar comunicaciones directas con los usuarios para llegar a acuerdos laborales.

## 🚀 Mejoras Implementadas
*   Se ha incluido desde cero la figura del **Tutor** dentro del flujo del sistema.
*   Esta mejora permite que los usuarios OVI menores de edad, que no pueden firmar contratos por sí mismos, puedan estar representados legalmente en la plataforma por su tutor.

## 🛠️ Tecnologías y Arquitectura
El proyecto integra distintas capas tecnológicas de desarrollo de software:
*   **Backend**: Estructurado y desarrollado utilizando el framework **Spring MVC**.
*   **Base de Datos**: Diseño físico e implementación mediante bases de datos relacionales (**SQL**), con tablas fuertemente tipadas para garantizar la integridad de entidades (usuarios, contratos, negociaciones, etc).
*   **Frontend y Diseño**: Interfaz de usuario diseñada bajo principios de usabilidad utilizando **Bootstrap**.

## 🎓 Autores
Proyecto desarrollado para la asignatura *Disseny i Implementació de Sistemes d'informació* (EI1027) de la Universitat Jaume I.
*   Talia Hinojo Montañana
*   Rayan Mohamed Djelloul Ayad
*   Pedro Jareño Sevilla
