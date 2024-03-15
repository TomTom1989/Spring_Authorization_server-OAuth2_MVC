Implemented the New Spring Authorization server and tested it in Spring MVC (Simulating Microservices)

Spring Authoirzation Server: 
1)configuration/creating OAuth client/Spring security configuration
2) Exchange Authoirzation code for JWT access Token with Postman

Resource Server for Spring Authorization server:
1) Creating and configuring the resource server
2) Creating resource server API endpoint
3) Consume these protected endpoints


OAuth client app with Spring Authorization server:
1) finally created MVC project (simulating also Microservices architecture) with this flow:

WebOauthClient fetching info from one app to display it in HTML webpage: When write the target URL of webclient controller=> Auhtorization Server Login page=>Successful authentication=> Fetching info from the other app (got authoirzation code in redirectURI which exhange to token access with the right scope)=> Info from the other app succesfully displayed in the webOauthclient HTML page.

PS: needed to map IP adddres 127.0.0.1 to "auth-server"   (in C:\Windows\System32\drivers\etc\host file)
