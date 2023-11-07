# Pruebas Automatizadas con Cypress

Este proyecto utiliza [Cypress](https://www.cypress.io/), un framework de pruebas de extremo a extremo para realizar pruebas automatizadas en una aplicación web. Cypress permite automatizar acciones de usuario y verificar el comportamiento de la aplicación.

## Requisitos

Antes de comenzar, asegúrate de tener instalado [Node.js](https://nodejs.org/) en tu sistema.

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/Project-PediSoft/Testing.git


2. Navega al directorio del proyecto:
   ```bash
   cd Testing

3. Instala las dependencias:
   ```bash
   npm install

## Ejecución de Pruebas

Para ejecutar las pruebas, utiliza el siguiente comando:
   ```bash
    npm run cypress:open


Esto abrirá la interfaz de Cypress, donde podrás seleccionar y ejecutar pruebas individuales o en conjunto.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- `cypress/` - Contiene las pruebas Cypress.
- `cypress/integration/` - Aquí se encuentran los archivos de pruebas.
- `cypress/support/` - Contiene archivos de soporte para configuración.
- `cypress/plugins/` - Contiene complementos personalizados.

## Personalización

Siéntete libre de personalizar las pruebas para adaptarlas a tu aplicación web. Puedes agregar más pruebas en `cypress/integration/` y modificar la configuración en `cypress/support/`.

## Colaboración

Si deseas contribuir a este proyecto, puedes hacerlo a través de [pull requests](https://github.com/tu-usuario/tu-proyecto-cypress/pulls).

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).
