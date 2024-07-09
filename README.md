# Deber 6 de Programación
## Descripción 
Estos códigos muestran una aplicación JavaFX para visualizar resultados de constructores de Fórmula 1 mediante una interfaz gráfica. La clase `Main` crea la interfaz principal que incluye un ComboBox para seleccionar un año y un TableView para mostrar los resultados de los constructores en función del año seleccionado. La lógica de la base de datos se maneja mediante varios repositorios, como `ConstructorsRepository`, que se encarga de recuperar datos de los constructores por año desde una base de datos PostgreSQL.

Los modelos incluidos, como `Constructors`, `Circuit`, `DriverResult` y `Season`, representan las entidades de la base de datos. Cada uno de estos modelos tiene sus propiedades y métodos getter y setter necesarios para interactuar con los datos de la aplicación. Por ejemplo, el modelo `Constructors` incluye campos como `name`, `wins`, `totalPoints`, y `rank`, que representan los detalles de un constructor en una temporada específica.

Los repositorios, como `CircuitRepository`, `ConstructorsRepository` y `DriverResultRepository`, contienen la lógica para conectarse a la base de datos y ejecutar consultas SQL. Estos repositorios utilizan JDBC para realizar operaciones como recuperar todos los circuitos, obtener resultados de constructores por año y listar años disponibles para consulta. Este enfoque modular y basado en repositorios permite una separación clara de la lógica de acceso a datos y la interfaz de usuario, facilitando el mantenimiento y la escalabilidad del código.

**Ejemplos de ejecución** 
________________________________________________________________________________________________________________________________________________________________________________________________
![image](https://github.com/Yadira-Quinde/Tareas6-Programacion/assets/168947646/98a494d4-b16b-4311-b4d8-181672509ff2)
![image](https://github.com/Yadira-Quinde/Tareas6-Programacion/assets/168947646/d1583b1c-7d10-4c55-9abb-5dacd43717a2)
![image](https://github.com/Yadira-Quinde/Tareas6-Programacion/assets/168947646/e274c10c-f2e8-4ee3-bb5d-8e9783d73e3a)


