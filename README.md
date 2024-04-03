<img title="a title" alt="Alt text" width="480" src="https://4266274253-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FSInMUrk5zXO1wiVbvasJ%2Fuploads%2FcZIK4ksJSZhdW0cAzM2y%2Fstargaze_logo_800.svg?alt=media&token=60d1324d-f844-4aa6-a86e-daa212634380">

FARCASTER WORKSHOP: CREACION DE NO-CODE FRAMES
======

Workshop donde analizaremos el fenómeno de los Frames en Farcaster y sus diferentes casos de uso y aplicaciones. Veremos desde herramientas hasta aplicaciones No-code que permiten la creacion de Frames sin conocimientos de programación. Orientado a personas de negocio, comunicación y redes sociales. 

## Farcaster

Stargaze Studio es una dApp para crear y administrar colecciones de NFT en Stargaze. Está diseñada para proporcionar interfaces de contratos inteligentes útiles que ayudan a crear e implementar tus propias colecciones de NFT sin escribir una sola línea de código.

### Contenido 

* carpeta con imagenes formato jpeg
* carpeta con metadatos formato json
* carpeta coleccion completa AI
* archivo csv para realizar airdrop
* archivo txt con billeteras whitelist
* PDF información coleccion AI

### Enlaces utiles 

* [Stargaze Studio TESTNET](https://studio.publicawesome.dev/collections/create/)
* [Stargaze Studio MAINNET](https://studio.stargaze.zone/)

graph LR
    subgraph Blockchain
        id[Farcaster Contracts]
    end

subgraph Message Graph
    id---hub1[<center>Farcaster Hub</center>]
    id---hub2[<center>Farcaster Hub</center>]
end

hub1---app1[<center>Server</center>]
hub2---app2[<center>Desktop Client</center>]
hub2---app3[<center>Mobile Client</center>]

subgraph App3
  app1-.-client1(Desktop Client)
  app1-.-client2(Mobile Client)
end

subgraph App2
    app2
end

subgraph App1
  app3
end
