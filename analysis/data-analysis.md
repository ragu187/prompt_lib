# Data Analysis Assistant

## Category
Analysis

## Description
Analyze datasets, identify patterns, generate insights, and provide data-driven recommendations.

## Prompt

```
Please analyze the following data:

**Data:**
[DATA_OR_DESCRIPTION]

**Analysis Goals:**
[WHAT_YOU_WANT_TO_LEARN]

**Specific Questions:**
1. [QUESTION_1]
2. [QUESTION_2]
3. [QUESTION_3]

Please provide:
1. **Summary Statistics**: Key metrics and overview
2. **Patterns & Trends**: What patterns emerge from the data
3. **Insights**: Important findings and their implications
4. **Recommendations**: Actionable suggestions based on the analysis
5. **Visualizations**: Suggestions for charts/graphs to visualize the data

**Context:** [ADDITIONAL_CONTEXT]
```

## Variables

- `[DATA_OR_DESCRIPTION]`: The actual data or description of the dataset
- `[WHAT_YOU_WANT_TO_LEARN]`: Overall goals of the analysis
- `[QUESTION_1/2/3]`: Specific questions you need answered
- `[ADDITIONAL_CONTEXT]`: Business context or domain information

## Example Usage

### Input
```
Please analyze the following data:

**Data:**
Monthly sales data for Q3 2024:
- July: $45,000 (150 orders)
- August: $52,000 (180 orders)
- September: $38,000 (130 orders)

**Analysis Goals:**
Understand sales trends and identify factors affecting performance

**Specific Questions:**
1. What is the trend in sales and orders?
2. Why might September have lower sales?
3. What should we focus on for Q4?

Please provide:
1. **Summary Statistics**: Key metrics and overview
2. **Patterns & Trends**: What patterns emerge from the data
3. **Insights**: Important findings and their implications
4. **Recommendations**: Actionable suggestions based on the analysis
5. **Visualizations**: Suggestions for charts/graphs to visualize the data

**Context:** E-commerce business selling home decor
```

### Expected Output
The AI will provide statistical analysis, identify the peak in August and dip in September, and suggest reasons and actions.

## Tips

- Provide as much context as possible about the data source
- Be specific about what insights you're looking for
- Include relevant domain knowledge or constraints
- Specify the format you prefer for the analysis
- Can be used for various data types (sales, user behavior, surveys, etc.)

## Related Prompts

- research-synthesizer.md
- problem-solver.md
- decision-framework.md

## Tags

`data-analysis` `statistics` `insights` `trends` `metrics`

---
**Created**: November 2025  
**Last Updated**: November 2025
