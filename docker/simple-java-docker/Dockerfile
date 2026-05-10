# stable official Java runtime base image
FROM eclipse-temurin:17-jdk-alpine

# working directory
WORKDIR /app

# copying source code into the container
COPY src/Main.java /app/Main.java

# compile the Java code
RUN javac Main.java

# run the Java application when container starts
CMD ["java", "Main"]
