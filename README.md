Oh... Google is already preparing. http://highscalability.com/blog/2016/7/6/machine-learning-driven-programming-a-new-programming-for-a.html





# EDD: Example Driven Development
my thought of Example Driven Development. inspired by http://www.wilfred.me.uk/blog/2016/07/30/example-driven-development/

## Concept

If you collect input/output example dataset, you can get implementation.

Training with source code with unit test. It generates model which can generate implementation.

### Training

- Input method or function with unit test code/data.
- It contains input and output and function.
- Model is trained for function generator.

### Generation

- Input input data and output data.
- Model generates candidate of function.

### Problem

This is not suitable for function which has side effect like File I/O, UI, access/modify instance variable.
