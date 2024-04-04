## Despliegue de apps Spring Boot en Railway

Crear archivo `system.properties` en el proyecto con el contenido:

* java.runtime.version=17

1. Crear cuenta en Railway.app y github.com
2. Tener configurado git en el ordenador (esto solo es necesario configurarlo en su primer uso)
   1. `git config --global user.name "Author_name"`
   2. `git config --global user.email exmaple@mail.com`
3. Subir el proyecto a Github dede Intellij IDEA desde la opcion: VCS > Share porjet on GitHub
4. Desde Railway:
   1. Crear conexion con GitHub
   2. Crear nuevo proyecto y elegir método GitHub y buscar el repositorio elejido
   3. Realizar el Deploy y habilitar el deploy automático

### NOTA
* El despligue lo realizamos en Railway de forma gratuita, este entorno nos proporciona 500h gratuitas al mes
* Heroku ya no es gratuita además de no poder subir los repositorios desde GitHub