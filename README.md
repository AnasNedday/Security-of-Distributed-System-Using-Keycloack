## Downloading Keycloack Image : 
from https://www.keycloak.org/getting-started/getting-started-docker
#### Docker Image : 
##### Start Keycloak
From a terminal, enter the following command to start Keycloak:
```sh
$ docker run -p 8080:8080 -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:23.0.0 start-dev
```
This command starts Keycloak exposed on the local port 8080 and creates an initial admin user with the username admin and password admin.

##### Log in to the Admin Console
1-Go to the Keycloak Admin Console on localhost:8080

2-Log in with the username and password you created earlier.

