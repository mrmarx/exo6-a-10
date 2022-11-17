<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script type="text/javascript">

{let chain="Ayibobo Ayiti"
chain=chain.split(" ")
let newchain=""
let chain2=chain.join("")
for(let i=1 ;i<=chain2.length;i++){
    newchain+=chain2[chain2.length-i]
}
console.log(newchain)
}
//'''''''''''''''''''''''''''''''' exo7
{
let chain=" Marx Aristal adolph"
chain=chain.split(" ")
 chain=chain.join("")
 let newchain= []
console.log(chain)
let voyelle=["a","e","i","u","o","y","A","E","O","I","U","Y"]
for (let i=0;i<chain.length;i++){
    if(chain[i].includes(voyelle)){
        chain[i-1].push("*")
    }else{
        chain+=chain[i]
    }

}
console.log(chain)
}

//.......................................exo8


let text="max max xmax max max max max "
text=text.split(" ")
text=text.join("")
console.log(text)

//...............................
let interval=[0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20]
let total=0
for(let i=0;i<interval.length;i++){
    if(interval[i]%2==0){
        total+=1
    }
}
console.log(total)











    </script>
 



</body>
</html>
