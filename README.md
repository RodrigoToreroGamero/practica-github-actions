# Practica de GitHub Actions

El propósito del repositorio es practicar GitHub Actions de la manera más simple y directa posible.

El repositorio tendrá ramas que representen niveles de dificultad para implementar CI/CD con GitHub Actions:

## Nivel 0: main
-	Implementa el workflow más simple:
-	Crea un ci.yml que corre el comando echo en una máquina virtual.
-	Hacer commit y push a origin main

## Nivel 2: java
-	Implementa un workflow con java:
-	Crea las carpetas `src/` para `.java`, `build/` para `.class`.
-	Agrega un .gitignore para ignorar la ruta `build/` y extensión `.class`.
-	Agrega un archivo `Main.java`
-	El archivo ci.yml debe ejecutar los siguientes comandos:
-	El comando para compilar Main: `javac -d build src/Main.java`
-	El comando para ejecutar Main: `java -cp build Main`