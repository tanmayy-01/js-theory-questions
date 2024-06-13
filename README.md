# JavaScript Theory Questions.

1.  **_What is Node ? a library or framework ?_**
    <details>
    <summary>Answer</summary>

    - Node is neither a library nor a framework, it's a runtime envornment which helps the javascript to run inside the terminal.

    - It is similar to browser but it does not provide browser based feature, instead it's provide lots of OS based feature.
    </details>
2.  **_Difference between == and === ?_**
    <details>
    <summary>Answer</summary>

    `==` is a abstract equality operator and `===` is a strict equality operator.
        
    - **_Abstract equality_** : Checks the type of both operands, if type is same then it calls Strict equality operator (===). If types are not same then type conversion occurs (coercion) and then comparision happens.

    - **_Strict equality_** : Checks type of both operands, if types are different then it returns false. If types are same then value comparision happens. (strict operator never do type conversion)

    [ **_Note_** : Both Abstract and Strict equality operator checks type of the operands :)]
    </details>
