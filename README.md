Black Notes: Web App. Donde puedes crear y archivar tus notas con facil acceso y de interfaz responsive.

Ubuntu20.04 @python3.8.10
Backend:
	-Crear Entorno Virtual:

		1- Crear Entorno:
			* sudo apt-get install python3-venv
			* python3 -m venv myvenv 
			* ls
			* 
		2- Activar entorno virtual:
		
			* source myvenv/bin/activate
			
	- Crear Requeriments.txt
		* touch requirements.txt
		
	- Seleccion de los Requerimientos:
		- Django4.0
		- django-restframework3.12
		- Otros : En requirements.txt
		
	- Descargar los Requerimientos:
		* pip3 install -r requirements.txt


	- Crear Proyecto
		* django-admin startproject note .
		
	- Crear App.
		 * python3 manage.py startapp api
		 
	- Hacer Migraciones
		* python3 manage.py makemigrations
		* python3 manage.py migrate


FrontEnd:
-React (JS):
	1. Crear un Projecto: React
		* npx create-react-app
	
		* npm install react-router-dom
			json.package --> "proxy":"http://127.0.0.1:8000",
			
	npm start
	npm build 
	
	
