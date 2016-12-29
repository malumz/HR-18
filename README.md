# HR-18
##Ejercicio 1


function forLoop(limit) {

    var total = 0;
    
for(var i=0; i<=limit;i++)
    {
        total=total+i;
    }
    return total
}

##ejercicio2
function sumaPares(n) {
var suma=0;
    for(var i=0;i<=n;i+=2){
        suma=suma+i;
    }
    return suma
}
##ejercicio3
function factorial(n) {
    var factorial = 1;
   if (n > 0){
       for(var i=1; i<=n; i++)
        {
            factorial= factorial*i;              // factorial = factorial*i;
        }
       return factorial;
   }
        

    else
    {
       return null; 
        
    }

    
}

