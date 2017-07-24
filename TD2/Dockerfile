FROM microsoft/aspnetcore-build:latest
ARG source
WORKDIR /app
EXPOSE 80
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "TD2.dll"]
