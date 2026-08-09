# Gestión y Protección de Contenidos Digitales

Sistema DRM (Digital Rights Management) desarrollado para proteger contenidos digitales mediante cifrado, gestión de licencias, autenticación y marca de agua.

## Descripción

El proyecto implementa un sistema de protección de contenidos digitales que controla el acceso al contenido mediante un sistema de licencias y autenticación.

El sistema permite:

- Cifrar contenido digital para evitar accesos no autorizados.
- Descifrar el contenido únicamente cuando se cumplen las condiciones de acceso.
- Gestionar licencias para controlar el acceso al contenido.
- Autenticar a los usuarios antes de permitir el acceso.
- Incorporar marcas de agua al contenido para su identificación y protección.
- Separar el contenido protegido del sistema encargado de gestionar las licencias.

## Funcionamiento

El funcionamiento general del sistema se basa en las siguientes etapas:

1. **Generación de claves:** se generan las claves criptográficas necesarias para proteger el contenido.
2. **Cifrado del contenido:** el contenido original se cifra para impedir su acceso directo.
3. **Gestión de licencias:** se generan y almacenan las licencias necesarias para autorizar el acceso al contenido.
4. **Autenticación:** el usuario debe identificarse y superar el proceso de autenticación.
5. **Validación de la licencia:** se comprueba que el usuario dispone de una licencia válida.
6. **Descifrado:** una vez autorizado el acceso, el contenido puede ser descifrado.
7. **Marca de agua:** se utiliza una marca de agua como mecanismo adicional de protección e identificación del contenido.

## Tecnologías

- Python
- Criptografía
- Sistema de licencias
- Autenticación
- Marca de agua digital
- Gestión y protección de contenidos multimedia

## Estructura del proyecto

El proyecto está dividido en diferentes módulos encargados de las distintas funciones del sistema:

- `generar_claves.py` — generación de claves criptográficas.
- `generar_base_licencias.py` — creación y gestión de la base de licencias.
- `cifrar_contenido.py` — cifrado del contenido.
- `contenido_servidor.py` — gestión del contenido protegido.
- `servidor_licencias.py` — gestión y validación de licencias.
- `modulo_descifrado.py` — descifrado del contenido autorizado.
- `aplicacion_usuario.py` — aplicación utilizada por el usuario para acceder al contenido.
- `utilidades_criptografia.py` — funciones auxiliares relacionadas con la criptografía.

## Resultados

El proyecto permite demostrar un flujo completo de protección de contenido digital:

**Contenido original → Cifrado → Licencia y autenticación → Validación → Descifrado → Acceso al contenido protegido**

Además, se incluye una demostración en vídeo del funcionamiento del sistema.

## Documentación

La documentación detallada del proyecto se encuentra en:

`Memoria_Proyecto_DRM.pdf`

También se incluye la presentación utilizada para explicar el funcionamiento y desarrollo del proyecto.

## Trabajo en equipo

Proyecto desarrollado en grupo durante el Grado en Tecnología Digital y Multimedia de la Universitat Politècnica de València.
