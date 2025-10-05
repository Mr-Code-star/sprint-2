- [5.2.2. Sprint 2](#522-sprint-2)
- [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
- [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-Leaders-and-collaborators)
- [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
- [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
- [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
- [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
- [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
- [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)

### 5.2.2. Sprint 2
Ahora en la presente sección, documentaremos y explicaremos el progreso del Sprint 2 en términos de desarrollo del producto y colaboración del equipo. Abordaremos varios aspectos clave, incluyendo la planificación del sprint, el backlog del sprint, la evidencia de desarrollo para la Revisión del Sprint.
#### 5.2.2.1. Sprint Planning 2.

<table>
  <tr>
    <th>Sprint #</th>
    <th>Sprint 2</th>
  </tr>
  <tr>
    <td colspan="2"><b>Sprint Planning Background</b></td>
  </tr>
  <tr>
    <td>Date</td>
    <td>5-10-2025</td>
  </tr>
  <tr>
    <td>Time</td>
    <td> 7:22 AM</td>
  </tr>
  <tr>
    <td>Location</td>
    <td> Reunión virtual mediante Discord </td>
  </tr>
  <tr>
    <td>Prepared By</td>
    <td> Vitaly Arturo, Baca Camargo </td>
  </tr>
  <tr>
    <td>Attendees</td>
    <td>Huapaya Galindo, Dyaron, Huarcaya Matias, Gilbert Alonso, Pariachi Limahuaya, Sebastian Ubaldo, Ramirez Carrasco, Ariana Lizeth  </td>
</td>
  </tr>
  <tr>
    <td>Sprint n-1 Review Summary</td>
    <td> En este primer sprint logramos completar y desplegar la primera versión del landing page de CollabUs, nuestro punto de inicio para presentar la propuesta del proyecto. Implementamos la barra de navegación, las secciones principales de información, los medios de contacto y el footer, cuidando que todo mantuviera una identidad visual coherente con la marca. El trabajo se realizó de manera ordenada. Algunos de los integrantes del equipo participaron activamente en el desarrollo. En general, sentimos que la entrega fue muy positiva, ya que cumplimos con los objetivos y el diseño final refleja claramente lo que queremos transmitir con CollabUs. </td>
  </tr>
  <tr>
    <td> Sprint n-1 Retrospective Summary</td>
    <td> Durante este sprint, el desarrollo del landing page estuvo principalmente a cargo de dos integrantes del equipo, ya que los demás tuvieron algunos contratiempos que les impidieron participar de manera activa. A pesar de ello, logramos mantener una buena coordinación entre quienes trabajamos directamente en las tareas y pudimos completar los objetivos planteados. El proceso fue fluido y nos permitió reforzar la comunicación y la organización dentro del grupo. Para los próximos sprints, esperamos que todos puedan involucrarse plenamente y así avanzar de manera más equilibrada y eficiente. </td>
  </tr>
  <tr>
    <td colspan="2"><b>Sprint Goal & User Stories</b></td>
  </tr>
  <tr>
    <td>Sprint 2 </td>
    <td> Desplegar una primera versión de la Aplicación Web

Métrica de Cumplimiento: Para evaluar el cumplimiento del presente sprint, vamos a utilizar la siguiente métrica: Evaluaremos que el proyecto compile y se pueda acceder a las pantallas establecidas para este sprint. El objetivo será implementar las pestañas principales de nuestra aplicación web.<br>
</tr>
  <tr>
    <td>Sprint 2 Velocity</td>
    <td>30 story points</td>
  </tr>
  <tr>
    <td>Sum of Story Points</td>
    <td>30 story points</td>
  </tr>
</table><br><br>

#### 5.2.2.2. Aspect Leaders and Collaborators.

En esta sección se incluye la elaboración de el artefacto Leadership-andCollaboration Matrix (LACX), el cual elegirenos quién es el líder y quiénes son los colaboradores para este Sprint 2.

| Team Member (Last Name, First Name)  | GitHub Username | Landing page |
| ------------------------------------ | --------------- | ------------ |
| Huarcaya Matias, Gilbert Alonso      | GilbertHuarcaya | C            |
| Huapaya Galindo, Dyaron              | Mainema         | C            |
| Pariachi Limahuaya, Sebastian Ubaldo | S-06X           | C            |
| Baca Camargo, Vitaly Arturo          | Mr-Code-star    | L            |
| Ramirez Carrasco, Ariana Lizeth      | ariana9513      | C            |

#### 5.2.2.3. Sprint Backlog 2.
<table>
  <thead>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item / Task</th>
  </tr>
   <tbody>
      <tr>
    <td>Id</td>
    <td>Title</td>
    <td>Id</td>
    <td>Title</td>
    <td>Description</td>
    <td>Estim<br>ation (Hours)</td>
    <td>Assigned to</td>
    <td>Status (To-do / InProcess / ToReview / Done)</td>
  </tr>
     <tr>
    <td>US001</td>
    <td>Registro y autenticación de usuarios</td>
    <td>WII-01</td>
    <td>Implementar vista de registro y inicio de seccion</td>
    <td>Crear las vistas de registro y inicio de seccion para la autenticación de los usuarios a las pagina inicial</td>
    <td>2</td>
    <td>Baca Camargo, Vitaly Arturo</td>
    <td>Done</td>
     </tr>
     <tr>
       <td>US028</td>
       <td>Selección de plan de suscripción	</td>
       <td>WII-02</td>
       <td>Implementar vista de selecionar un plan e bloquear todas la funciones de la pagina</td>
       <td>Implementar solo la vista de selecionar plan con los planes gratuito de $0 y premium de $5. Si el usuario no tiene un plan
          de los dos presentes se bloque todas las funciones de la aplicativo debe comprar un plan para que recien haga las actividades dentro de la pagina.             
       </td>
       <td> 5 </td>
       <td> Pariachi Limahuaya, Sebastian Ubaldo</td>
       <td> Done </td>
     </tr>
     <tr>
       <td>US057</td>
       <td>API RESTful – Planes de suscripción	</td>
       <td>WII-03</td>
       <td>Consumir endpoint de planes de suscripción</td>
       <td>
         Implementar la lógica para consumir el endpoint '/api/plans' desde el frontend usando una fake API (mock o json-server). Mostrar dinámicamente los planes Gratuito y Premium en la interfaz de selección, manejando estados de carga y errores en caso de fallo de conexión.
       </td>
       <td> 4 </td>
       <td> Pariachi Limahuaya, Sebastian Ubaldo</td>
       <td> Done </td>
     </tr>
     <tr>
       <td>US029</td>
       <td>Perfil de usuario registrado	</td>
       <td>WII-04</td>
       <td>Implementar vista del perfil del usuario</td>
       <td>Crear la vista del perfil del usuario registrado que muestre su foto, nombre, rol, descripción personal, habilidades, proyectos, puntos y botones de “Ver CV”, “Portafolio” y “Experiencias”. Asegurar que los datos se carguen correctamente desde el backend y que la interfaz sea responsiva.</td>
       <td>6</td>
       <td>Huarcaya Matias, Gilbert Alonso</td>
        <td> Done </td>
     </tr>
      <tr>
       <td>US004</td>
       <td>Creación de proyectos	</td>
       <td>WII-05</td>
       <td>Implementar módulo de creación de proyectos</td>
       <td> Desarrollar la vista “Crear Proyecto” que permita al usuario registrar el nombre del proyecto, su área, etiquetas y un resumen descriptivo. Incluir la segunda etapa del flujo para definir roles, donde el usuario puede agregar tarjetas con títulos, ítems y responsabilidades personalizadas. El flujo finaliza con la opción de publicar el proyecto, asegurando validaciones en todos los campos y una navegación clara entre pasos (Siguiente, Volver, Cancelar). </td>
       <td>8</td>
       <td>Ramirez Carrasco, Ariana Lizeth</td>
        <td> Done </td>
     </tr>
     <tr>
       <td>US017</td>
       <td>API RESTful - Crear proyecto		</td>
       <td>WII-06</td>
       <td> Implementar endpoint para registro de proyectos </td>
       <td> Desarrollar la conexión entre el formulario de creación de proyectos del frontend y la API RESTful para registrar los proyectos. Configurar el método POST /api/projects que reciba los datos del formulario (nombre, área, etiquetas, resumen y roles) y los almacene en la base de datos o mock API. Implementar validaciones y retornar código HTTP 201 en caso de registro exitoso. </td>
       <td>6</td>
       <td> Huapaya Galindo, Dyron </td>
      <td> Done </td>
     </tr>
     <tr>
        <td>US025</td>
       <td>Ranking de colaboradores			</td>
       <td>WII-07</td>
       <td> Implementar ranking de los 10 mejores colaboradores de acuerdo a la cantidad de puntos</td>
       <td>Desarrollar un sistema en el cual se presente a los 10 mejores colaboradores detacados en la pagina de CollabUs de acuerdo a la cantidada de puntos que fueron dejando otros usuarios al perfil de dicho perfil del colaborador. </td>
       <td> 8 </td>
       <td> Baca Camargo, Vitaly Arturo</td>
      <td> Done </td>
     </tr>
      <tr>
        <td>US007</td>
       <td>Postulación a proyectos		</td>
       <td>WII-08</td>
       <td> Implementar módulo de postulación a proyectos </td>
       <td> Desarrollar la funcionalidad que permita a los colaboradores postularse a proyectos disponibles. Incluir formulario con campos de mensaje de motivación y habilidades relevantes. Conectar con el endpoint correspondiente para registrar la postulación y notificar al creador del proyecto. Mostrar confirmación visual del envío y gestionar los estados de solicitud (pendiente, aceptada o rechazada). </td>
       <td> 6 </td>
       <td> Baca Camargo, Vitaly Arturo</td>
      <td> Done </td>
     </tr>
      <tr>
        <td>US027</td>
       <td>Ver proyecto		</td>
       <td>WII-09</td>
       <td>Implementar vista de detalle de proyecto </td>
       <td> Desarrollar la vista detallada del proyecto accesible desde el botón “Ver más”, mostrando información completa del mismo: resumen, beneficios, nivel académico, habilidades técnicas, roles disponibles, creador y fecha de publicación. Incluir las opciones de interacción “Postular”, “Contribuir” y “Guardar en favoritos”, asegurando que la interfaz sea dinámica y responsive. </td>
       <td> 7 </td>
       <td>Ramirez Carrasco, Ariana Lizeth y Huapaya Galindo, Dyron</td>
      <td> Done </td>
     </tr>
   </tbody> 
  </table>

  
  
#### 5.2.2.4. Development Evidence for Sprint Review.
#### 5.2.2.5. Execution Evidence for Sprint Review.
#### 5.2.2.6. Services Documentation Evidence for Sprint Review.
#### 5.2.2.7. Software Deployment Evidence for Sprint Review.
#### 5.2.2.8. Team Collaboration Insights during Sprint
