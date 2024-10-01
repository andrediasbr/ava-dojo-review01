# Use a imagem oficial do .NET como base
FROM mcr.microsoft.com/dotnet/aspnet:6.0
WORKDIR /app
EXPOSE 80

COPY ./src-dotnet-webapi.dll .
ENTRYPOINT ["dotnet", "src-dotnet-webapi.dll"]