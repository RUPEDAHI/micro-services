FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
ENV ASPNETCORE_URLS http://+:83
EXPOSE 83
COPY ${source:-dockerPublish} .
ENTRYPOINT ["dotnet", "CoreAppWithDocker.dll"]
