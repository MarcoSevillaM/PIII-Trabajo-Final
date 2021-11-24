#
# Proyect Created by Marco Sevilla Martin
# Alumno de 2ndo Ingenieria Informatica 2020/21 USAL
# Contact:marcosevillam@usal.es
#

TrabajoPrograIII.jar: trabajoprograiii/TrabajoPrograIII.class controlador/Controlador.class controlador/Colocar.class controlador/CompararJug.class controlador/CompararTel.class controlador/OrdenaInicial.class modelo/LigaFem.class modelo/Jugadora.class modelo/Equipo.class modelo/Partido.class modelo/Jornada.java modelo/Datos_equipo.class vista/Vista.class

#
# Regla de construcción del jar
#
	jar cmfv manifest TrabajoPrograIII.jar trabajoprograiii/TrabajoPrograIII.class controlador/Controlador.class controlador/Colocar.class controlador/CompararJug.class controlador/CompararTel.class controlador/OrdenaInicial.class modelo/LigaFem.class modelo/Jugadora.class modelo/Equipo.class modelo/Partido.class modelo/Jornada.java modelo/Datos_equipo.class vista/Vista.class

# -------------------------------------------------
# Reglas de contruccion de todos los Argumentos.class
# -------------------------------------------------
#----------------Main----------------
#TODAS LAS DEPENDENCIAS
trabajoprograiii/TrabajoPrograIII.class: trabajoprograiii/TrabajoPrograIII.java modelo/LigaFem.java modelo/Datos_equipo.java modelo/Jugadora.java modelo/Equipo.java modelo/Partido.java modelo/Jornada.java vista/Vista.java controlador/Controlador.java controlador/Colocar.java controlador/CompararJug.java controlador/CompararTel.java controlador/OrdenaInicial.java 
	javac -cp "./biblioteca.jar" trabajoprograiii/TrabajoPrograIII.java modelo/LigaFem.java modelo/Datos_equipo.java modelo/Jugadora.java modelo/Equipo.java modelo/Partido.java modelo/Jornada.java vista/Vista.java controlador/Controlador.java controlador/Colocar.java controlador/CompararJug.java controlador/CompararTel.java controlador/OrdenaInicial.java 
	
#----------------Vista----------------

#Regla de construcción de Vista.class
vista/Vista.class: vista/Vista.java
	javac -cp "./biblioteca.jar" vista/Vista.java
		
	
#----------------Controlador----------------
#Regla de construccion de Controlador.class
controlador/Controlador.class: controlador/Controlador.java
	javac -cp "./biblioteca.jar" controlador/Controlador.java

#Regla de construccion de Colocar.class
controlador/Colocar.class: controlador/Colocar.java
	javac -cp "./biblioteca.jar" controlador/Colocar.java

#Regla de construccion de CompararJug.class
controlador/CompararJug.class: controlador/CompararJug.class
	javac -cp "./biblioteca.jar" controlador/CompararJug.java

#Regla de construccion de CompararTel.class
controlador/CompararTel.class: controlador/CompararTel.java
	javac -cp "./biblioteca.jar" controlador/CompararTel.java

#Regla de construccion de OrdenarInicial.class
controlador/OrdenaInicial.class: controlador/OrdenaInicial.java
	javac -cp "./biblioteca.jar" controlador/OrdenaInicial.java

#----------------Modelo----------------

#Regla de contruccion de LigaFem.class
modelo/LigaFem.class: modelo/LigaFem.java
	javac -cp "./biblioteca.jar" modelo/LigaFem.java

#Regla de construccion de Jugadora.class
modelo/Jugadora.class: modelo/Jugadora.java
	javac -cp "./biblioteca.jar" modelo/Jugadora.java

#Regla de construccion de Equipo.class
modelo/Equipo.class: modelo/Equipo.java
	javac -cp "./biblioteca.jar" modelo/Equipo.java

#Regla de construccion de Partido.class
modelo/Partido.class: modelo/Partido.java
	javac -cp "./biblioteca.jar" modelo/Partido.java

#Regla de construccion de Jornada.class
modelo/Jornada.class: modelo/Jornada.java
	javac -cp "./biblioteca.jar" modelo/Jornada.java

#Regla de construcción de Datos_equipo.class
modelo/Datos_equipo.class: modelo/Datos_equipo.java
	javac -cp "./biblioteca.jar" modelo/Datos_equipo.java


lean:
	rm -rf *.class
	rm -rf */*.class
clean:
	rm -rf TrabajoPrograIII.jar
all:
	rm -rf *.class
	rm -rf */*.class
	rm -rf TrabajoPrograIII.jar
	

