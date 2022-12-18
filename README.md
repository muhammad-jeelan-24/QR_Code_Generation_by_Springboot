# QR_Code_Generation_by_Springboot

This QR Code generation application developed by using spring boot . The main idea of this project to encrypt the message and communicate between two parties

Technical Specication: 
    JDK1.8 or above,
    Spring-boot-3.0.0
    thymeleaf
    Spring-web
    com.google.zxing
    Maven
    
How to use :

1. Checkout the project 
2. To run the application either 
   mvn install 
   java -jar target/qrcode-1.0-SNAPSHOT.jar 
   or
   mvn spring-boot:run 
3.Using url -http://localhost:8080/qrcode/{Insert message to generate QR-Code}
4.Once provide the message and hit the endpoint.
5.It will download the image-QR.PNG

   
    
