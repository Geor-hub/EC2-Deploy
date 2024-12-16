# EC2-Deploy
Desafío - Configuración de GitHub Actions para despliegues en EC2

Se creara y gestionara una instancia EC2 en AWS usando GitHub Actions para automatizar el proceso de creación y configuración de la instancia. 

Este reto proporcionará los conocimientos necesarios para crear instancias EC2, gestionar la seguridad y el acceso a través de SSH, configurar redes en una VPC y utilizar AMIs personalizadas.

El proceso inicia con la activación al ejecutarse un push a la Branch main, y luego se definen los secretos que se encuentran configurados para la conexión segura con AWS.

A continuación, se guarda la clave SSH privada y se procede al lanzamiento de la instancia EC2 indicando cada uno de los datos específicos de dicha instancia.

El proceso finaliza con una limpieza con el objetivo de evitar riesgos para la maquina virtual y la red.
