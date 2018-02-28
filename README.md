# ES6 I want to know 💪

## Notes
- `var` has function scope / `let` has block scope (`{ }` is a block).


## Tips

**1. Is var Dead. What should I use?**
- Use `const` by default
- Only use `let` if rebinding is needed
- `var` shoudn't be used in ES6

**2. Arrow function**
- Switch two variables'value with `[first, second] = [second, first]`
- Understanding `this` object in arrow functions.


## Snippets

1. Default arguments
```
function calculateBill(total, tax = 0.13, tip = 0.15) {
  return total + (total * tax) + (total * tip);
}
```
