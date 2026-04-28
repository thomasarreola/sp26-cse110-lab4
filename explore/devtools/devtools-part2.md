# Question 1
The bug was that it was taking and processing the number inputs as strings and not number, and when it added
them together it would combine strings rather then add numbers together.

# Question 2
The way I would fix it is to just do Number(num1) + Number(num2), this should convert both of them into numbers
before adding them. 