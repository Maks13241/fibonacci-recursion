function fibonacciRecursion(guantity, m = 5, n = 1, sumrec = []) {
    if (guantity <= 0) {
        return sumrec;
    }
    sumrec.push(m);    
    return fibonacciRecursion(guantity - 1, n, m + n, sumrec);
}

const a = fibonacciRecursion(3);
console.log("fibonacciRecursion 3:", a);

const b = fibonacciRecursion(5);
console.log("fibonacciRecursion 5:", b);

const c = fibonacciRecursion(7);
console.log("fibonacciRecursion 7:", c);
