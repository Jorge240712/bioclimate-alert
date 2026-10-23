# 🩺 BioClimate Alert

> Una aplicación web simple en Python que monitorea el clima en tiempo real para alertar a personas vulnerables sobre olas de calor y riesgos ambientales para la salud.

---

## 🎯 Objetivo
Prevenir emergencias de salud ante eventos climáticos extremos mediante alertas tempranas y recomendaciones directas para la comunidad.

#📋 Lista de Control de Pruebas (Test Checklist)
1. Funcionalidad (Prioridad: 🔴 Alta)
Resultado esperado: La aplicación se conecta a la API y muestra la temperatura actual de Neuquén con su mensaje correspondiente.

Tareas de prueba:

[ ] El servidor ejecuta sin errores (python app.py).

[ ] La temperatura se obtiene y muestra correctamente en pantalla.

[ ] El condicional de temperatura cambia el mensaje (alerta si sube de 30°C / seguro si es menor).

2. Interfaz de Usuario / UI (Prioridad: 🟡 Media)
Resultado esperado: Diseño limpio, centrado y legible para cualquier usuario.

Tareas de prueba:

[ ] La tarjeta y el texto se alinean bien en el navegador.

[ ] Los mensajes de alerta son claros y fáciles de diferenciar.

3. Manejo de Errores (Prioridad: 🟢 Baja)
Resultado esperado: La aplicación no se detiene si se interrumpe la conexión con la API de clima.

Tareas de prueba:

[ ] Probar el bloque except para verificar que use la temperatura de respaldo si falla la red.
