# JavaScript Theory Questions.

1.  Difference between == and === ?
    <details>
        <summary>Answer</summary>
        
        `==` is a abstract equality operator.
        `===` is a strict equality operator.
        
        Abstract equality: Checks the type of both operands, if type is same then it calls Strict equality operator (===). If types are not same then type conversion occurs (coercion) and then comparision happens.

        Strict equality: Checks type of both operands, if types are different then it returns false. If types are same then value comparision happens. (strict operator never do type conversion)

        [Note: Both Abstract and Strict equality operator checks type of the operands :)]
    </details>
