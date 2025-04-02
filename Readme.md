# Moodle
Como siempre empezamos con la istalación que anteriormente ja he mostrado en otros repositorios.

## Instalacion

El primer paso de la instalacion sera personalizarlo nos preguntara nuestro nombre, contraseña, apellidos, direccion de correo, ciudad, pais, zona horaria y por ultimo nos preguntaran si queremos añadir una descripcion a nuestro perfil.


![f1](https://github.com/user-attachments/assets/b5e40c1b-da01-41ff-8c45-06afe4f7141d)



![f2](https://github.com/user-attachments/assets/2aa36438-0eb8-4500-ad20-a8e8f01a716c)


## Crear el Moodle


Una vez ja tenemos nuestro perfil creado llega el momento de crear nuestro **Moodle**.


Nos pediran varias cosas como el **Nombre del Moodle, Nombre corto, Zona horaria,Contacto de soporte, Correo Saliente**.

![f3](https://github.com/user-attachments/assets/60f7b8f3-ad24-4de7-9997-b8e71a4d0f1a)



![f4](https://github.com/user-attachments/assets/1e0ccdfb-7483-45e8-9a7e-bdec12dd0974)

**Hay que recordar que siempre que acabemos de editar algo darle al boton Guardar cambios.**

## Configuracion

Lo primero que se nos pide al entrar la moodle es cambiar nuestra contraseña en caso de haberla dejado por defecto pero como ja la he cambiado da igual, tambien nos pide cambiar el nombre del curso pero ja tenemos nuestro nombre escogido entonces tampoco nos interesa, el idioma de nuestro sitio es el que vamos a dejar.

 
 Lo si que hermos sera comprobar la zona horaria de nuestro portal sea el correcto para la hora de entregar las tareas no haya problema.

 ![f5](https://github.com/user-attachments/assets/f1b46670-be0d-4dd5-acf5-335187dbc22f)


 Una vez hemos comprobado la zona horaria tenemos que cambiar la politica de las contraseñas para que se de como minimo 4 digitos en los cuales tienen que inculuir ***Majusculas, Minusculas y cifras***. `Administració del lloc > Seguretat > Normatives del lloc.`



 ## Creacion de cursos

 Una vez ya he cambiado toda la configuracion como se nos pide creamos 2 cursos: Un curso **A** que este formado por 3 temas i otro curso que se llame **B** que este formado por 5 temas. `Cursos > Afegeix curs`




 Una vez he credo los **2 cursos** entramos a uno y subimos un PDF y ahora tenemos completa libertat para usar el boton de `actiar edicion`


 ## Creacion de usuarios

 Tengo que crear un usuario manualmenmte que se llame **`Bob`** con el metodo de auteticacion manual. `Administració del lloc > Usuaris > Comptes > Afegeix un usuari`


 Ahora hay que generar 10 alumnos automaticamente con un archivo **`CSV`**
 ```console
username,firstname,lastname,email,password
blobesponja,Blob,Esponja,blobesponja@elpuig.xeill.net,Abc123!
jsongoku,JSON,Goku,jsongoku@elpuig.xeill.net,Abc123!
canceligretel,Cancel,Gretel,canceligretel@elpuig.xeill.net,Abc123!
davidelgnome,David,Gnome,davidelgnome@elpuig.xeill.net,Abc123!
ritahardware,Rita,Hardware,trritahardwarees@elpuig.xeill.net,Abc123!
```

## Usuarios

Una vez tengo creado los usuarios los matriculo en los **dos** cursos.

**a)** Haz que en el curso A no haya posibilidad de inscripción (es decir, que sólo se permita el acceso de visitante de forma que el curso sea totalmente público sin control de usuarios -ni alumnos ni profesores-). Por otra parte, haz que en el curso B se necesite registro manual de usuarios (es decir, que sea el administrador -tú- quien matricule a cada usuario en el curso, ya sea como profesor o como alumno). Todo esto lo puedes hacer desde `Administración del curso > Usuarios > Métodos de inscripción`. Si no sale algún método de inscripción disponible, debes activarlo en: `Administración de sitio > Conectores > Autenticación > Gestión de la autenticación`


 






