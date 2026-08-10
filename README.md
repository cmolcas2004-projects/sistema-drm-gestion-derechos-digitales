# Gestión y Protección de Contenidos Digitales

Sistema DRM (Digital Rights Management) desarrollado en Python para proteger contenidos digitales mediante cifrado y descifrado, gestión de licencias, autenticación y marca de agua.

## Descripción

El proyecto consiste en el desarrollo de un sistema de gestión de derechos digitales (DRM) diseñado para controlar y proteger el acceso a contenido digital.

El sistema implementa diferentes mecanismos de seguridad para garantizar que únicamente los usuarios autorizados puedan acceder al contenido protegido:

- Generación de claves criptográficas.
- Cifrado y descifrado del contenido.
- Generación y gestión de licencias.
- Autenticación de usuarios.
- Validación de licencias.
- Gestión del contenido protegido mediante un servidor.
- Incorporación de marcas de agua como mecanismo adicional de protección.

## Tecnologías

- Python
- Criptografía
- Cifrado y descifrado de contenido
- Gestión de licencias
- Autenticación
- Marca de agua digital
- Gestión de contenidos multimedia

## Funcionamiento

El sistema está compuesto por diferentes módulos que permiten realizar el proceso completo de protección y acceso al contenido digital.

### Generación de claves

`generar_claves`

Se encarga de generar las claves criptográficas necesarias para el funcionamiento del sistema.

### Generación de licencias

`generar_base_licencias`

Genera la base de licencias utilizada para controlar los permisos de acceso al contenido protegido.

### Cifrado del contenido

`cifrar_contenido`

Se encarga de cifrar el contenido digital para impedir su acceso directo sin autorización.

### Contenido del servidor

`contenido_servidor`

Gestiona el contenido protegido dentro del sistema y forma parte del flujo de acceso al contenido digital.

### Servidor de licencias

`servidor_licencias`

Gestiona las licencias y las solicitudes de autorización necesarias para acceder al contenido protegido.

### Módulo de descifrado

`modulo_descifrado`

Realiza el proceso de descifrado del contenido una vez que se ha autorizado el acceso.

### Aplicación de usuario

`aplicacion_usuario`

Es el punto de acceso del usuario al sistema DRM. Utiliza los diferentes componentes desarrollados para realizar el proceso de autenticación, validación de licencia y acceso al contenido protegido.

## Orden de ejecución

Para ejecutar correctamente el sistema, los archivos deben ejecutarse en el siguiente orden:

1. `generar_claves`
2. `generar_base_licencias`
3. `cifrar_contenido`
4. `contenido_servidor`
5. `servidor_licencias`
6. `modulo_descifrado`
7. `aplicacion_usuario`

## Flujo del sistema

El funcionamiento general del sistema sigue el siguiente flujo:

Contenido original  
↓  
Generación de claves  
↓  
Generación de licencias  
↓  
Cifrado del contenido  
↓  
Gestión del contenido en el servidor  
↓  
Solicitud y validación de licencia  
↓  
Autenticación del usuario  
↓  
Descifrado  
↓  
Acceso al contenido protegido

## Protección mediante marca de agua

El sistema incorpora una marca de agua como mecanismo adicional de protección del contenido digital.

Esta permite identificar el contenido y proporciona una capa adicional de protección frente a su distribución o utilización no autorizada.

## Mi aportación

Participación en el desarrollo del sistema DRM, incluyendo la implementación y configuración de los diferentes módulos relacionados con el cifrado y descifrado del contenido, gestión y validación de licencias, autenticación y mecanismos de protección del contenido.

## Resultados

El proyecto permite demostrar un flujo completo de protección de contenido digital, desde la generación de claves y el cifrado inicial hasta la gestión de licencias, autenticación, descifrado y acceso final al contenido protegido.

## Material del proyecto

El material completo del proyecto, incluyendo los archivos de funcionamiento, memoria y material audiovisual, se encuentra disponible en el siguiente enlace:

' https://drive.google.com/drive/folders/1zU0BQ-O6aBBd0IZVFKZV3ncp8JXDdlV7?usp=sharing '

## Documentación

La memoria técnica recoge información sobre el diseño, funcionamiento e implementación del sistema DRM, así como los diferentes mecanismos de protección utilizados.

## Proyecto académico

Proyecto desarrollado durante el Grado en Tecnología Digital y Multimedia de la Universitat Politècnica de València.
