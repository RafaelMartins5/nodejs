
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

Link: https://rafaelmartins5.github.io/nodejs/
