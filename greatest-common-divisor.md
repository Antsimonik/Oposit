function mygcd(x,y){
//your code here
var number1 = x; //обьявил переменные
var number2 = y;
if(number2 == 0){ return number1;} // если второе число будет 0, то останется первое, этим мы определили значние до окончательного остатка, чтоб одно число было 0, если это так, то решение сразу есть.
else{
var remainder = number1 % number2; // найдем остаток от первого числа
return mygcd(number2,remainder);
}
}
