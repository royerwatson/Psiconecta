# Psiconecta

Programas de bienestar psicológico y salud mental laboral para empresas.

[Estado del CI] — [Dependabot] — [Licencia]

Resumen
-------
Psiconecta agrupa herramientas y servicios orientados a la evaluación, seguimiento y promoción del bienestar psicológico en entornos laborales. Este repositorio principal contiene varios subproyectos (Dashboards, Empresarial, Research, Shop) con el código y recursos de cada área.

Estructura del repositorio
--------------------------
- Psiconecta-Dashboards/ — Paneles y visualizaciones (front-end).
- Psiconecta-Empresarial/ — Código y recursos para clientes empresariales.
- Psiconecta-Research/ — Materiales, scripts y datos para investigación.
- Psiconecta-Shop/ — Tienda/servicios para clientes.
- README.md — Documentación general (este archivo).
- .github/ — Configuraciones de CI, plantillas y dependabot.

Quick start (local)
-------------------
1. Clona el repositorio:
   git clone https://github.com/royerwatson/Psiconecta.git
   cd Psiconecta

2. Entra en el subproyecto que quieras probar. Ejemplo para un subproyecto con Node.js:
   cd Psiconecta-Dashboards
   npm install
   npm run dev         # o npm start según el proyecto

   Para un subproyecto Python:
   cd Psiconecta-Research
   python -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   pytest                      # ejecutar tests

Linting y tests
---------------
Recomendado:
- Node.js: npm run lint (eslint), npm test (jest/mocha)
- Python: ruff/flake8, black y pytest para tests

Integración continua
--------------------
Se han añadido workflows de ejemplo para ejecutar lint y tests en GitHub Actions (Node.js y Python). Los workflows detectan si el subproyecto tiene package.json o requirements/pyproject y ejecutan los pasos solo si existen esos archivos.

Contribuir
---------
1. Fork y branch con nombre descriptivo: feature/mi-cambio o fix/descripcion.
2. Sigue las reglas de linting y añade tests cuando sea posible.
3. Abre un Pull Request con descripción y checklist de cambios.

Plantillas y automatizaciones recomendadas
-----------------------------------------
- Añadir `.github/ISSUE_TEMPLATE/` y `.github/PULL_REQUEST_TEMPLATE/` para estandarizar contribuciones.
- Habilitar Dependabot para actualizaciones automáticas de dependencias (npm y pip).
- Añadir un archivo CONTRIBUTING.md con guía de estilo y proceso de revisión.

Contacto
--------
Maintainer: @royerwatson  
Email: (añadir email de contacto si procede)

Licencia
--------
(Añadir LICENSE según corresponda, por ejemplo MIT)