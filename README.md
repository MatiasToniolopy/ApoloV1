# Bienvenidos a mi repositorio 

Este proyecto se desarrolló en un transcurso de 7 dias


# Instaladores

##### 1) Compilador

- [Python3](https://www.python.org/downloads/release/python-396/ "Python3")

##### 2) IDE

- [Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code")


##### 3) Motor de base de datos

- [Sqlite Studio](https://github.com/pawelsalawa/sqlitestudio/releases "Sqlite Studio")
- [PostgreSQL](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads "PostgreSQL")
- [MySQL](https://www.apachefriends.org/es/index.html "MySQL")

##### 4) Repositorios

- [Git](https://git-scm.com/downloads "Git")

# Instalación

##### 1) Clonar o descargar el proyecto del repositorio

`git clone https://repo...`


##### 2) Instalar el complemento de [weasyprint](https://weasyprint.org/ "weasyprint")

- Si estas usando Windows debe descargar el complemento de [GTK3 installer](https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer/releases "GTK3 installer"). En algunas ocaciones se debe colocar en las variables de entorno como primera para que funcione y se debe reiniciar el computador.
- Si estas usando Linux debes instalar las [librerias](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html#linux "librerias") correspondientes a la distribución que tenga instalado en su computador.


##### 3) Instalar todas las librerias del proyecto que se encuentran en la carpeta deploy

- `pip install -r deploy/requirements.txt`

##### 6) Crear la base de datos con las migraciones y el superuser para iniciar sesión

- `python manage.py makemigrations`
- `python manage.py migrate`
- `python manage.py createsuperuser`

##### 7) Insertar información inicial en la base de datos

- `python manage.py shell`
- `from core.utilities import *`

------------

#  Si te gusta y te sirve mi contenido ✅🙏
### ¡Apóyame! para seguir haciéndolo siempre 😊👏
Paso la mayor parte de mi tiempo creando contenido y tratando de seguir aprendiendo

🤗💪¡Muchas Gracias!💪🤗

**Puedes apoyarme de la siguiente manera.**

**Enviándome un mail**
taekwondotae9@gmail.com

**Donando**
matias_remo19@hotmail.com

***Te deseo lo mejor en tu aprendizaje y crecimiento profesional como programador 🤓.***


