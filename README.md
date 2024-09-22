# API REST para Red Social: Backend Proyecto Final del Bootcamp DWFSV3-179 - API Rest - Red Social (stack MERN)

Este proyecto es una API REST desarrollada con el Stack MERN (MongoDB, Express.js, React.js, Node.js) para una aplicación de Red Social. La autenticación se realiza utilizando JWT (JSON Web Tokens).

## Instalación

Para ejecutar este proyecto en tu máquina local, sigue estos pasos:

1. Clona este repositorio en tu máquina local (Crea un Fork si lo vas a editar):

    ```bash
    https://github.com/inesmariao/backend_snet.git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd carpeta_donde_alojarás_tu_proyecto
    ```

3. Abre el proyecto en tu editor de código, crea una carpeta en la raíz del proyecto llamada: .env: configura las variables de entorno con el string de conexión a Mongo Atlas Cloud y el puerto de conexión en local, así

    ```bash
    MONGODB_URI=aquí_el_string_de_conexión_a_Mongo_Atlas_sin_comillas_sin_espacios
    SECRET_KEY=aquí_la_clave_secreta_para_generar_el_token_de_autenticación_con_JWT
    PORT=####
    ```
    Ejemplo:
    ```bash
    MONGODB_URI=mongodb+srv://tu_usuario_mongo_atlas_cloud:tu_password@tu_cluster.configuración_de_mongo.mongodb.net/tu_nombre_bd?retryWrites=true&w=majority
    SECRET_KEY=SECRET_KEY_oTrOs_cArAcTeReS_CLAVE
    PORT=3900
    ```

4. Instala las dependencias del proyecto utilizando npm:
    ```bash
    npm install
    ```

## Ejecución de Node

Para ejecutar el servidor de Node, en la terminal escribe:
    ```
    npm run start:watch
    ```

> [!IMPORTANT]
> Asegúrate de tener Mongo Atlas Cloud configurado correctamente y la conexión de base de datos en el archivo `.env` antes de ejecutar el archivo de inicio. Este proyecto está configurado para trabajar con una conexión a Base de Datos con Mongo Atlas Cloud.
