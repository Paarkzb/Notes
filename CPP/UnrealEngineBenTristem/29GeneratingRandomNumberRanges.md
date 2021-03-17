# 29. Generating Random Numbers Ranges

- <https://www.udemy.com/course/unrealcourse/learn/lecture/14613068#content>

- Modulus operator %
  - Performs a divison but returns the remainder!
  - It can be used to control the range of rand().
  - +1 to offset the range.
- Seeding rand()
  - We need to initialize rand() with a different seed.
    - This will product more random results
  - The best way to do this is based on computer's time.
  - include ctime library.
  - At the start of main add: "srand(time(NULL));"
  - Crates new random sequence based on the time of day.
