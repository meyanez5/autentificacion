## Supabase-Configurar una tabla de Proyectos y Perfiles

1. Inicie sesión en [Login-Supabase](https://supabase.com/)
2. Cree un nuevo proyecto y rellene los campos
3. Vaya al Editor SQL y seleccione la plantilla 'Iniciador de administración de usuarios'
4. Elimine el bloque en tiempo real y el bloque de almacenamiento de la plantilla
5. En la tabla de perfiles:
- Elimine las siguientes columnas 'avatar_url' y 'sitio web' y cambie el nombre de la columna' nombre de usuario 'a'nombre completo'
- Eliminar la restricción única aplicada en la columna 'nombre de usuario'
6. Ejecute el script y se creará la tabla 'perfiles'

## Supabase-Claves API del Proyecto

1. Iniciar sesión en Supabase
2. Vaya a la opción configuración en la barra lateral
3. Seleccione la opción API en el bloque de configuración del proyecto
4. Copie 'anónimo público' y 'URL'

## Supabase-Configurar Autenticación de Correo Electrónico

1. Iniciar sesión en Supabase
2. Vaya a la opción de autenticación en la barra lateral
3. En el bloque de autenticación de correo electrónico, deshabilitó` Confirmar dos veces los cambios de correo electrónico `y`Habilitar confirmaciones de correo electrónico'

## Supabase-Configurar el Proveedor de Google

- [Autenticacion con Google](https://supabase.com/docs/guides/auth/auth-google)

## Desarrollo

1. Clone este repositorio en un directorio y luego ejecute ' npm install`
2. Configure sus variables de entorno siguiendo el `.env.ejemplo ' archivo. NOTA: El archivo de entorno debe tener el nombre:`.env`
- Puede obtener la 'SUPABASE_URL' y `ANON_KEY` siguiendo [Supabase - Project API Keys] (#supabase-project-api-keys)
3. Ejecute 'npm run dev' para comenzar a desarrollar el modo
