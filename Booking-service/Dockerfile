FROM maven:3.8.2-jdk-8
WORKDIR /Booking-service
COPY . .
RUN mvn clean install
CMD mvn spring-boot:run