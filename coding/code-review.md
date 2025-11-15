# Code Review Assistant

## Category
Coding

## Description
A comprehensive prompt for conducting thorough code reviews with focus on quality, security, and best practices.

## Prompt

```
Please review the following code and provide feedback on:

1. **Code Quality**: Readability, maintainability, and adherence to best practices
2. **Performance**: Potential bottlenecks or optimization opportunities
3. **Security**: Vulnerabilities or security concerns
4. **Testing**: Test coverage and edge cases
5. **Documentation**: Comments and documentation quality

Code to review:
[CODE]

Language/Framework: [LANGUAGE/FRAMEWORK]
Context: [ADDITIONAL_CONTEXT]
```

## Variables

- `[CODE]`: The code snippet or file to be reviewed
- `[LANGUAGE/FRAMEWORK]`: The programming language and framework used
- `[ADDITIONAL_CONTEXT]`: Any relevant context about the codebase or requirements

## Example Usage

### Input
```
Please review the following code and provide feedback on:

1. **Code Quality**: Readability, maintainability, and adherence to best practices
2. **Performance**: Potential bottlenecks or optimization opportunities
3. **Security**: Vulnerabilities or security concerns
4. **Testing**: Test coverage and edge cases
5. **Documentation**: Comments and documentation quality

Code to review:
def process_user_data(user_input):
    data = eval(user_input)
    return data * 2

Language/Framework: Python
Context: This function processes user input for a web application
```

### Expected Output
The AI will provide structured feedback covering all five areas, highlighting issues like the dangerous use of `eval()` and suggesting improvements.

## Tips

- Include sufficient context about the project and requirements
- Specify the coding standards or style guide you follow
- Ask for specific types of feedback if you have particular concerns
- Can be adapted for different languages and frameworks
- Consider breaking large files into smaller chunks for review

## Related Prompts

- debug-helper.md
- refactoring-assistant.md
- test-generation.md

## Tags

`code-review` `quality` `security` `best-practices` `debugging`

---
**Created**: November 2025  
**Last Updated**: November 2025
