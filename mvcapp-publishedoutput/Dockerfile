FROM mcr.microsoft.com/dotnet/aspnet:6.0
WORKDIR /app
COPY . .
EXPOSE 5000
ENV DOTNET_URLS=http://+:5000
ENTRYPOINT ["dotnet", "MVCCoreApp.dll"]