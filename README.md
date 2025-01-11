# MillionManagement

## Descripción

Este proyecto está desarrollado en .NET 8 utilizando la arquitectura hexagonal. La aplicación se conecta a una base de datos MySQL para almacenar los datos. Se ha implementado autenticación en las APIs para asegurar el acceso a los recursos.

## Tecnologías Utilizadas

- **.NET 8**: El framework principal para el desarrollo del proyecto.
- **MySQL**: Base de datos relacional utilizada para el almacenamiento de datos.
- **Arquitectura Hexagonal**: El proyecto sigue el patrón de arquitectura hexagonal, también conocida como "Arquitectura de Puertos y Adaptadores", para desacoplar la lógica de negocio de las interfaces externas.

## Configuración de la Base de Datos

Es importante comenzar con la migración de la base de datos para crear las tablas necesarias. Para ello, sigue estos pasos:

### Migración de Base de Datos

1. **Abre la consola de administrador de paquetes NuGet** en Visual Studio.

2. **Ejecuta el siguiente comando** para agregar la primera migración (esto organizará las tablas y esquemas basados en los modelos definidos en tu proyecto):

   ```powershell
   Add-Migration Initial -Project Infraestructura -StartupProject MillionManagement
   
3. **Ejecuta el siguiente comando** para agregar las tablas en base de datos automaticamente:
   
    ```powershell
   Update-database


### Resumen de los pasos:

1. **Ejecutar `Add-Migration Initial`**: Se crea la migración en el proyecto `Infraestructura`, asociada al proyecto `MillionManagement`.
2. **Ejecutar `Update-Database`**: Aplica las migraciones y crea las tablas en la base de datos MySQL.
3. **Ver el video del demo**: Para más detalles sobre cómo ejecutar las migraciones correctamente.

De esta forma, ya tienes toda la información organizada en el `README.md`, y los comandos están claros para realizar la migración y crear las tablas en la base de datos MySQL.
    
