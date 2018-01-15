FROM microsoft/dotnet:2.0.0-runtime-stretch

ARG EXE_DIR=./bin/Debug/netcoreapp2.0/publish

WORKDIR /app

COPY $EXE_DIR/ ./

CMD ["dotnet", "BC.dll"]