# FundamentosAWS
https://platzi.com/clases/aws-cloud/
**1. Introducción al cómputo en la nube**
    **Class#1**
        ¿Qué es el cómputo en la nube?
            En AWS el cómputo en la nube trata de los siguiente:
                => Sitios Web, una sola computadora corriendo un solo stack de programación cómo LAMP, XAMPP, entre otros.
                => Respaldos y recuperación, incluso de sistemas operativos completos.
                => Archivos Permanentes, también puedes guardar archivos estáticos como fotografías o documentos.
                => DevOps, no solo tenemos automatización en el release de los proyectos, también cuentas con alta disponibilidad o respaldos automatizados en diversos lugares del mundo.
                => Análisis Masivos
                => Cómputo Serverless, en lugar de preocuparte por la cantidad de computadoras o cómo y cuándo va a escalar tu servicio puedes programar tu aplicación con microservicios mientras que AWS se encarga de darte los elementos necesarios.
                => Cómputo de Alto Rendimiento, levanta tus servidores sólo cuando tu aplicación lo necesita.
                => Internet of Things.
                => Aplicaciones Empresariales.
                => Distribución de media.
                => Servicios móviles.
                => Cómputo científico.
                => E-commerce.
                => Ambientes Híbridos.
                => Blockchain.        
            Ventajas de AWS:
                => Cero inversión inicial, muchos servicios son gratis el primer año
                => Usa lo que necesites, apaga lo que no
                => Crece tanto como sueñes
                => Velocidad cuando la necesitas
                => Si no lo usas, no lo pagas
                => Cobertura mundial
    **Class#2**
        ¿Cómo puedo empezar a usar AWS?
            Para crear tu cuenta de AWS debes entrar a aws.amazon.com, recuerda que para crear tu contraseña puedes usar passwordsgenerator.net.
            AWS dispone de dos programas que permiten a los clientes trasladar sus enseñanzas y esfuerzos de investigación a la nube y de este modo innovar más rápidamente y con un menor costo. Para aplicar a las becas de AWS entra a aws.amazon.com/es/grants.
            Cuando tengas tu cuenta registrada, entra a console.aws.amazon.com y tendrás acceso a la consola de amazon con todos los servicios disponibles.
    **Class#3**
        Introducción a la oferta de servicios de AWS y sus aplicaciones
**2. Introducción a la oferta de AWS y sus interacciones**
    **Class#4**
        Ejemplo de arquitectura con Elastic Beanstalk
    **Class#5**
        ¿Qué es EC2?
    **Class#6**
        Creando una instancia de EC2
    **Class#7**
        Conectándonos a nuestra instancia desde Windows
    **Class#8**
        Conectándonos a nuestra instancia desde Linux
            ssh-command: ssh -i name.pem user@ip
    **Class#9**
        Conectándonos a nuestra instancia desde OSX
            ssh-command: chmod 600 name.pem && ssh -i name.pem user@ip
    **Class#10**
        Subiendo un proyecto: Clonando un repositorio de GitHub a nuestra Instancia de EC2
    **Class#11**
        Subiendo un proyecto a nuestra instancia de EC2: Ejecutar nuestro proyecto
    **Class#12**
        ¿Qué es Lambda y Serverless?
            Creando una función Lambda
    **Class#13**
        Creando una función Lambda
**3. Elastic Beanstalk**
    **Class#14**
        Conociendo Elastic Beanstalk
    **Class#15**
        Creando un ambiente en Elastic Beanstalk
    **Class#16**
        Almacenamiento - S3
    **Class#17**
        Almacenamiento con S3: Contenido Estatico
    **Class#18**
        Almacenamiento con Glacier: Contenido duradero:
            AWS tiene un tipo de almacenamiento más económico, pero también más lento que S3 llamado Glacier. Es una muy buena opción si tienes que guardar algún tipo de archivo histórico, como documentos de transacciones de años pasados.
            Glacier podrá entregarte tus datos y/o archivos con tiempos de entre 2 y 15 minutos por archivo.
**4. Bases de Datos**
    **Class#19**
        Bases de Datos - RDS Aurora PG
            AWS creó un producto llamado RDS que optimiza el funcionamiento de un motor de bases de datos. Este servicio incluye mantenimiento a tu base de datos, respaldos diarios, optimización para tu tipo de uso, etc.
            RDS tiene varias opciones de motores de bases de datos, como: Aurora PG, Aurora MySQL, MySQL, MariaDB, PostgreSQL, Oracle y Microsoft SQL Server.
            Recuerda que AWS te da 750 horas de servicio gratis de RDS, incluyendo cualquiera de los motores de bases de datos.
    **Class#20**
        Conociendo RDS PG
            AWS implementa el motor de PostgreSQL (RDS PG) en una instancia optimizada para correr con la máxima eficacia.
            RDS PG incluye, por omisión, tareas de optimización como vacuum, recuperación de espacio en el disco duro y planificación de queries. Tambien te permite hacer respaldos diarios (o incluso más seguido) de tu base de datos.
            Otras ventajas de RDS PG son:
                => Cifrado a tu elección, tu base de datos puede estar cifrada en disco duro
                => Migración asistida: RDS PG tiene mecanismos que te ayudan a migrar tu información en caso de que tu ya cuentes con una base de datos con otro proveedor.
                => Alta disponibilidad: RDS PG te permite fácilmente configurar un ambiente de alta disponibilidad al ofrecerte diversas zonas para tu base de datos.
                => Recuerda que Amazon RDS provee de seguridad por omisión tan alta que no podrás conectarte a tu DB hasta que explícitamente lo permitas.
**Links**
    aws-platzi-python:
        https://github.com/mauropm/aws-platzi-python/tree/elastic-beanstalk
    Secure Password Generator:
        https://passwordsgenerator.net/
    Programas de AWS para investigación y educación:
        https://aws.amazon.com/es/grants/
