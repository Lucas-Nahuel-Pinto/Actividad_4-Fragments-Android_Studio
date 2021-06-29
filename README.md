<h1>Enunciado</h1>
<br/>
AGREGANDO MENÚS:

     Crea un menú de opciones que muestre el Item “Contacto” y el Item “Acerca De”
<br/>    
<img src="https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/gvP2TgNnEeahzgq54E2myw_5a1924be5d2c6bd8cff7dad23af0bfd8_Mo_dulo-5-y-6_1.png?expiry=1625097600000&hmac=0_V4t4eIKWAvoAtNmKp2utFyg-UctAWCYIs_tlSBZvQ" />

Contacto deberá:

    Llevarte a una pantalla con un formulario en el que solicites el nombre, el correo y su mensaje (utiliza los EditText de Material Design), 
    Además habrá un botón de “Enviar Comentario” el cual tomará la información recopilada y con ayuda de la librería JavaMail envíe un mail con el comentario del contacto.
    
Este es el enlace con la documentación de JavaMail: https://java.net/projects/javamail/pages/Android

Acerca De, deberá llevarte a una pantalla con la Bio del desarrollador.

FRAGMENTS

A partir de la siguiente imagen de maqueta: 

    Modulariza el proyecto anterior en Fragments para que estos puedan ser mostrados en un ViewPager.
    
<br/>
<img src="https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/W592_gNrEeaaqg5MSeYjIQ_d09987d1704bd0d6f066dc8e31a98b40_mo_dulo-5-y-6_2.png?expiry=1625097600000&hmac=QTwNULMJk9syGTR629RbD2spHIZmXyDR1wE55YcLYw8" />
    
2. Crea un Fragment Adicional que muestre el perfil de nuestra mascota. Tendrá su foto de perfil, su nombre y un RecyclerView en donde se mostrarán todas las fotos que ha subido se acomodarán en forma de Grid. 

3. Cada ítem deberá contener la foto y la cantidad de raits que se le han dado representado por huesos. Recuerda que todos los datos son dummy.

Puedes utilizar esta librería para generar una imagen redonda como foto de perfil de la mascota: https://github.com/lopspower/CircularImageView  
