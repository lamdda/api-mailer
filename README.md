# api-mailer
api para enviar formulario de contacto por medio de AWS


******* instrucciones para uso ******


1. $ npm i -g serverless

2. serverless config credentials \
    --provider aws \
    --key xxxxxxxxxxxxxx \ (ingresar credenciales de AWS, IAM user)
    --secret xxxxxxxxxxxxxx
    
3. $ serverless deploy


NOTA: los comandos serverless se deben correr en la carpeta local donde se alojen los archivos de la API.


Editado por: Cesar Abreu
