# Contributing to Prompt Library

Thank you for contributing to this prompt library! This guide will help you add high-quality prompts.

## 📋 Before You Start

- Browse existing prompts to avoid duplicates
- Check if your prompt fits an existing category
- Consider if it could be a variation of an existing prompt

## 🎯 What Makes a Good Prompt?

A good prompt should be:

1. **Clear**: Easy to understand and use
2. **Structured**: Follows a consistent format
3. **Flexible**: Includes variables for customization
4. **Practical**: Solves a real problem or need
5. **Documented**: Includes examples and tips

## 📝 Adding a New Prompt

### Step 1: Choose a Category

Select the most appropriate category for your prompt:
- `coding/` - Programming and development
- `writing/` - Content creation and writing
- `analysis/` - Data analysis and research
- `creative/` - Brainstorming and creativity
- `productivity/` - Planning and organization
- `learning/` - Education and studying

If none fit, consider creating a new category.

### Step 2: Use the Template

Copy the template from `templates/prompt-template.md` and fill in all sections:

```bash
cp templates/prompt-template.md [category]/[prompt-name].md
```

### Step 3: Fill Out the Template

Required sections:
- **Title**: Clear, descriptive name
- **Category**: Primary category
- **Description**: One-sentence summary
- **Prompt**: The actual prompt text with variables
- **Variables**: Explanation of customizable parts
- **Example Usage**: At least one complete example
- **Tips**: Best practices (minimum 3)
- **Tags**: Relevant tags for searching

### Step 4: Add Examples

Include at least one complete example showing:
- Input: The prompt filled in with actual values
- Expected Output: What kind of response to expect

### Step 5: Update the Index

Add your prompt to `INDEX.md`:
1. Add it under the appropriate category
2. Include the title, link, and description
3. List the tags
4. Update the total prompt count

## ✅ Quality Checklist

Before submitting, ensure your prompt:

- [ ] Follows the template structure
- [ ] Has a clear, descriptive title
- [ ] Includes all required sections
- [ ] Has at least one complete example
- [ ] Uses clear variable names in [BRACKETS]
- [ ] Includes practical usage tips
- [ ] Has relevant tags for discoverability
- [ ] Is added to INDEX.md
- [ ] Uses proper markdown formatting
- [ ] Has been tested with an AI assistant

## 💡 Tips for Writing Prompts

### Be Specific
```
❌ "Help me with my code"
✅ "Review this Python function for performance issues and suggest optimizations"
```

### Use Variables
```
❌ "Explain quantum computing"
✅ "Explain [CONCEPT] at a [LEVEL] level with examples from [DOMAIN]"
```

### Include Context
Good prompts provide:
- Background information
- Constraints or requirements
- Desired outcome or format
- Relevant details

### Structure for Clarity
Use sections, bullet points, and formatting to make prompts easy to follow.

## 🏷️ Tag Guidelines

Choose 3-5 relevant tags:
- Use existing tags when possible (check INDEX.md)
- Use lowercase and hyphens
- Be specific but not overly narrow
- Include the primary category

Common tags:
- Technical: `debugging`, `code-review`, `documentation`
- Writing: `content-creation`, `editing`, `seo`
- Process: `planning`, `analysis`, `brainstorming`
- Domain: `productivity`, `learning`, `creativity`

## 📁 File Naming

Use descriptive, kebab-case names:
- ✅ `code-review.md`
- ✅ `meeting-agenda.md`
- ✅ `data-analysis.md`
- ❌ `prompt1.md`
- ❌ `CodeReview.md`

## 🔄 Updating Existing Prompts

When updating a prompt:
1. Maintain the original structure
2. Update the "Last Updated" date
3. Add a note about significant changes
4. Test the updated prompt
5. Update examples if needed

## 🚫 What Not to Include

Avoid:
- Prompts that could produce harmful content
- Overly specific prompts for single use cases
- Duplicate prompts (combine similar ones instead)
- Prompts without clear value or purpose
- Personal or sensitive information in examples

## 🤝 Review Process

Self-review checklist:
1. Test the prompt with an AI assistant
2. Verify all links work
3. Check for typos and formatting
4. Ensure examples are clear and helpful
5. Confirm variables are well-explained

## 📮 Questions?

If you're unsure about:
- Which category to use
- How to structure your prompt
- Whether your prompt is a good fit

Feel free to open an issue for discussion!

---

## Example Contribution Flow

1. Create a new branch
2. Copy the template: `cp templates/prompt-template.md coding/my-new-prompt.md`
3. Fill in all sections
4. Test the prompt
5. Update INDEX.md
6. Commit with descriptive message: "Add [prompt name] for [use case]"
7. Create a pull request

---

**Thank you for helping build a better prompt library!** 🎉

Your contributions help everyone work more effectively with AI assistants.
