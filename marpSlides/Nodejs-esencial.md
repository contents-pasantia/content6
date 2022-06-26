---
title       : nodejs-esencial
author      : kevin Pilo
description : pasantia 22.2.
marp        : true
paginate    : true
theme       : intership1 
---
# Nodejs 

![bg height:200px left:50% ](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fres.cloudinary.com%2Fpracticaldev%2Fimage%2Ffetch%2Fs--vrvqSDHx--%2Fc_imagga_scale%2Cf_auto%2Cfl_progressive%2Ch_420%2Cq_auto%2Cw_1000%2Fhttps%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fi%2Fs15ubgod56c7butyt7eu.jpg&f=1&nofb=1)





---
# Que es nodejs
### Un entorno de ejecucion de javascript
### fuera del navegador.
### Se crea en 2009, orientado a servidores




---
# Fuera del Navegador ?

- Servidores
- Herramientas
    Transipiladores,scraping,automatizacion



---


# Concurrencia

## Monohilo,con entradas y salidas asincronas.

## Un proceso por cada nucleo del procesador.







---
# Motor V8

## Entorno de ejecucion de JS creado por Google,
## y libre desde 2008.
## Escrita en C++.
## Convierte JS en codigo Maquina en lugar de 
## interpretarlo en tiempo real.



---

# Modulos

## - Todo lo qwe no sea sintaxis de programacion, son modulos.
## - Muchos modulos vienen por defecto en el paquete de Node.
## - Puedes crear tus propios modulos.






---
# Orientado a eventos

## Hay un bucle de eventos que se ejecutan constantemente
## Puedes orientar tu codigo de forma reactiva.




---
# EventLoop

## Un proceso con un bucle que gestiona, de forma
## asincrona, todos los eventos de tu aplicacion. 







---
![bg](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.imgur.com%2FRhSv95K.jpg&f=1&nofb=1)







---


![bg](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.learnsimpli.com%2Fwp-content%2Fuploads%2F2019%2F09%2F1-6.png&f=1&nofb=1)





---
# Callbacks
## Es una funcion que es pasada como argumento a otra funcion, para ser llamada(called back) 

---
# Promesas

```javascript
 const miPromesa = new Promise((resolve, reject) => {
    let estado = false;
    if (estado) {
        resolve('Todo salio bien');
    }else{
        reject(new Error('Todo salio mal'));
    }
});

```

[promesas](../Resource/promesas.md)





---
# Async/Await
---
# Modulos
- Globals
- File system
- Console
- Errores (try/catch)
- HTTP
- OS
- Process
---
# Modulos y paquetes externos
- NPM y package.json
- Modulos utiles
- Buffers
- streams
---
# Mas..
- benchmarking(console time y timeEnd)
- debugger
- Scraping
- Automatizacion de procesos
- Aplicaciones de escritorio.






