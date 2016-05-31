# dotnet-docker-hello-world
Hello World in dotnet that runs on docker

## How to run locally
```
dotnet restore
dotnet run
```

## How to run on docker (with microsoft/dotnet:1.0.0-preview1)
```
docker build -t hellodotnet .
docker run hellodotnet
```
