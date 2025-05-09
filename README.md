# personapi-dotnet
## Configuración del contenedor SQL Server con Docker

1. Instalar Docker Desktop.
2. Ejecutar el siguiente comando:

```bash
docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=YourStrong@Passw0rd" -p 1433:1433 --name sqlserver2022 -d mcr.microsoft.com/mssql/server:2022-latest
