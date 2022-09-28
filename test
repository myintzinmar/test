const express=require ('express');
const first=express()
first.get("",(req,res)=>{
    res.send("<h1>Hello Express Web Page Server using Node.js</h1>");
})

first.get("/MZM",(req,res)=>{
    res.send("<h1>Welcome to my Home Page</h1>");
})

first.get("/basic",(req,res)=>{
    res.send("<h1>This is basic knowledge</h1>");
})

first.get("/beginner",(req,res)=>{
    res.send("<h1>I am a beginner</h1>");
})
first.listen(3000,()=>{
    console.log("Server starting up at port:3000:");
})
