FROM microsoft/dotnet:2.1.3-aspnetcore-runtime-alpine3.7
RUN apk update && apk add krb5 && apk add cifs-utils
RUN addgroup -g 1000 -S appuser && adduser -u 1000 -S appuser -G appuser
USER appuser
