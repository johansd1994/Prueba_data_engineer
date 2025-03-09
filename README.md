***Librerias necesarias***

En este proceso se necesitaron de las siguientes librerias:
numpy y pandas para poder interactuar con los dataframes
unicode para eliminar las tildes de los datos 
sqlalchemy y psycopg2 para la conexion con PostgreSQL

***Pasos para ejecutar el Script***

primero de debe instalar las librerias de Sqlalchemy y psycopg2 para poder usarlas
para esto se ejecutara los siguientes comandos por cmd o bash 

pip install sqlalchemy 
pip install psycopg2

tambien es necesario que cuente con PostgreSQL, este configurado con el usuario, clave y puerto
por Default el usuario es postgres y el puerto es 5432, cree la base de datos, en mi caso la llame ventas
si se hace algun cambio se debe modificar la linea 

engine = create_engine('postgresql://**postgres:root**@localhost:**5432**/**ventas**') #se crea la conexion con PostgreSQL

en mi caso postgres es mi usuario, root la clave, 5432 es el puerto y ventas el nombre de mi BD

una vez hecho esto se puede ejecutar el Script, abra el archivo ETL en un editor como jupyternotebook, visual studio code
ejecute todo el script 
