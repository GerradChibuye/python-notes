Loops are used to repeat tasks automatically without writing the same code multiple times.

i. For Loop

fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

Explanation:
The for loop iterates over each item in a sequence (like a list).
fruit is a temporary variable that represents the current item in the list during each iteration.
Every time the loop runs, it prints the current fruit.

ii. While Loop

count = 0
while count < 5:
    print("Count:", count)
    count += 1

Explanation:
The while loop repeats as long as the condition (count < 5) is true.
count += 1 increases count by 1 each time, preventing an infinite loop.
Use break to exit a loop early or continue to skip to the next iteration.
Why it matters:
Loops make your code efficient and scalable, especially when dealing with repetitive tasks like processing lists or running calculations multiple times.


 Combining Loops and Conditionals
 
You can use conditional statements inside loops to make complex decisions repeatedly.
eg.,
numbers = [1, 2, 3, 4, 5]
for num in numbers:
    if num % 2 == 0:
        print(num, "is even")
    else:
        print(num, "is odd")
        
Explanation:
The for loop goes through each number in the list.
The if statement checks if the number is divisible by 2 (num % 2 == 0).
If true, it prints that the number is even; otherwise, it prints that the number is odd.

Why it matters:
Combining loops and conditionals allows programs to handle lists, datasets, or streams of information intelligently, making them more powerful and flexible.

✅ Key Takeaways from Notes:
Conditional statements let programs make decisions.
Loops let programs repeat actions efficiently.
Combining both allows your program to process data intelligently.
