function factorial(n)
{
// Calculate the factorial here
if(n > 12 && n > 0) throw "RangeError";

    return n ? n * factorial(n - 1) : 1;

}
}
