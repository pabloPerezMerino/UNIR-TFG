# UNIR-TFG
Repositorio donde está almacenado el código del Trabajo Fin de Grado de la titulación Grado en Ingeniería Informática de la Universidad Internacional de la Rioja realizado por Pablo Pérez Merino. El trabajo se denomina **Aplicación para solicitudes de donación de material informático**.

# Estructura
Está organizado en las siguientes carpetas:
* [aplicaciones](https://github.com/pabloPerezMerino/UNIR-TFG/tree/main/aplicaciones): se almacenan los paquetes de la aplicación, importables en un entorno de PowerApps
* [diagramas](https://github.com/pabloPerezMerino/UNIR-TFG/tree/main/diagramas): diagramas de draw.io utilizados en la memoria
* [evidencias](https://github.com/pabloPerezMerino/UNIR-TFG/tree/main/evidencias): capturas para probar las aplicaciones y comprobar que se cumplen los requisitos
* [imágenes](https://github.com/pabloPerezMerino/UNIR-TFG/tree/main/imágenes): imágenes adicionales utilizadas en la memoria
* [tablas](https://github.com/pabloPerezMerino/UNIR-TFG/tree/main/tablas): ficheros de Excel con datos utilizados para cargar las tablas del entorno
* [LICENSE](https://github.com/pabloPerezMerino/UNIR-TFG/blob/main/LICENSE): fichero de licencia GNUv3
* [README.md](https://github.com/pabloPerezMerino/UNIR-TFG/blob/main/README.md): este fichero

# Requisitos técnicos
* Licencia activa de Microsoft 365 que incluya Power Apps (por ejemplo, planes E3, E5, o licencias específicas de Power Platform).
* Acceso a Power Apps a través del portal: https://make.powerapps.com
* Conectividad a fuentes de datos como:
  * SharePoint
  * Excel (en OneDrive o SharePoint)
  * Microsoft Dataverse
  * SQL Server
  * Otros conectores estándar o premium

# Requisitos organizativos
* Permisos adecuados en el entorno de Power Platform:
  * Crear y modificar aplicaciones
  * Acceder a los datos necesarios
* Usuarios registrados en el directorio de Microsoft Entra (Azure AD) si se requiere autenticación
* Entorno de desarrollo habilitado:
  * Puede ser un entorno de desarrollo, pruebas o producción

# Importar la aplicación
Para importar la aplicación en un entorno, hay que realizar los siguientes pasos:
1. Crear un entorno en la Power Platform: https://github.com/pabloPerezMerino/UNIR-TFG/blob/main/imágenes/power-platform.png
2. Crear las tablas a partir de las excel subidas: https://github.com/pabloPerezMerino/UNIR-TFG/tree/main/tablas
3. Importar los paquetes con las aplicaciones: https://github.com/pabloPerezMerino/UNIR-TFG/tree/main/aplicaciones
