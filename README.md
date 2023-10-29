# ECE444-F2023-Lab5
Introduction to TDD (Test-Driven Development)
## Test Cases to Project
Tests for event class (written, pushed and merged to the main branch of our project). This was completed as a part of my sprint task for week 2. 
https://github.com/ECE444/Byte_Benevolence/blob/main/Event%20Class/event_unittest.py


# What is Test-driven Development?

Test-driven development is a practice that aims to create minimal and efficient code.  It follows a test-first, code-later structure that places an emphasis on writing tests before any actual coding. By failing the tests, programmers get an idea of what is needed and produce just enough code to pass. This way we end up with clean and maintainable code without anything extra.
A TDD cycle is as follows:
1. Write a test (and fail it)
2. Write the code (to pass the test)
3. Refactor the code (improving code and design)
4. Repeat
   
As you might notice, the idea of TDD is to make *Code that Works*!

To dive deeper into the pros and cons of this type of practice, we see that TDD clearly enables us to deliver clean and robust code - reducing the time it takes to debug lengthy code by coding objectively to pass tests. Through TDD, the concept of debugging (which is the nightmare of almost every programmer) seemingly do not exist since we are doing the reverse. This also makes our code flexible and extensible with minimal risk of breaking code during refactoring stages. This is because our code is made to be simple, and adding onto basic code is often easier than implementing over complex ones. 
Aside from creating working code, TDD can also encourage us to be more thorough in test cases. In standard coding practices, it is possible that programmers may miss a type of bug that ends up propagating through later implementations and leading to massive headaches. In comparison, TDD makes it a habit of only adding more code when previous code passes the tests. Overall this practice pushes for the implementation of essential working code with little to no wasted effort from programmers while allowing improvements to design during every cycle. 

However, TDD also has its own share of problems, especially in larger and more complex projects where the process of setting up tests each time can be more time-consuming than just writing code to start. Personally, as a programmer, I often find that this structure can hinder my creativity when writing code as I have to consider all the restrictions and think about bugs even before I code. This can all seem overwhelming to me and many others. As traditional practices all revolve around code-first, test-later, it can take a while for some programmers to adapt to this very different practice. Hence there can be a learning curve or even some resistance to change to this approach in development. Lastly, since tests have to be constantly updated with code, there can be some overhead when having to maintain the extensive test suite for basically everything.
As TDD entirely depends on writing code for tests, we also have to consider that poorly written tests can lead to poorly written code!
