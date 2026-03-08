1️⃣ What is the difference between var, let, and const?
    
    ans: - var: i. Var creates global scope, 
                ii. It's value is re-assignable,
                iii. It's also re-declarable with same name.
         
         - const:i. Const creates block scope (different from var), 
                ii. It's value is not re-assignable (diff from both let and var), 
                iii. It's also not re-declarable with same name (different from var).
         
         - let: i. Let creates block scope (different from var), 
                ii. It's value is re-assignable (diff from const), 
                iii. It's not re-declarable with same name (different from var).

2️⃣ What is the spread operator (...)?

    ans:    It works like a loop. This spreads the items. Like, we can get array properties separately by it, we can  get every word from a string by it etc. 
        For example: let a = [1, 2 , 3]; let b = [a] // means b = [[1,2,3]];
                    but b = [...a] //  means b = [1,2,3] 

3️⃣ What is the difference between map(), filter(), and forEach()?

    ans:    (1)map(): it performs the given condition and returns a new array.
                    for example: [1,2,3].map(e =>e*2) // it will return a new array which is [2,4,6]. but for multiline code we have to write return.
            (2)filter(): it matches condition. if the condition is correct, it will keep, otherwise it will not take it.
                    for example: [1,2,3,4].filter(e =>e%2 === 0) // it will return a new array which is [2,4].
            (3)forEach(): it almost acts like for of loop. It gives us each value of an array separately but not an array.
                    for example: [1,2,3,4].forEach(e => {console.log(e)}) // it will give us 1 2 3 4.

4️⃣ What is an arrow function?
    ans:    Arrow funtion is a shortcut of function where we :
            i. Arrow function don't need to write key word function.
            ii. This don't need to write () if there is single parameter.
            iii. Also it don't need to write {} and return for single line code.
            for example: [1,2,3].map(e =>e*2) // here function (e){return e*2} is the the full form.

5️⃣ What are template literals?
    ans:    Template literals is a way to create string. It has some benefits. They are -
            i. Template literals can take values of variables by ${}.
            ii. It can write multi line codes without \n
            iii. It can do operation inside a string by ${};