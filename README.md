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
##ejercicio4 
function stringMultiplicar(n) {
    var salida= "";
    var producto;

   for(var i=1;i<=10;i++){
       producto =n*i;
       salida +=n+"x"+i+"="+producto;
       if((i+1)<=10){
    salida += "/";
        }
   } 
    

return salida
}

##ejercicio 5

function casiPalindrome(palabra) {
 var tam=palabra.length;
    var palindrome;
    var count=0;
    for(var i=0, j=tam-1; i<tam/2, j>tam/2; i++, j--){
        if(palabra[i]!=palabra[j]){
            count ++;
        }
    }
        if(count<=2){
            palindrome=true;
            
        }
        else{
            palindrome=false;
        
        
    }
    return palindrome;
}
