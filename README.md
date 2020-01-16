# Vanilla-HTML Client to load data from : Apollo-GraphQL Server (standalone with data)
Cliente html para correr desacoplado y sin integración de node js:

• Descarga el archivo app.html y lee los datos en consola desde el servidor alojado en codesandbox: https://38r91.sse.codesandbox.io/

• Ejecuta directamente el servidor apollo en: https://38r91.sse.codesandbox.io/
  aplicando:
  
  query listTeams {
    teams {
      id
      institution
      nickname
      color
      favorite
    }
  }
