FROM mcr.microsoft.com/dotnet/sdk:6.0 AS build
WORKDIR /src
COPY BlazorApp.csproj .
RUN dotnet restore "BlazorApp.csproj"
COPY . .
RUN dotnet build "BlazorApp.csproj" -c Release -o /app/build
FROM build AS publish
RUN dotnet publish "BlazorApp.csproj" -c Release -o /app/publish

#docker build -t mymicroservice .
#docker run -it --rm -p 3000:80 --name blazorapp blazorapp
