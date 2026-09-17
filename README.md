# Formularios Mercado Cheque

Formulario online para que los clientes completen el **Informe comercial, ventas y deudas** y la **Manifestación de bienes**, y descarguen cada uno en PDF A4.

- Link público: https://marketingmercadocheque.github.io/formularios/
- Es una sola página estática. No hay servidor, base de datos ni envío de datos: lo que completa el cliente queda solo en su navegador (se borra solo a los 30 días sin uso, o con «Vaciar» / «Borrar mis datos de este dispositivo").
- No usa servicios de terceros: la tipografía (Poppins, OFL) y las librerías del PDF (html2canvas 1.4.1 y jsPDF 2.5.1, MIT) están en `fonts/` y `vendor/`, verificadas con su huella oficial.
- La página trae una política de seguridad (CSP) que le impide conectarse o mandar datos a cualquier otro sitio, y no funciona embebida dentro de otra página.

## Reglas para este repositorio (es PÚBLICO)

- Nunca subir datos de clientes, PDFs completados, contraseñas, tokens ni información interna.
- No activar GitHub Pages en otros repos de esta cuenta (compartirían el mismo origen que el formulario).
- Para actualizar: reemplazar `index.html` y hacer commit en `main`; GitHub Pages lo publica en uno o dos minutos.
