FROM microsoft/dotnet:1.0.0-core
WORKDIR /app
ENV ASPNETCORE_URLS http://*:53507
EXPOSE 53507
ENTRYPOINT ["dotnet", "Mvc.Client.dll"]
COPY . /app
