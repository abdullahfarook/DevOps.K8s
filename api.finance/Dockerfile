
# Stage 1, based on Nginx, to have only the compiled app, ready for production with Nginx
FROM mcr.microsoft.com/dotnet/aspnet:5.0-alpine3.12
RUN apk add --no-cache icu-libs
ENV DOTNET_SYSTEM_GLOBALIZATION_INVARIANT=false
COPY ./drop/ App/
WORKDIR /App
EXPOSE 80
EXPOSE 443
ENTRYPOINT ["dotnet", "Api.dll"]