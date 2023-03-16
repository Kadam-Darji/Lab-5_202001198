# Lab-5_202001198
#Author Kadam Darji
#Date: 16-03-2023
# Static Analyzing Code.py file using pylint

Below is the screenshot of the output by analyzing Code.py using pylint:
![image](https://user-images.githubusercontent.com/81846811/225570076-f084d6a3-7de2-4726-aea5-641f4fc5aa12.png)

Errors:
1. Code.py:37:0: C0304: Final newline missing (missing-final-newline)
2. Code.py:1:0: C0114: Missing module docstring (missing-module-docstring)
3. Code.py:1:0: C0103: Module name "Code" doesn't conform to snake_case naming style (invalid-name)
4. Code.py:1:0: C0116: Missing function or method docstring (missing-function-docstring)
5. Code.py:1:23: C0103: Argument name "l" doesn't conform to snake_case naming style (invalid-name)
6. Code.py:1:26: C0103: Argument name "r" doesn't conform to snake_case naming style (invalid-name)
7. Code.py:1:29: C0103: Argument name "x" doesn't conform to snake_case naming style (invalid-name)
8. Code.py:1:18: W0621: Redefining name 'arr' from outer scope (line 25) (redefined-outer-name)
9. Code.py:1:29: W0621: Redefining name 'x' from outer scope (line 28) (redefined-outer-name)
10. Code.py:10:4: R1705: Unnecessary "elif" after "return", remove the leading "el" from "elif" (no-else-return)
11. Code.py:35:14: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)

-----------------------------------
Your code has been rated at 3.12/10

Understanding the errors:
1: This error is shown because the file doesn't have an empty line at the end of the file. It is recommended in the python source code to have a newline at the end.

2: This error is because the source code doesn't include description of this module for example what is does, how to use its classes, we can solve this error by including the description between """ and """ at the top.

3: This error is regarding the name used to address the souce code. As python suggests to use the snake-case (i.e python_code), this source doesn't have that naming convention. We can solve this error by naming the file as code_198 or similar.

4: This error is similar to the C0114. This is simply stating that function doesn't have the description of its application. Remove this error by providing decsription between """ and """.

5,6,7: This error is same as error 2. It recommends to use snake_case style to define variables.

8,9: This error is because the variables names hide the variable that has the same name in the outer scope and hides the global variables.

10: This is because when the control of code reaches that part of code it has no option but to return without checking the condition becuase that's the reason control reached there.

11: This is becuase using format() function is a old way of formatting



-----------------------------------Code2.py-------------------------------------
Below is the screenshot of the output by analyzing Code.py using pylint:
![image](https://user-images.githubusercontent.com/81846811/225580224-0c272a48-b1c9-477d-83f5-3ee2ec180580.png)

1. Code2.py:13:0: W0311: Bad indentation. Found 3 spaces, expected 4 (bad-indentation)
2. Code2.py:15:0: W0311: Bad indentation. Found 3 spaces, expected 4 (bad-indentation)
3. Code2.py:17:0: W0311: Bad indentation. Found 3 spaces, expected 4 (bad-indentation)
4. Code2.py:18:0: W0311: Bad indentation. Found 7 spaces, expected 8 (bad-indentation)
5. Code2.py:19:0: C0304: Final newline missing (missing-final-newline)
6. Code2.py:19:0: W0311: Bad indentation. Found 3 spaces, expected 4 (bad-indentation)
7. Code2.py:1:0: C0114: Missing module docstring (missing-module-docstring)
8. Code2.py:1:0: C0103: Module name "Code2" doesn't conform to snake_case naming style (invalid-name)
9.Code2.py:4:0: C0103: Constant name "num" doesn't conform to UPPER_CASE naming style (invalid-name)
10. Code2.py:9:0: C0103: Constant name "factorial" doesn't conform to UPPER_CASE naming style (invalid-name)

Understanding the erroRs:
1,2,3,4: This errors show us the unnecessary use of spaces.

5: This error is shown because the file doesn't have an empty line at the end of the file. It is recommended in the python source code to have a newline at the end.

6:  This errors show us the unnecessary use of spaces.

7: This error is because the source code doesn't include description of this module for example what is does, how to use its classes, we can solve this error by including the description between """ and """ at the top.

8: This error is regarding the name used to address the souce code. As python suggests to use the snake-case (i.e python_code), this source doesn't have that naming convention. We can solve this error by naming the file as code2_198 or similar.

9,10: This error shows that mathematical variables should be defined in the uppercase. Here, num and factorial is in lowercase. We can solve this by naming it NUM and FACTORIAL.
