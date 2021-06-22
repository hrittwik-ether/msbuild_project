FROM mcr.microsoft.com/dotnet/sdk:3.1 As build-env
WORKDIR /app
COPY /publish .
ENTRYPOINT ["dotnet", "ConsoleApp.dll"]