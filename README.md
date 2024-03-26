# CIM
Sistema web para el control remoto de un dispositivo automatizado de la Facultad de Ingeniería UNMdP.


1. Introducción
El Sistema de Control Remoto de Dispositivos Automatizados (SCRDA) es una solución web desarrollada para el Departamento de Laboratorios Remotos de la Facultad de Ingeniería de la UNMdP. Este sistema permite la gestión remota de un servidor que controla un sistema industrial automatizado, facilitando prácticas educativas para estudiantes y documentando los procesos correspondientes.

2. Requerimientos Funcionales
2.1 Gestión de Sesión
Inicio de Sesión: Los usuarios deben poder iniciar sesión en el sistema utilizando credenciales proporcionadas por la facultad.
Gestión de Cuentas: Los alumnos deben tener cuentas individuales que les permitan acceder a los recursos compartidos, mientras que los docentes deben tener privilegios adicionales para supervisar y administrar las actividades.

  2.2 Control Remoto del Servidor
Acceso Remoto: Los estudiantes deben poder acceder al servidor de control del sistema automatizado desde cualquier ubicación utilizando un navegador web estándar.
Interfaz de Control: Se debe proporcionar una interfaz intuitiva que permita a los usuarios controlar el servidor y ejecutar prácticas en el sistema automatizado.

  2.3 Soporte Multimedia
Transmisión en Tiempo Real: Se debe integrar soporte multimedia para permitir la visualización en tiempo real de las actividades en el sistema automatizado, incluyendo audio (Opcional) y video.

  2.4 Herramientas de Apoyo
Mensajería Directa: Se debe implementar una función de mensajería directa que facilite la comunicación entre los usuarios y el personal encargado de supervisar el sistema automatizado durante las prácticas.

  2.5 Gestión de Turnos
Reserva de Turnos: Los usuarios deben poder reservar turnos en un calendario para coordinar el uso del sistema automatizado de manera ordenada y eficiente.

  2.6 Almacenamiento de Archivos
Almacenamiento Temporal: El sistema debe permitir el almacenamiento de archivos multimedia durante un período de tiempo definido para que los usuarios puedan acceder a ellos y descargar contenido relevante, así como información estadística de las prácticas realizadas.

Requerimientos No Funcionales
1. Seguridad
Seguridad de Datos: Garantizar la seguridad de los datos almacenados y transmitidos, mediante el uso de cifrado de extremo a extremo y medidas de seguridad robustas.
Autenticación y Autorización: Implementar un sistema de autenticación sólido para verificar la identidad de los usuarios y un sistema de autorización para controlar el acceso a diferentes funciones y datos.
Protección contra Amenazas Externas: Incorporar medidas de protección contra posibles ataques como inyección de código, XSS (Cross-Site Scripting) y CSRF (Cross-Site Request Forgery).

2. Rendimiento
Tiempo de Respuesta: Garantizar tiempos de respuesta rápidos para la interfaz de usuario y las operaciones del sistema automatizado, incluso en condiciones de alta carga.
Escalabilidad: Diseñar el sistema para que pueda escalar fácilmente y manejar un aumento en el número de usuarios y prácticas simultáneas sin comprometer el rendimiento.
Optimización de Recursos: Optimizar el uso de recursos del servidor para minimizar el consumo de ancho de banda y recursos de hardware, maximizando así la eficiencia del sistema.

3. Fiabilidad
Registro de Errores: Mantener un registro detallado de errores y eventos del sistema para facilitar la depuración y el diagnóstico de problemas.

4. Usabilidad
Interfaz Intuitiva: Diseñar una interfaz de usuario intuitiva y fácil de usar que requiera un mínimo de capacitación para su uso.
Documentación Clara: Proporcionar documentación detallada y clara que explique el funcionamiento del sistema y brinde instrucciones paso a paso para su uso.

5. Interoperabilidad
Compatibilidad con Navegadores: Garantizar la compatibilidad del sistema con una amplia gama de navegadores web populares para maximizar la accesibilidad de los usuarios.
Estándares Abiertos: Utilizar estándares y protocolos abiertos para facilitar la integración con otros sistemas y la interoperabilidad futura.

6. Tecnología
Tecnologías Web Modernas: Utilizar tecnologías web modernas y frameworks de desarrollo que permitan el desarrollo rápido, la escalabilidad y el mantenimiento sostenible del sistema. (Sin restricciones)
WebSockets y WebRTC: Implementar WebSockets para una comunicación bidireccional en tiempo real entre el navegador y el servidor, y WebRTC para la transmisión de datos multimedia en tiempo real. (Recomendacion)
Seguimiento de Tendencias: Mantenerse al tanto de las últimas tendencias y avances en tecnología web para asegurar que el sistema esté actualizado y pueda aprovechar nuevas oportunidades y mejoras.
