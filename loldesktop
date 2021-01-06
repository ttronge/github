function divisors(n) {
let arr = []
    for(let i = 1; n  >= i;i++){
         if(n%i === 0 ){
            arr.push(i)
         }
    }
    if(arr.length < 2){
        return n + " is prime"
    }
    else {
        arr.shift()
        arr.pop()
        return arr
    }
}

function tribonacci(arreglo,hasta) {
    let arr = []
    let start  = 0
    for(let i = 0 ; arreglo.length > i; i++){

        arr.push(arreglo[i])
        start += arr[i]
    }                       
    arr.push(start)                               
    let begin = arr[3]
   for(let i = begin; arr.length <= hasta;i++){
       arr.push(arr[i-2]+arr[i-1]+i)
   }
   return arr 
}                                                                              
 tribonacci([1,1,1],10)