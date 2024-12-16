I know about basic binary stuff already. 
addition and subtraction are same as usual. There is a carry and stuff. For [reference](https://www.youtube.com/watch?v=Kh3dyx2wSqc&list=PLyG2VxFPjWqDDbo1FKEvzMvj33fI22weJ&index=3&pp=iAQB)
Multiplication and division are a bit unique. For [reference](https://www.youtube.com/watch?v=tr4cqD_UEUc&list=PLyG2VxFPjWqDDbo1FKEvzMvj33fI22weJ&index=4&pp=iAQB). 

Now, we do 1's compliment for subtraction of binary numbers because computer hardware made of logic gates can't do borrowing(or it's not efficient). So instead, we calculate 1's complement of 2nd number and then add those 2 numbers. 

When you do a 1's complement to a number, in a system that can interpret 1's complement, it is equivalent to multiplying that number with -1. 
SO $0101_2 = 5_{10}$ and $1010_2 = -5_{10}$ 

In a 1's complement system, you have to first look at the most significant bit(left most bit) and if it's value is 0, it means the number is positive, and treat it just like regular binary number and convert to decimal.
If the value is 1, then it means, the value is negative, and to get magnitude, you have to perform 1's complement on it, then convert to decimal and add -ve sign. 

2's complement is where, you add 1 to 1's complement result. It helps during binary addition, where you don't have to carry over the result, but can just ignore it. 
