#See https://aka.ms/containerfastmode to understand how Visual Studio uses this Dockerfile to build your images for faster debugging.

FROM mcr.microsoft.com/dotnet/aspnet:6.0 AS base
WORKDIR /app
COPY . .
ENV ASPNETCORE_URLS http://localhost:5000
ENTRYPOINT ["dotnet", "MVCCoreApp.dll"]