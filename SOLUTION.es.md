# 💡 Solución

> ⚠ Si en algún momento te sientes atascado y no puedes avanzar, puedes consultar la solución proporcionada. Sin embargo, te animamos a que intentes resolver las vulnerabilidades por tu cuenta primero, ya que esto te brindará una experiencia más enriquecedora en el análisis de ciberseguridad.

Ahora bien, para abordar este proyecto como analista de ciberseguridad para 4Geeks Academy, para identificar y resolver el problema. A continuación, se describen las vulnerabilidades presentes en la máquina que deberás investigar.


### Vulnerabilidades Configuradas en la Máquina

 - **Configuración de MySQL:** Se ha creado intencionalmente un usuario de base de datos con una contraseña débil. Investiga cómo esta configuración puede comprometer la seguridad de la base de datos.

- **Configuración de FTP:** El servidor FTP está mal configurado, permitiendo accesos inseguros que exponen archivos y servicios. Examina los permisos de acceso y la configuración del servidor.


- **Configuración de SSH:** El acceso SSH ha sido configurado para permitir autenticación con contraseñas débiles. Evalúa el método de autenticación y su fortaleza.

- **Puertos innecesarios abiertos:** Verifica que existen puertos abiertos innecesarios, lo que aumenta la superficie de ataque del sistema. Identifica cuáles son estos puertos y los servicios asociados.

- **Permisos incorrectos en wp-config.php:** El archivo wp-config.php, que contiene credenciales críticas de la base de datos, está expuesto a usuarios no autorizados debido a permisos demasiado permisivos. Revisa los permisos asignados a este archivo.


- **Directorio web listable:** Los directorios web han sido configurados para ser listables, lo que permite a los atacantes explorar y acceder a archivos que deberían estar ocultos o protegidos. Investiga la configuración del servidor web para entender cómo se permite esta indexación.

Estas instrucciones te guiarán en la identificación de las vulnerabilidades presentes en el servidor. Una vez que las hayas documentado, podrás proceder a elaborar un informe sobre tus hallazgos.