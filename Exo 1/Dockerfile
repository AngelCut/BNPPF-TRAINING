FROM ubuntu

RUN apt-get update -y
RUN apt-get install openjdk-8-jdk -y

COPY ./java-src/Main.java /app/java/Main.java

WORKDIR /app/java/

CMD ["javac", "Main.java"]

#A lancer avec:  "docker run -d -v /c/Users/ancuttit/Desktop/delme/java-src/:/app/java compilejava"