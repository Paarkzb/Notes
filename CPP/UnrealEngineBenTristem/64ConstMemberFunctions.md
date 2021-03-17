# 64. Const Member Functions

- <https://www.udemy.com/course/unrealcourse/learn/lecture/16158639#content>

- Safety
  - By using **const** you protect yourself.
  - If a function doesn't change any member variables of the class, make it **const**.
  - Makes sure your functions aren't modifying your classes when you don't intend them too.
  - Also reffered to as a **const function**.
- const Functions
  - **const** functions can't call non-const functions.
  - **const** objects can only call const functions.
