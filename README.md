# Ejercicio1DDI

La empresa BK continua con el desarrollo de las interfaces para la aplicación de gestión hotelera y solicitan tu ayuda para completar las interfaces que necesitan. 
Entre otras, la empresa tiene la necesidad de cubrir la reserva de salones disponibles para convenciones, eventos, congresos, etc. 
La práctica que debes realizar consiste en crear una interfaz que permita gestionar la reserva de uno de estos salones, llamado "Salón Habana". 
Los requisitos que debe cumplir esta interfaz son:

        1. Se debe escribir el nombre y teléfono de contacto de la persona que hace la reserva.
        2. Hay que cumplimentar:
            ▪ Fecha del evento. Utiliza un spinner al que deberás modificar el modelo.
            ▪ Tipo, se puede escoger entre banquete, jornada o congreso. Componente a tu criterio.
            ▪ Número de personas que asistirán. Componente a tu criterio.
            ▪ Tipo de cocina que se precisará, a elegir entre bufé, carta, pedir cita con el chef o no precisa. Componente a tu criterio.
        3. Si el evento es un congreso se debe preguntar el número de jornadas del congreso y si se requerirán habitaciones para los asistentes al evento.
        Esto puedes hacerlo añadiendo los componentes necesarios con la propiedad enabled a falso.
        
Tu tarea consistirá en generar una aplicación que cuente con un diálogo nuevo en el que crearás la interfaz con las restricciones que se indican más arriba. Además de añadir los componentes que necesites para darle funcionalidad deberás cumplir con los siguientes requisitos no funcionales:
    • Debes cambiar el nombre y añadir un ToolTipText a los componentes.
    • Modifica el formato de texto de las etiquetas y añade separadores y paneles con título para aportar vistosidad a la interfaz.
    • Utiliza el modo de diseño libre para colocar los componentes en el diálogo. Cuida que la composición quede armónica.
    • La interfaz generada irá conectada a la interfaz principal de la aplicación mediante el menú principal y mediante un botón que debes añadirle que tendrás que programar correctamente para que abran el diálogo que has creado.
    • Debes crear la interfaz modal.
    • Cuando se selecciona como tipo de evento banquete o jornada los componentes para número de días y habitaciones deben estar desactivados, 
    sin embargo si es congreso se deben activar.
    
Criterios de puntuación. Total 10 puntos.
    1. Creación de la interfaz empleando los componentes más adecuados. 3 puntos.
    2. Cambiar los nombres y ToolTipText para los elementos de formulario adecuado: 1 punto.
    3. Distribuir los elementos adecuadamente usando el modo de distribución libre. 1 punto.
    4. Modificar la fuente de las etiquetas para dar vistosidad a la interfaz. 1 punto.
    5. Añadir el código para poder abrir el diálogo en modo modal desde la ventana principal usando el menú y usando un botón al que se gestione el evento. 2 puntos.
    6. Añadir la gestión de eventos necesaria para que cuando se seleccione la opción congreso se active el número de días y si necesita habitaciones, y se desactive en caso contrario. 2 puntos.  
