# Guia rapida

## Convertir una URL

1. Abre la pestana Actions.
2. Entra en Convertir HTML a Divi JSON.
3. Pulsa Run workflow.
4. Pon:
   - source_type: url
   - source_value: la URL de la pagina
   - divi_version: divi5 o divi4
5. Ejecuta.
6. Al terminar, descarga el artefacto page2divi-output.
7. Dentro deberia estar el page.json.
8. En Divi Builder importa ese page.json desde Portability / Import.

## Convertir un HTML del repositorio

1. Cambia el archivo input/page.html por tu HTML.
2. Abre Actions.
3. Ejecuta Convertir HTML a Divi JSON con:
   - source_type: file
   - source_value: input/page.html
   - divi_version: divi5 o divi4
4. Descarga page2divi-output.

## Resultado

El workflow genera la carpeta output con el JSON y medios que Page2Divi consiga extraer.
