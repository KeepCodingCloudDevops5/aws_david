#1.- Requisitos previos:
      He realizado 6 de 7 requisitos previos.
      El requisito de generar la SCP para denegar recursos en París y Sao Paulo no me ha funcionado. La política aplicada al user IAM si funciona, pero aplicada
      a root organizations no me ha funcionado. He probado a asociar otra cuenta distinta, pero no he sabido hacerlo funcionar.
            
#2.- La aplicación está funcionando correctamente y persistiendo los datos:
      ARN de rol de auditor: arn:aws:iam::452977502702:role/auditoria-profesor
      DNS Name del balanceador: LB-Keepcoding-Practica-2054215825.eu-west-1.elb.amazonaws.com
      En el repositorio he subido el fichero captura_webapp_OK.png que es una captura de pantala con la webapp en funcionamiento
      
#3.- Despliegue de los componentes como IaaC, con Terraform:
     - He estado investigando y aprendiendo para construir la infraestructura con terraform.
     - Por falta de tiempo no me ha dado tiempo a investigar y a construir la parte de AWS RDS, pero el resto está funcionando.
     - Cuando destruyo la infraestructura y la vuelva a generar, termina dando el error de que el Secrets Manager no se puede generar con ese nombre porque
       está agendando para ser eliminado, recorde este asunto, y tuve que ir restaurarlo desde la consola.
     - Te he dado accceso a mi repositorio Github y el archivo Terraform-David.7z contiene lo necesario para levantarlo vía IaaC Terraform.

     
     
