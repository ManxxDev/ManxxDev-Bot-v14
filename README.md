# Bot Público y Servidor de Soporte!

<a href="https://discord.gg/YW8QdwqTMn"><img src="https://discordapp.com/api/guilds/1020715614546964491/widget.json"></a>
 
# ⚠ IMPORTANTE ⚠
Gracias por usar este código! Porfavor, si tienes dudas, errores o preguntas sobre como se usa, unete al Discord de Soporte!
<br>💛 Apoya el desarollo [**donándonos**](https://paypal.me/deustouh) 

# Guía de Instalación 🔥


## ✅ Requisitos Mínimos

  * Tener instalado una versión de [nodejs](https://nodejs.org) 16.11.0 o mayor.
  * Un [cluster de MongoDB](https://www.mongodb.com/es/cloud/atlas/) para la base de datos.
  * Hostearlo en un VPS o un Raspberry PI, para no tener tu PC encendido 24/7
  

## 🤖 Configuración Básica

   1. Introducir el Token del Bot en el archivo `./config/config.json` **NOTA:** *Si usas REPLIT, lo podrá ver todo el mundo!(usa .env entonces)*
   2. Introducir el Prefijo del Bot en el archivo `./config/config.json`
   3. Introducir la URL de MongoDB en el archivo `./config/config.json` **NOTA:** *Si usas REPLIT, lo podrá ver todo el mundo!(usa .env entonces)*
   4. Instala los paquetes del Bot usando `npm i` en la consola.
   5. Inicia el Bot usando: `node index.js` o `npm start` en la consola.
     * Si tienes un servidor linux o tienes pm2 instalado, entonces usa: `pm2 start --name Nombre_Bot index.js`

## 🎶 Sistema de Música

   Si vas a hostear el bot en Linux, deberás de instalar ffmpeg con `sudo apt install ffmpeg`
   
   Si vas a hostear el bot en Windows, te recomiendo descargar ffmpeg de la [página oficial de descarga](https://ffmpeg.org/download.html) o puedes instalar ffmpeg-static con `npm i ffmpeg-static`

# Creditos

> Si vas a usar este bot, asegúrate de darle créditos a ManxxDev y dewstouh!
