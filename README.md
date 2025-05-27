# Schema, vecka 22
###### Backend med Node.js, vecka 3 av 5

## Introduktion

Att skydda användardata och dokumentera vår backend är avgörande för att bygga professionella applikationer. 
I denna modul lär vi oss hur man krypterar lösenord, använder JSON Web Tokens (JWT) för autentisering och hur man dokumenterar sitt API med Swagger. 
När du är klar med denna modul kommer du kunna säkra din backend och skapa tydlig dokumentation som gör din kod lätt att använda – även för andra utvecklare!

## Mål för veckan:
1. Kunna kryptera lösenord på serversidan med t.ex. bcrypt
2. Kunna skapa och hantera autentisering med JWT
3. Kunna dokumentera ett API med hjälp av Swagger
4. Förstå säkerhetsaspekter vid utveckling av API:er 
5. Kunna läsa, förstå och ge feedback på någon annans backend-kod

## Resurser

### Presentationer

* [Auth](https://docs.google.com/presentation/d/1d9B9Av--V3szkKwaM77oRjcCLCpXQXKu/edit?usp=sharing&ouid=117251319654116712560&rtpof=true&sd=true)

### Inspelade föreläsningar

**LIVE**

* [Auth, förmiddag 26 maj](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Karlstad-Arvika/EaYIV1TuKt9Pkam6AlJTdzMBgF3vvkF1WrjvnOrygOP-YA?e=eFpIte&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
* [Auth fördjupning, eftermiddag 26 maj](https://funet-my.sharepoint.com/:v:/g/personal/jesper_nyberg_folkuniversitetet_se/EYuZ8kzLEzhEuHZNLk6OH4ABJ-p667FN9wdnJNsGAJ-qXQ?e=HQKtPE&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
* [Swagger, 27 maj](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Distans/ES2yDDYg4X1AtgMV7jbYlHwB3jnZye5AEOhfEAxxUoS4_w?e=uTlQvC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - för distans

**Förinspelat** (för distansklassen)

* [01 - Auth : Koncept](https://vimeo.com/818261075/a180ef090a)
* [02 - Auth : Kodexempel](https://vimeo.com/818261111/5cd320acda)

### Lektionsrepon

* [26 maj](https://github.com/fu-node-fe24/week-22-lecture-26-maj)
* [27 maj](https://github.com/fu-node-fe24/week-22-lecture-27-maj)
* [28 maj](https://github.com/fu-node-fe24/week-22-lecture-28-maj)

### Filmer


### Länkar

* [Jsonwebtoken documentation](https://www.npmjs.com/package/jsonwebtoken)
* [Bcrypt documentation](https://www.npmjs.com/package/bcrypt)
* [Swagger documentation](https://swagger.io/docs/)

### Övningar 

Denna vecka är tanken att ni fortsätter arbeta med era Todo APIer. Ni skall:
* Kryptera alla lösenord innan de skickas till databasen
* Använda jsonwebtoken till autentisering och auktorisering istället för ```global.user``` från förra veckan
* Dokumentera ert API med Swagger 

Om ni vill så kan ni ju även passa på att bygga en frontend-app till ert API. Glöm isåfall inte bort att läsa på om [cors](https://www.npmjs.com/package/cors) så att ni kommer åt er server från klienten.






