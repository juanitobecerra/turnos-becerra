# Sistema de Turnos Online - Consultorio Cardiológico Dr. Becerra

Este proyecto es una aplicación web para gestionar turnos online en el consultorio del Dr. Becerra.  
Permite a los pacientes seleccionar fecha y horario (solo martes y jueves) para reservar su turno, además de ingresar sus datos personales.

---

## Funcionalidades

- Selección de fecha (solo martes y jueves habilitados)  
- Selección de horario disponible  
- Registro de datos: nombre, apellido, obra social, primera vez, WhatsApp, email  
- Envío de turnos a Google Sheets mediante Google Apps Script  
- Validación de horarios ocupados (en desarrollo)

---

## Archivos principales

- `turneroweb.html`: Código HTML, CSS y JavaScript para la interfaz web y lógica de reserva.  
- `calendar.js` (opcional): Código JavaScript para manejo avanzado del calendario (no usado actualmente).  
- `styles.css` (opcional): Estilos CSS adicionales.

---

## Cómo usar

1. Abrir el archivo `turneroweb.html` en un navegador o alojarlo en un servidor web.  
2. Configurar el URL del Google Apps Script en el archivo para enviar los turnos (ya configurado en el código).  
3. Acceder y realizar reservas.  
4. Ver los turnos confirmados en la hoja de Google Sheets vinculada al script.

---

## Contacto

Juanito Becerra  
[Email opcional]  
[Teléfono / WhatsApp opcional]

---

## Licencia

Este proyecto está bajo licencia MIT.  

---

*¡Gracias por usar este sistema de turnos!*
