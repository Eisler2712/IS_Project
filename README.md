#### README

## Introducción
Este proyecto es una API para un Aeropuerto desarrollada en .Net 7.0. La API proporciona funcionalidades esenciales para la gestión de operaciones aeroportuarias.

## Características
- Gestión de vuelos: creación, actualización y eliminación.
- Gestión de pasajeros: registro y verificación.
- Gestión de personal: asignación de tareas y horarios.

## Instalación
Para instalar y configurar este proyecto, sigue los siguientes pasos:

1. Clona el repositorio:
   ```
   git clone https://github.com/Eisler2712/IS_Project.git
   ```
2. Navega al directorio del proyecto:
   ```
   cd IS_Project
   ```
3. Restaura los paquetes NuGet:
   ```
   dotnet restore
   ```
4. Compila el proyecto:
   ```
   dotnet build
   ```

## Uso
Para ejecutar la API localmente, usa el siguiente comando:
```
dotnet run --project APIAeropuerto
```
La API estará disponible en `https://localhost:5001`.

## Documentación de la API
### Endpoints principales

- **GET /vuelos**: Obtiene la lista de vuelos.
- **POST /vuelos**: Crea un nuevo vuelo.
- **GET /pasajeros**: Obtiene la lista de pasajeros.
- **POST /pasajeros**: Registra un nuevo pasajero.
- **GET /personal**: Obtiene la lista de personal.
