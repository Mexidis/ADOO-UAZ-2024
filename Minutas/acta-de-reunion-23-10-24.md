### Minuta de Reunión

**Fecha:** 23 de octubre de 2024  
**Hora:** 16:00 hrs  
**Lugar:** Sala de reuniones virtual

#### Asistentes:

- Patrick Martínez
- Víctor Colón López

#### Puntos tratados:

1. **Revisión del diagrama conceptual:**  
    Se revisó el diagrama conceptual preliminar para la aplicación de gestión de torneos amateurs, incluyendo entidades como _Torneo, Equipo, Jugador, Partido, Resultado_ y _Estadística.  Se discutieron las relaciones y multiplicidades entre las entidades.
    
2. **Nuevos roles dinámicos en la aplicación:**  
    Se definió que los usuarios, al registrarse, automáticamente se convierten en jugadores. Además, se especificaron las siguientes dinámicas de roles:
    
    - Si un jugador crea un equipo, automáticamente se convierte en **entrenador** de dicho equipo.
    - Si un jugador crea un torneo, automáticamente se convierte en **administrador del torneo**.
    - Los entrenadores pueden invitar jugadores a unirse a sus equipos.
    - Los administradores de torneos pueden invitar equipos a participar en torneos.
      
3. **Casos de uso iniciales basados en los roles dinámicos:**  
    Se discutieron los siguientes casos de uso clave para reflejar la dinámica de roles en la aplicación:
    
    - **Registrar usuario:** Un usuario se registra y automáticamente se convierte en jugador.
    - **Crear equipo:** Un jugador crea un equipo, lo que lo convierte en entrenador.
    - **Crear torneo:** Un jugador crea un torneo y automáticamente se convierte en administrador del torneo.
    - **Invitar jugadores a un equipo:** El entrenador puede invitar jugadores a su equipo.
    - **Invitar equipos a un torneo:** El administrador del torneo puede invitar equipos a participar.
      
4. **Próximos pasos en el diseño del diagrama de casos de uso:**  
	Se acordó diseñar un diagrama de casos de uso que refleje la dinámica de roles y las principales funcionalidades discutidas.

#### Acuerdos:

- Se mantendrá el enfoque de roles dinámicos en la aplicación.
    
- Se elaborará el diagrama de casos de uso en la próxima reunión para validar estas funcionalidades.
    
- **Fecha de la siguiente reunión:** 25 de octubre de 2024.
    
- **Tema principal:** Refinar los casos de uso y trabajar en el diagrama de clases UML.

#### Tareas pendientes:

- **Patrick** preparará una lista más detallada de los casos de uso para ser revisada y discutida en la próxima sesión.
- Víctor creará un diagrama preliminar de casos de uso que refleje la dinámica de roles y las funcionalidades descritas.

La reunión concluyó a las ~ 17:23 hrs.
