FROM microsoft/dotnet:1.0.0-core
WORKDIR /app
ENV ASPNETCORE_URLS http://*:54540
EXPOSE 54540
ENTRYPOINT ["dotnet", "Mvc.Server.dll"]
COPY . /app
