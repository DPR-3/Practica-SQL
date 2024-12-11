# Practica-SQL
Crea notebook de Jupyter y con la librería de SQLite realiza las siguientes consultas a la base de datos "Chinook_Sqlite" (archivo proporcionado junto con los apuntes de SQL).

Actividad 2-1 (Atención al cliente)

Trabaja con la tabla Customer.

Muestra la columna Email.
Muestra la columna FirstName.
Muestra las columnas FirstName y LastName.
Muestra las columnas Address, Phone y Fax.
Muestra todas las columnas.
 

Actividad 3-1 (Ordenando a mi manera)

Ordena la tabla de géneros (Genre) por orden alfabético.
Corta los resultados para que solo se muestren los 6 primeros.
Subir Nota:

Muestra las últimas 2 filas de la tabla.
 

Actividad 3-2 (En busca del peor cliente)

Volvemos a usar la tabla Customer.

Muestra los usuarios que han reportado más de 3 incidencia (columna donde se cuentan es SupportRepid)
Filtra los resultados anteriores por los que viven en Brasil.
Muestra a los usuarios que tengan un código postal empezado en 7.
Muestra a los usuarios que tengan un email de hotmail.
Muestra los usuarios nacidos en Estados Unidos (USA) o Canadá (Canada).
De los resultados anteriores, muestra los que tengan un email de gmail.
Muestra al usuario que trabaja en Apple (columna Company). Te aviso que no sabes el formato de la compañía, podría ser: Apple SL, Company Apple, APPLE…
Muestra los usuario que han reportado entre 3 y 4 incidencias.
 

Actividad 3-3 (Limpieza de personal)

Usaremos la tabla Employee (empleados).

Cuenta la cantidad de empleados que hay por ciudad.
Cuenta la cantidad de empleados que hay por departamento.
Subir Nota:

Muestra la edad de cada empleado.
Calcula la media de edad por departamento (Title).
Cuenta los empleados que fueron contratados, de media, por año.
 

Actividad 4-1 (Experto en canciones)

Volvemos a usar la tabla Track (canción).

Muestra todas las canciones con el MediaType Protected AAC audio file.
Muestra todas las canciones que contengan algún MediaType con AAC.
Muestra todas las canciones que duren más de 2 minutos.
Muestra todas las canciones de Jazz.
Averigua cual es la canción más pesada.
Subir Nota:

¿Cuantos discos tiene Led Zeppelin?
De entre sus discos, ¿cuanto cuesta el disco Houses Of The Holy?
 

Actividad 5-1 (Solo compañías)

De la tabla Customer crea una vista llamada Customer_with_companies, donde estarán incluidos todos los resultados salvo cuando Company sea NULL. A partir de la vista realiza las siguientes acciones.

Ordena los resultados por orden alfabético de Company.
Muestra que compañías son de Brazil.
 

Actividad 6-1 (Dame la factura)

De la tabla Track, consigue la siguiente información.

Cual es el título de la canción que menos pesa (Bytes).
Cual es el título de la canción que más dura (Miliseconds).
Cuantas canciones cuestan 1$ o más.
Cuantas canciones hay de Queen.
Cual es la media de duración entre todas las canciones.
Cual es la media de peso entre todas las canciones de U2.
Cuantas canciones esta Bill Berry como Composer (Compositor).
Un Mb son: Bite / 1024 / 1024. Muestra todos los Tracks calculando, y renombrando, la columna Bytes en Mb.
 

Actividad 7-1 (Buscando facturas)

De la tabla Invoice, consigue la siguiente información.

Muestra: InvoiceId, nombre del cliente y BillingCountry.
Ordena de mayor a menor por Total.
Cual es el país que más a facturado.
 

Actividad 8-1 (Alimentado la productora)

Añade 5 artistas que te gusten en la tabla Artist.
Introduce el MediaType Wav.
Crea 2 discos que estén relacionados con los artistas que has creado.
 

Actividad 9-1 (Artistas desaparecidos)

Volvemos a usar la tabla Artist (canción). (usa PRAGMA foreign_keys = OFF para desactivar la comprobación)

Borra a U2.
Borra los artistas que tengan en su nombre el símbolo &.
Borra los artistas con una Id entre 201 y 230.
Borra toda la tabla de Track.
 

Actividad 10-1 (Se acabaron las rebajas)

Volvemos a usar la tabla Track (canción).

Sube el precio de todas las canciones de 0.99 a 2.99.
Sube el precio de todas las canciones de 1.99 a 4.99.
Cambia el Compositor (Composer) por Sara del TrackId número 2000.
Cambia el Compositor (Composer) por clasico de todas las canciones que empiecen con el nombre Concerto.
