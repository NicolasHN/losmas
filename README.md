# losmas

Pequeño y entretenido sistema web para elegir los más (trabajadores, simpáticos, buenos amigos, enojones, etc) en un grupo de personas (cursos, oficinas, etc). Ideal para pasar un rato agradable con los compañeros.

El sistema debe estar hecho en Laravel y pensado desde un principio para ser montado en un cluster Kubernetes. La idea es que sirva de práctica para realizar la instalación, y configuración de git, Docker, Kubernetes, Laravel, Composer, Mysql, Nginx, PHP. El objetivo es lograr balanceo de carga (elástico) y alta disponibilidad, y de paso practicar el uso de Laravel para el desarrollo de aplicaciones Web.
 
- Quien quiera ocupar el Sistema deberá crear una cuenta temporal con solo dos datos (Nombre y correo electrónico).
- Una vez creada la cuenta llegará un correo de confirmación. Desde ese punto ya podrá registrar a más personas (Nombre o apodo y email). Con la posibilidad de cargar archivo separado por comas o planilla de cálculo.
- Podrá crear categorías, existiendo algunas por defecto (El más trabajador(a), El mas patero(a), El más jote, El más guapo, La más guapa, El más puntual, El zapatillas de clavo, El que saca más la vuelta, Mister o Miss Facebook, El más enojón(a), El(la) más insolente, El(la) más califa, etc).
- Una vez agregadas todas las personas del grupo se debe poder pincha un botón Finalizar, con lo cual se confirmará el envío de correos a cada uno de los integrantes.
- El correo recibido contendrá una URL con una clave única que permitirá realizar de manera anónima la votación por una única vez cuando finalice su votación.
- Cuando todos los integrantes hayan votado o cuando el administrador de término manual al proceso de votación, este recibirá un correo con el el resultado final de las votaciones y un diploma en PDF, que contendrá el nombre del evento, el nombre o apodo de la persona y el premio ganado, El(la) más trabajador(a), El(la) más flojo(a), etc.

Vamos allá...
