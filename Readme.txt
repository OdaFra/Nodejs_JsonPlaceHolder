#Tener instalado NodeJs

# Desde la linea de comando (cmd o terminal), dirigirse a la carpeta de trabajo para crear el proyecto con el siguiente comando

	npm init -y

# Instalar el json-server (instrucción a ejecutar desde el cmd o terminal)
	
	npm install -g json-server

# Abrir el proyecto desde el vscode u otro editor de código preferido para crear el siguiente archivo .json

	db.json

# Es necesario modificar el archivo package.json para agregar el siguiente script de ejecución
	
	"scripts": {
    "start": "json-server --watch db.json"
  },

# En el archivo agregamos db.json los recursos a utilizar de JSONPlaceholder (para esta prueba se ha agregado dos)
	
	/albums

# Ejecutamos la siguiente instrucción en la linea de comando o terminal, para obtener el siguiente detalle

	npm start

> prueba_api_rest@1.0.0 start
> json-server --watch db.json


  \{^_^}/ hi!

  Loading db.json
  Done

  Resources
  http://localhost:3000/albums

  Home
  http://localhost:3000

  # Accedemos desde la web a la url para comprobar

  	Congrats!
	You're successfully running JSON Server
	✧*｡٩(ˊᗜˋ*)و✧*｡

	Resources
	/albums 100x

# Para acceder y modificar recursos, puede utilizar cualquier método HTTP, en este caso para las pruebas recomiendo Postman.
	
	GET 
	POST 
	PUT 
	PATCH 
	DELETE