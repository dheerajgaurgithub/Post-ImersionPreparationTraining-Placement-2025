Problem Statement
Given two integers w and x, determine whether:

x is divisible by w OR

w is divisible by x

Based on that:

If the condition is true, add 1 to a counter y

Otherwise, add 10 to y

Print the value of y.

FUNCTION fun(w, x):
    SET y = 0

    IF (x MOD w == 0) OR (w MOD x == 0) THEN
        y ← y + 1
    ELSE
        y ← y + 10
    ENDIF

    PRINT y
END FUNCTION

CALL fun(40, 4)


Dry Run
Input:
w = 40
x = 4
Steps:
Initialize y = 0

Check conditions:

x % w = 4 % 40 = 4 ≠ 0 → False

w % x = 40 % 4 = 0 → True

Since one condition is True → enter IF block:

y = y + 1 → y = 1

Print y → Output: 1

🧾 Final Output
1
