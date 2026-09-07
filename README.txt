Pedidos Navidad 2026 · v12

Corrección crítica PDF:
- Eliminada la captura HTML (html2canvas).
- El PDF se dibuja directamente con jsPDF con diseño visual de tarjetas.
- Lectura defensiva de campos para evitar errores 'Cannot read properties of null (reading value)'.
- Descargar PDF y Compartir PDF usan el mismo documento visual.
- Compartir cae automáticamente a descarga si el navegador no permite compartir archivos.
- Service worker actualizado a red primero para evitar versiones antiguas en caché.
