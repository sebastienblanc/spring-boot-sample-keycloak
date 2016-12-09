Springboot Keycloak sample
=========================

## Initial setup
* Maven
* Setup a Keycloak server : check different option on https://keycloak.gitbooks.io/server-installation-and-configuration/content/ and http://www.keycloak.org/downloads.html
* Import the realm provided at the root of this repo ( springboot.json )
* Depending on where you Keycloak server run, be sure to set the right url for the `keycloak.auth-server-url` property in the `application.properties`

Default user : user / password

## Running the sample

`mvn spring-boot:run`

If you browse to `http://localhost:8080/` you should be redirected to Keycloak's login page.
