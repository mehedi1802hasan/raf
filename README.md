
mkdir (projectName)
cd projectName
npm init -y
code .  --- 'start':'node index.js'
npm i express cors mongodb dot


const express =require ('express');
const app=express();
const port =process.env.PORT || 5000;
// const cors =require ('cors')

// app.use(express.json());
// app.use (cors());


app.get('/',(req,res)=>{
res.send("server runnign on....")
})
app.listen(port,()=>{
console.log(`server port:${port}`)
})
