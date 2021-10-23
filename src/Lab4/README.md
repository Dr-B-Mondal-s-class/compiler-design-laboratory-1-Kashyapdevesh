# Lab 4 - 27 August 2021

| Sr. No. | Description | Date | Source Code | Output |
| :--: | :---- | :--: | :--: | :--: |
| 1. | WAP to recognize float and int data type. |  27/08/2021  | [Link](./recognize_float_int/recognize_float_int.l)  | [Link](./recognize_float_int/output.png)
| 2. | WAP to verify a valid identifier. |  27/08/2021  | [Link](./verify_identifier/verify_identifier.l)  | [Link](./verify_identifier/output.png)
| 3. | WAP to verify a valid keyword. |  27/08/2021  | [Link](./verify_keyword/verify_keyword.l)  | [Link](./verify_keyword/output.png)
| 4. | WAP to recognize basic operators (`PLUS(+), MINUS(-), GE(>=), LE(<=)`). |  27/08/2021  | [Link](./recognize_basic_operators/recognize_basic_operators.l)  | [Link](./recognize_basic_operators/output.png)
| 5. | WAP to determine input operators whether arithmetic or logical. |  27/08/2021  | [Link](./arithmetic_logical_operators/arithmetic_logical_operators.l)  | [Link](./arithmetic_logical_operators/output.png)

[Link to Lab5](../Lab5)

## Sample Input/Output

1. Write a program to recognize float and int data type.</br>
       Date - 27/08/2021 </br>
       [Source Code](./recognize_float_int/recognize_float_int.l) <br>
       [Output](./recognize_float_int/output.png) <br>

        Sample Input:
        ```
        001
        123.1
        Devesh
        ```
        Sample Output:
        ```
        001 is of int type
        123.1 is of float type
        Devesh neither float nor int
        ```

2. Write a program to verify a valid identifier.</br>
       Date - 27/08/2021 </br>
       [Source Code](./verify_identifier/verify_identifier.l) <br>
       [Output](./verify_identifier/output.png) <br>

        Sample Input:
        ```txt
        var
        0var
        Var_check0
        Devesh_Kashyap
        ```

        Sample Output:
        ```txt
        A valid identifier
        Not a valid identifier
        A valid identifier
        A valid identifier
        ```

3. Write a program to verify a valid keyword.</br>
       Date - 27/08/2021 </br>
       [Source Code](./verify_keyword/verify_keyword.l) <br>
       [Output](./verify_keyword/output.png) <br>

        ```
        Sample Input:
        bool
        boool
        tushar
        for

        Sample Output:
        A keyword
        Not a keyword
        Not a keyword
        A keyword
        ```

4. Write a program to recognize basic operators (PLUS(+), MINUS(-), GE(>=), LE(<=)).</br>
       Date - 27/08/2021 </br>
       [Source Code](./recognize_basic_operators/recognize_basic_operators.l) <br>
       [Output](./recognize_basic_operators/output.png) <br>

        Sample Input:
        ```
        +
        -
        >=
        <=
        ```

        Sample Output:
        ```
        It's a PLUS operator
        It's a MINUS operator
        Greater or equal to operator
        Lesser or equal to operator
        ```

5. Write a program to determine input operators whether arithmetic or logical.</br>
       Date - 27/08/2021 </br>
       [Source Code](./arithmetic_logical_operators/arithmetic_logical_operators.l) <br>
       [Output](./arithmetic_logical_operators/output.png) <br>

        ```
        Sample Input:
        +
        &&
        *
        ||
        @

        Sample Output:
        It's a valid arithmetic operator
        It's a valid logical operator
        It's a valid arithmetic operator
        It's a valid logical operator
        Neither logical nor arithmetic operator!
        ```
