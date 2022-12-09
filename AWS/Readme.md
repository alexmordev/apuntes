# AWS

## Temas
1. [Regiones](#regiones)
   1. [Como elegir una region](#region_elegir)
   2. [Servicios por región](#region_servicios)
2. [IAM](#iam)

<a name= "regiones"></a>

## Regiones
Una región tiene uno o más data centers, estos están conectados entre sí con un latencia ultra baja, lo que tiene dos propocitos, proteger la información contra desastres y mantener una alta disponibilidad 

<a name="region_elegir"></a>

### Cómo elegir una region
   1. Cumplimiento, algunos sectores, como el publico requieren que selecciones una región local, por tanto si el desarrollo es para el gobierno Francés, deberás elegir Francia como la región donde estará el servidor.
   2. Proximidad. Elige una región donde estarán la mayoría de tus usuarios para reducir la latencia o lag. 
   3. Servicios Disponibles. No todas las regiones tienen disponibles todos los servicios.
   4. Precios. Los precios entre zonas varían. Debes consultar el costo en cada región antes de hacer tu despliegue.

<a name="region_servicios"></a>

### Servicios por región 
Para saber los servicios que tiene cada region puede ir al siguiente enlace https://aws.amazon.com/es/about-aws/global-infrastructure/regional-product-services/ 


<a name="iam"></a>

## IAM
Son las siglas de Identity and Access Managment. Es un servicio global de Amazon
Permite crear y configurar los accesos de los usuarios. El usuario principal es el creado al crear la cuenta y nunca debe ser compartido, probablemente tampoco usado de nuevo, todo debería ser gestionado por los usuarios que se crean.
Se pueden crear grupos dentro de IAM.

### Permisos 
AWS aplica el principio de "El menor privilegio". Otorga el menor privilegio posible para cada usuario
Los permisos se pueden adminstrar por usuario y por grupo. Puedes subir un JSON con el que lograrías establecer todos los permisos de los grupos y de los usuarios.

