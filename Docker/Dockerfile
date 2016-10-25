############################################################
# Dockerfile
############################################################
FROM ymazieres/dotnet:compile

ENV ASPNETCORE_URLS http://+:5000

CMD ["sh", "/script/run.sh"]
COPY Docker/script/run.sh /script/run.sh
RUN chmod +x /script/run.sh
COPY Docker/src /src
WORKDIR /src
#TEST
