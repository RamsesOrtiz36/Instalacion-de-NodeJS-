# Instalacion-de-NodeJS-y-Node-Red
Se instala NodeJS para usar Node Red, programar de forma grafica la comunicación entre dispositivos de IoT

## Instalación de Node.js
Primeramente se debe ingresar al repositorio de [distribución de linux](https://github.com/nodesource/distributions/blob/master/README.md) basados en debian y ubuntu, paquetes, enterprise linux fedora y snap.

Luego se busacará la version de **Node.js LTS (v16.x)**
Ahí nos muestra dos instrucciones pero antes de ejecutarlas hay que tener instalado curl en ubuntu, para esto usamos:

         sudo apt install curl
         curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash - &&\
         sudo apt-get install -y nodejs

Ya se instalo Node.js, lo siguiente es instalar Node-red
## Instalación de Node-Red
Desde la pagina principal de node-red nos movemos a la documentción y seleccionamos el recuadro de "getting started" y luego la opcion de [Runnig locally](https://nodered.org/docs/getting-started/local) no spide de prerequisito tener instalado Node.js y nos da enlace para la instalacion, como ya lo tenemos seguimos con el siguiente paso.

         sudo npm install -g --unsafe-perm node-red
      
y cuando termine la instalación verificamos la version instalada con el comando 

         node-red --version
## Comandos para inicar y detener Node-Red      
Para iniciar node-red en terminal usamos

         node-red
      
La terminal se quedará trabajando y para usar node-red nos vamos  un navegador y escribimos:

         localhost:1880
              
Para salir de node-red, presionamos las teclas

         Ctrl+C
                
