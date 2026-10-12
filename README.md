# Contratos SIARQ

Generador de Contratos Individuales de Trabajo (sujetos a periodo a prueba) de SIARQ Soluciones Integrales de Arquitectura.

- Se abre en el navegador; el contrato se arma dentro del navegador y se descarga en Word. Ningún dato de los trabajadores se envía a un servidor.
- `plantilla.docx`: plantilla oficial con etiquetas `{campo}`.
- `config.json`: datos fijos y catálogo de puestos que usa todo el equipo. Se genera desde la pestaña "Datos fijos y puestos" con el botón **Descargar config.json** y se sube aquí con *Add file → Upload files*.
- `lib/`: PizZip, docxtemplater y SheetJS incluidos para no depender de servicios externos.
