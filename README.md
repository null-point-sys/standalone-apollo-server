# Vanilla-HTML Client to load data from : Apollo-GraphQL Server 
Cliente html para correr desacoplado en el navegador sin integración de node js ni apollo server

(standalone with data) Descarga el archivo app.html, al ejecutar en un navegador carga los datos en consola haciendo fetch a https://k43hh.sse.codesandbox.io/graphql

(standalone with data) -> Ejecutar app.html alojado en codesanbox: https://509r0.csb.app/

Ejecutar directamente graphiql desde el servidor apollo: https://k43hh.sse.codesandbox.io/graphql
  
query listTeams {
    teams {
      id
      institution
      nickname
      color
      favorite
    }
  }
