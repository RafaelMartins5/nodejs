<<<<<<< HEAD
Aqui aprendi a instalar o express do Noje.js pelo terminal git bash. 
Aprendi a chamar funcões.
Aprendi a vincular o HTML e CSS no Index.Js (peguei meu projeto do formulario)

git sta
=======
# Node.js

Aqui instalei e aprendi a usar o Express.


const express = require ("express");
const app= express();
const port = 5000;

const path = require('path');


app.get('/',(req,res)=>{
    res.sendFile(path.join(__dirname, '/index.html'));
});

app.listen(port,()=>{
    console.log("servidor rodando");
})
>>>>>>> 8ba557ca1ff5c2e94af9da4d1a7a6c0c8f32ba64
