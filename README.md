# Asincrono-vercel- apuntes

## deploy

se hace con netlify, vercel... y ellos son los que se conectan a nuestro repositorio para hacer el despliegue de la app (npm run vir)

Nos permiten configurar las variables de entorno


## cómo se conectan las apps 

- localhost: nuestro ordena (entorno de desarrollo)
tendremos:

        - React (archivo de entorno co vite) 
        - API en node y express con su archivo de entorno y que se conecta a mongoDB. la url de express se guarda en el archivo de entorno de react
        - dentro de mongo, tenemos una url, guardada en el archivo de entorno de express





- entorno de produccion: 

Normalmente subiremos nuestra app de react a vercel. dentro de vercel tenemos nuestras variables de entorno. tb tenemos express y mongo Atlas 

1. Publicar app react, express y mongo 
2. primero publicamos mongo en mongo atlas
3. uego api en vercel 
4. luego react en vercel 


Para poder publicar nuestra api, primero necesitamos VERCEL.JSON en el proyecto de express
archivo pbligatorio para que la api funcione. Despues:

- entramos en vercel 
- importamos proyecto desde github
- elegimos proyecto desde github 



proyecto tiene que estar subido a github 
asegurar variables vite configuradas bien 


