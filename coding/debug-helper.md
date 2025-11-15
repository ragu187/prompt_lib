# Debug Helper

## Category
Coding

## Description
A systematic prompt for debugging code issues by analyzing errors, understanding context, and finding solutions.

## Prompt

```
I'm encountering an error in my code. Help me debug this issue:

**Error Message:**
[ERROR_MESSAGE]

**Code:**
[CODE_SNIPPET]

**What I Expected:**
[EXPECTED_BEHAVIOR]

**What Actually Happened:**
[ACTUAL_BEHAVIOR]

**Environment:**
- Language/Framework: [LANGUAGE/FRAMEWORK]
- Version: [VERSION]
- OS: [OPERATING_SYSTEM]

**What I've Tried:**
[ATTEMPTED_SOLUTIONS]

Please help me:
1. Identify the root cause of the issue
2. Explain why the error is occurring
3. Provide a solution with explanation
4. Suggest best practices to avoid similar issues
```

## Variables

- `[ERROR_MESSAGE]`: The exact error message or stack trace
- `[CODE_SNIPPET]`: The relevant code where the error occurs
- `[EXPECTED_BEHAVIOR]`: What you expected to happen
- `[ACTUAL_BEHAVIOR]`: What actually happened
- `[LANGUAGE/FRAMEWORK]`: Your programming language and framework
- `[VERSION]`: Version numbers of relevant tools
- `[OPERATING_SYSTEM]`: Your operating system
- `[ATTEMPTED_SOLUTIONS]`: What you've already tried

## Example Usage

### Input
```
I'm encountering an error in my code. Help me debug this issue:

**Error Message:**
TypeError: Cannot read property 'length' of undefined

**Code:**
function processArray(arr) {
    return arr.length > 0 ? arr[0] : null;
}

let result = processArray();
console.log(result);

**What I Expected:**
The function should return null when no array is passed.

**What Actually Happened:**
The code throws a TypeError before it can check the length.

**Environment:**
- Language/Framework: JavaScript
- Version: ES6
- OS: Windows 10

**What I've Tried:**
- Checked if array exists
- Tried different syntax

Please help me:
1. Identify the root cause of the issue
2. Explain why the error is occurring
3. Provide a solution with explanation
4. Suggest best practices to avoid similar issues
```

### Expected Output
The AI will explain that the function tries to access the length property before checking if arr exists, and provide a solution using proper null/undefined checking.

## Tips

- Include the complete error message and stack trace
- Provide enough code context (not just the error line)
- Describe what you've already tried to avoid duplicate suggestions
- Mention any recent changes that might have caused the issue
- Include relevant configuration files if applicable

## Related Prompts

- code-review.md
- error-analysis.md
- refactoring-assistant.md

## Tags

`debugging` `error-handling` `troubleshooting` `problem-solving`

---
**Created**: November 2025  
**Last Updated**: November 2025
