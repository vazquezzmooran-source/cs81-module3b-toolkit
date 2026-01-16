# Final Reflection

## What patterns or surprises did you notice?

The most interesting pattern I noticed was how similar functions can be built from simple operations. The `isEven()` and `isOdd()` functions are essentially opposites of each other, both using the modulo operator but with different comparison logic. This made me realize that many complex operations can be broken down into simple, reusable building blocks.

One surprise was how clean and readable JavaScript functions become when you focus on single responsibility - each function does one thing well. The predictability of mathematical operations made testing straightforward, which was satisfying.

## What logic challenged your thinking?

Initially, I struggled with the modulo operator (%) logic in `isEven()` and `isOdd()`. Understanding that `n % 2 === 0` returns true for even numbers took a moment to click. The key insight was that the modulo returns the remainder - even numbers have no remainder when divided by 2.

Another challenge was thinking about edge cases. For example, what happens if someone passes a negative number to these functions? Or a decimal? These real-world considerations made me think more carefully about function design and validation.

## How might this kind of toolkit be used in the real world?

Math toolkits like this are fundamental to many real-world applications:

1. **Form Validation**: Functions like `isEven()` could validate user input (e.g., ensuring room numbers are even on one side of a building)

2. **E-commerce**: `multiply()` is essential for calculating prices, taxes, and totals in shopping carts

3. **Game Development**: Functions like `square()` are used for distance calculations, collision detection, and scoring systems

4. **Data Processing**: These basic functions become building blocks for more complex calculations in analytics dashboards and reporting tools

5. **Financial Applications**: Doubling, multiplying, and other math operations are core to interest calculations, currency conversions, and investment projections

This assignment taught me that even simple functions, when well-designed and tested, become powerful tools that can be reused across countless applications. The process of predicting, testing, and documenting helped me develop a more systematic approach to programming.
