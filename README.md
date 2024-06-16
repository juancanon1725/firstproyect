## Authors

Juan Pablo Poveda Cañon

# First Project

Introducción a Maven, GIT, GitHub.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisitos

Maven: Automatiza y estandariza el flujo de vida de la construcción de software
Git: Administrador descentralizado de configuraciones

### Instalación

Para crear el proyecto maven se usa el siguiente comando:

```
mvn archetype:generate -DgroupId=edu.escuelaing.arsw.ASE.app -DartifactId=firstproyect -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```

![mvn_create](https://github.com/juancanon1725/firstproyect/assets/98672541/966a3cb0-eb91-48a8-ab75-c85bf0f02ac7)

### Ejecución

Para ejecutar el proyecto utilizamos el comando:

```
java -cp target/firrstproyect-1.0-SNAPSHOT.jar edu.escuelaing.arsw.ASE.app.App
```

![image](https://github.com/juancanon1725/firstproyect/assets/98672541/b3766ed9-1857-4929-9174-dfb886b88b01)


![image](https://github.com/juancanon1725/firstproyect/assets/98672541/3e4d87ab-76e3-403a-922f-c5719b9e4dbb)

# POM actualizado

![image](https://github.com/juancanon1725/firstproyect/assets/98672541/f54e3d1e-01c2-46f3-9315-f9c21d154a61)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

