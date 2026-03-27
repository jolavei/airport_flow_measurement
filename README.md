Sistema de Medición de Flujos - AERODROMOS.IGS

Una herramienta web ligera y offline diseñada para el levantamiento de datos en terreno. Permite medir el flujo de pasajeros, calcular tiempos de espera y registrar las tasas de llegada/salida en puntos de control o atención (ej. counters, filtros de seguridad) utilizando el método de registro por intervalos.

Características Principales

100% Offline: No requiere conexión a internet ni servidores. Funciona ejecutando el archivo localmente en el navegador del dispositivo.
Diseño Móvil (Responsive): Interfaz optimizada para su uso en smartphones mediante "botones de cojín" grandes para facilitar el registro rápido en terreno.
Carga Inicial: Permite calibrar la medición ingresando la cantidad de personas que ya se encuentran en la fila antes de iniciar el cronómetro.
Cálculo Automático de KPIs: Calcula en tiempo real y al finalizar la sesión los indicadores clave de rendimiento operativo.Exportación de Datos: Genera un archivo .csv detallado con el registro segundo a segundo y el resumen de la medición, listo para ser analizado en Excel o PowerBI.

Requisitos de Instalación

Esta herramienta consta de solo dos archivos que deben estar siempre en la misma carpeta:medicion_aerodromos.html (El código fuente de la aplicación).logo aigs.png (El logo corporativo que se muestra en la cabecera).No se requiere instalar ningún software adicional, solo un navegador web moderno (Google Chrome, Apple Safari, Microsoft Edge).
¿Cómo usarla en el celular (Trabajo en Terreno)?
Dado que las mediciones se realizan de pie y en movimiento, la mejor forma de usarla es: Envía ambos archivos (.html y .png) a tu celular (vía Correo, WhatsApp o cable).Guárdalos en la carpeta de "Descargas" o "Archivos" de tu teléfono.
Abre tu gestor de archivos, busca el archivo .html, mantenlo presionado y selecciona "Abrir con..." -> Google Chrome (o Safari en iPhone).

Importante: No lo abras directamente con el "Visualizador HTML" por defecto del celular, ya que estas vistas previas bloquean los botones por seguridad.Opcional: Para acceso rápido, una vez abierto en el navegador, selecciona la opción "Agregar a la pantalla principal".

Instrucciones de Operación
Preparación: Ubícate en un punto con buena visibilidad tanto del inicio (cola) como del final (punto de atención) del proceso.
Set-up Inicial: Cuenta a las personas que ya están esperando en la fila e ingresa ese número en la casilla "Fila Actual".
Inicio: Presiona INICIAR MEDICIÓN. El cronómetro comenzará a correr.
Registro: Presiona 📥 ENTRA cada vez que un pasajero o grupo se sume a la fila. Presiona 📤 SALE cada vez que un pasajero sea atendido y abandone el sistema.
Finalización: Al terminar el período de muestra (ej. 30 minutos), presiona FINALIZAR MEDICIÓN.
Descarga: Revisa el resumen en pantalla y presiona DESCARGAR REPORTE (.CSV). Guarda el archivo para su posterior análisis.


KPIs Generados en el Reporte
El archivo CSV exportado te entregará la siguiente información ya procesada:
Duración (min): Tiempo total de la muestra.
Carga Inicial: Pasajeros pre-existentes en el sistema.
Tasa de Entrada ($\lambda$): Pasajeros por minuto que ingresan a la fila.Tasa de Salida ($\mu$): Pasajeros por minuto que son procesados.
Tiempo Promedio en Fila ($W$): Estimación en minutos del tiempo de espera, calculado en base al promedio del largo de la fila y la tasa de llegada.
Solución de Problemas Frecuentes
"Presiono INICIAR pero no pasa nada": Estás abriendo el archivo en un visor de texto básico. Ciérralo y asegúrate de abrirlo usando explícitamente el navegador (Chrome, Safari, Edge).
"El logo no carga, sale un ícono roto": El archivo de la imagen no está en la misma carpeta que el archivo HTML, o el nombre de la imagen no es exactamente logo aigs.png (respeta los espacios y minúsculas).

Desarrollado para operaciones en terreno - AERODROMOS.IGS
