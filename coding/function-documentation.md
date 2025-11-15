# Function Documentation Generator

## Category
Coding

## Description
Generate comprehensive documentation for functions and methods, including descriptions, parameters, return values, and examples.

## Prompt

```
Generate documentation for the following function:

[FUNCTION_CODE]

Please provide:
1. A clear description of what the function does
2. Parameter documentation (name, type, description)
3. Return value documentation (type, description)
4. Usage examples
5. Any important notes or edge cases
6. Time/space complexity if applicable

Documentation style: [STYLE] (e.g., JSDoc, docstring, XML comments)
```

## Variables

- `[FUNCTION_CODE]`: The function or method to document
- `[STYLE]`: The documentation format/style (JSDoc, Python docstring, Javadoc, etc.)

## Example Usage

### Input
```
Generate documentation for the following function:

function calculateDiscount(price, discountPercent, membershipLevel) {
    if (membershipLevel === 'gold') {
        discountPercent += 10;
    } else if (membershipLevel === 'silver') {
        discountPercent += 5;
    }
    return price - (price * discountPercent / 100);
}

Please provide:
1. A clear description of what the function does
2. Parameter documentation (name, type, description)
3. Return value documentation (type, description)
4. Usage examples
5. Any important notes or edge cases
6. Time/space complexity if applicable

Documentation style: JSDoc
```

### Expected Output
The AI will generate complete JSDoc documentation including @param, @returns, @example tags with descriptions.

## Tips

- Provide the complete function signature and implementation
- Specify your preferred documentation style for consistency
- Include context about the function's purpose in the larger system
- Can be used for classes, methods, and entire modules
- Ask for specific documentation elements if needed

## Related Prompts

- code-review.md
- refactoring-assistant.md

## Tags

`documentation` `comments` `functions` `api-docs`

---
**Created**: November 2025  
**Last Updated**: November 2025
