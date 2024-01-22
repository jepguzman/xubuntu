# xubuntu Instalación

## Instalar Actualizaciones (terminal)
1. sudo apt update
2. sudo apt upgrade

## Instalar Visual Studio Code (terminal)
sudo dpkg -i code.deb 

## Instalar Node.JS (terminal)

1. Instalar un Manejador de Versiones de Node

   "curl -fsSL https://fnm.vercel.app/install | bash"
	 >reiniciar la terminal

3. fnm use v18.19.0
	 >para instalar la versión de Node elegida

5. node -v
	 >nos muestra la versión de Node Instalada

## Crear cuenta en github.com
    1. Deberás crear tu cuenta en el sitio usando tu correo de gmail, con la opción :
    2. Sign Up (Registrar)
    3. Recuerda que deberás recordar tu USUARIO y tu Correo con los que te registras, nos servirán adelante
    4. Crearemos un repositorio para almacenar nuestra aplicación en línea
    5. Copiaremos la dirección HTTPS que nos genera el repositorio
    6. Ejemplo del código (ver imagen) 

## Instalando GIT
    1. Vamos a nuestra carpeta personal en nuestra PC (www/web/nombre) desde tu Explorador de Archivos
    
    2. Abrimos la Terminal y instalar git en tu PC tecleamos el comando:
      • sudo apt install git
      • Damos la clave de usuario: 1 y Enter
      • Esperamos que termine la instalación
    
    3. Con eso ya tenemos instalado nuestro programa de git
    
    4. Ahora vamos a configurarlo, para eso ejecutaremos los siguentes comandos (estos son unicamente una vez) :
       • git version
       • git config --global user.name "tu_usuario_de_github"
       • git config --global user.email "tu_correo_gmail"

### Comandos de GIT para subir nuestra Aplicación a GitHub
    1. Vamos a nuestra carpeta personal en nuestra PC (www/web/nombre) desde tu Explorador de Archivos
    
    2. Abrimos la Terminal
    
    3. Y ejecutamos Visual Studio Code (VSC) con : code .
    
    4. Dentro de VSC abrimos una nueva Terminal y ejecutaremos lo siguiente: [NOTA: sin lo que está entre paréntesis]
        • git init (inicia el repositorio local)
        • git remote add origin tu_código_del_repositorio (agrega el repositorio remoto en github)
        • git add . (agrega TODOS los archivos)
        • git commit -m "primer commit" (prepara los archivos para subirlos y agrega un comentario)
        • git push -u origin master (finalmente sube los archivos a github).
        
