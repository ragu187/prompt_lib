# Problem Solver

## Category
Analysis

## Description
A structured approach to analyzing and solving complex problems using systematic thinking.

## Prompt

```
Help me solve the following problem:

**Problem:**
[PROBLEM_DESCRIPTION]

**Current Situation:**
[CURRENT_STATE]

**Desired Outcome:**
[DESIRED_STATE]

**Constraints:**
- [CONSTRAINT_1]
- [CONSTRAINT_2]
- [CONSTRAINT_3]

**Available Resources:**
[RESOURCES]

Please provide:
1. **Problem Analysis**: Break down the problem into components
2. **Root Cause**: Identify the underlying causes
3. **Solution Options**: Generate 3-5 potential solutions with pros/cons
4. **Recommended Approach**: Best solution with implementation steps
5. **Risk Assessment**: Potential risks and mitigation strategies
6. **Success Metrics**: How to measure if the solution works
```

## Variables

- `[PROBLEM_DESCRIPTION]`: Clear description of the problem
- `[CURRENT_STATE]`: Where you are now
- `[DESIRED_STATE]`: Where you want to be
- `[CONSTRAINT_1/2/3]`: Limitations or constraints
- `[RESOURCES]`: Available resources (time, budget, people, tools)

## Example Usage

### Input
```
Help me solve the following problem:

**Problem:**
Our website load time has increased from 2 seconds to 8 seconds over the past month, causing a 30% drop in conversions.

**Current Situation:**
- Average page load: 8 seconds
- Server response time: 3 seconds
- Large image files: 5MB average
- No caching implemented
- Traffic increased 50%

**Desired Outcome:**
Reduce page load time to under 2 seconds

**Constraints:**
- Budget: $5,000
- Timeline: 2 weeks
- Cannot change hosting provider

**Available Resources:**
- In-house developer (20 hours/week)
- CDN subscription available
- Image optimization tools

Please provide:
1. **Problem Analysis**: Break down the problem into components
2. **Root Cause**: Identify the underlying causes
3. **Solution Options**: Generate 3-5 potential solutions with pros/cons
4. **Recommended Approach**: Best solution with implementation steps
5. **Risk Assessment**: Potential risks and mitigation strategies
6. **Success Metrics**: How to measure if the solution works
```

### Expected Output
Systematic analysis identifying image size and lack of caching as main issues, multiple solution options, and a prioritized implementation plan.

## Tips

- Be specific about constraints and resources
- Include measurable goals in your desired outcome
- Provide context about what's been tried before
- Mention any technical or organizational constraints
- Specify timeline and urgency

## Related Prompts

- data-analysis.md
- decision-framework.md
- research-synthesizer.md

## Tags

`problem-solving` `analysis` `strategy` `decision-making` `troubleshooting`

---
**Created**: November 2025  
**Last Updated**: November 2025
