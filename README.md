# 🩺 BioClimate Alert

> Una app web en Python que avisa sobre olas de calor y riesgos para la salud por el cambio climático.

## 🚀 ¿Qué hace?
Monitorea el clima en tiempo real para proteger a personas vulnerables (con asma, alergias o problemas cardíacos) de temperaturas extremas.

📋 Lista de Control de Pruebas: BioClimate Alert
1. Funcionalidad (Prioridad: 🔴 Alta)
Resultado esperado: La aplicación se conecta a la API de clima y muestra la temperatura actual de Neuquén correctamente.

Tareas a probar:

[ ] Ejecutar el servidor en Python sin errores.

[ ] Comprobar que la temperatura en la web cambia según los datos reales.

2. Interfaz de Usuario (Prioridad: 🟡 Media)
Resultado esperado: La página se ve ordenada, limpia y las alertas se entienden a simple vista.

Tareas a probar:

[ ] Abrir la web en el navegador y verificar que el diseño se vea bien.

[ ] Comprobar que el texto de alerta y los colores cambian según el clima.

3. Manejo de Errores (Prioridad: 🟢 Baja)
Resultado esperado: Si no hay internet o falla la API, la app no se rompe y muestra un valor de respaldo.

Tareas a probar:

[ ] Simular una falla de conexión para verificar que el sistema sigue funcionando con datos por defecto.
