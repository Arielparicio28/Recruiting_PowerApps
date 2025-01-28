# Aplicación de Reclutamiento

## Descripción
Esta aplicación de reclutamiento está diseñada para gestionar y optimizar los procesos de selección de talento en una organización. Desarrollada utilizando **Power Apps**, **Power Automate** y **Dataverse**, es de uso interno, nos permite tener las ofertas y los usuarios que estan en esas ofertas y realizar un seguimiento internamente.

## Tecnologías Utilizadas
- **Power Apps**: Para la creación de interfaces de usuario interactivas y adaptables.
- **Power Automate**: Para la automatización de flujos de trabajo, notificaciones y procesos asociados.
- **Dataverse**: Como base de datos centralizada para almacenar y gestionar la información de vacantes, candidatos y entrevistas.
- **Microsoft 365**: Integración con servicios como SharePoint, Outlook y Teams para colaboración.

## Funcionalidades Principales
1. **Gestión de Vacantes**:
   - Crear, editar y cerrar publicaciones de empleo.
   - Asignar responsables de selección y definir requisitos de las posiciones.
2. **Registro de Candidatos**:
   - Captura de información personal y profesional.
   - Adjuntar currículums y documentos relevantes.
3. **Automatización de Procesos**:
   - Notificaciones automáticas para candidatos y responsables.
4. **Seguimiento del Proceso de Selección**:
   - Visualización del progreso de cada candidato mediante un kanban.
   - Registro de evaluaciones y retroalimentación.
5. **Reportes y Métricas**:
   - Análisis del tiempo de contratación, cantidad de vacantes cubiertas, etc.
  
## Arquitectura
La aplicación sigue un enfoque modular y escalable:

- **Power Apps**: Interfaz principal para la interacción del usuario.
- **Dataverse**: Base de datos que centraliza:
  - Proceso de selección.
  - Candidatos.

- **Power Automate**: Flujos que conectan:
  - Notificaciones por correo.
  - Sincronización de entrevistas con calendarios de Outlook.

## Requisitos
Para desplegar y usar la aplicación, se necesitan los siguientes recursos:
- Licencia de Microsoft Power Platform (Power Apps y Power Automate).
- Permisos de administrador para configurar Dataverse.
- Acceso a Microsoft 365 para la integración con otros servicios.

## Instalación y Configuración
1. **Clonar o descargar el repositorio**.
2. **Importar el archivo Power Apps** en el entorno deseado.
3. **Configurar conexiones en Power Automate**:
   - Vincular los flujos con los conectores necesarios (Dataverse, Outlook, Teams, etc.).
4. **Cargar datos iniciales en Dataverse** (opcional).
5. **Probar la aplicación** y ajustar configuraciones según sea necesario.

## Uso
1. Accede a la aplicación desde Power Apps.
2. Inicia sesión con tu cuenta de Microsoft 365.
3. Navega por las secciones para:
   - Publicar vacantes.
   - Registrar candidatos.
   - Realizar seguimientos de entrevistas y evaluaciones.


## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

### Contacto
Si tienes dudas o sugerencias, puedes contactarnos en:
- **Correo**: [arielaparicio100@gmail.com](mailto:arielaparicio100@gmail.com)
- **LinkedIn**: [Linkedin](https://www.linkedin.com/in/arielaparicio/)

---
¡Gracias por usar nuestra aplicación de reclutamiento!
