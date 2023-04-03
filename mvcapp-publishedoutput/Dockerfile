FROM mcr.microsoft.com/dotnet/aspnet:6.0
WORKDIR /app
COPY . .
EXPOSE 80
#ENV ASPNETCORE_URLS http://*:5000
ENTRYPOINT ["dotnet", "MVCCoreApp.dll"]