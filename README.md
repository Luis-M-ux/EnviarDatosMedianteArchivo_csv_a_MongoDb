# EnviaryDatosMedianteArchivocsv_a_MongoDb
App Local para enviar datos y Crear esquema en MongoDB Mediante archivo csv

1--La aplicacion fue desarrollada en Linux Mint derivada de Ubuntu Linux la configuración esta basada en sistema Linux
2--Para ejecutar la aplicación en el entorno local se debe tener instalado MongoDB en el equipo a realizar la ejecucion
3--Asi Mismo Tener instalado Git, Nodejs, npm,
4--Clonamos el proyecto y abrimos en terminal desde la ubicacion del Proyecto, tambien se puede Iniciar en visual o cualquier editor y utilizar la Terminal integrada
5--Estando en la ubicación el proyecto desde terminal ejecutamos npm install para que se instalen las dependencias necesarias
6--Desde Terminal y en la ubicación del proyecto iniciamos el servidor con el comando   node app.js  y nos debe devolver un mensaje similar o el mismo a continuación server run at port 3000 conected to Db!! , nos debe indicar el puerto de la conexión en este caso el 3000 nos dirigimos a un navegador y escribimos localhost:3000(cabe resaltar que debe ir el puerto que nos indica), si todo va bien nos debe mostrar una vista donde nos pide cargar el archivo csv le damos en cargar nos llevara a la carpeta del equipo y nos dirigiremos a la ubicacion del proyecto, mas puntualmente a la ruta StackMern/public/uploads  y alli encontraremos el archivo   Datos_de_Prueba_Personas.csv  el cual tiene solo dos filas de datos de usuarios (podemos agregar las que se deseen) seleccionamos el archivo el cual sera cargado y damos click en submit y se creara el esquema en MongoDb y asi mismo los datos en el interior del arcivo CSV se guardaran en MongoDB e igual nos devolvera la información almacenada en la Db,la cual podremos visualizar en una tabla en la misma vista, si agregamos mas registros al archivo seguiran aumentando en la base de datos, igualmente en la tabla de la vista.
