FROM microsoft/aspnetcore-build:2.0 AS build
WORKDIR /src
COPY CFlix.ImageViewer.csproj ./
RUN dotnet restore

COPY . ./
RUN dotnet publish -c Release -o out

FROM microsoft/aspnetcore:2.0

WORKDIR /app
ARG source
COPY --from=build /src/out ./

EXPOSE 5000

WORKDIR /app

ENTRYPOINT ["dotnet", "CFlix.ImageViewer.dll"]
