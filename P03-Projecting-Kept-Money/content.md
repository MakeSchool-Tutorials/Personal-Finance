---
title: "Projecting Kept Money"
slug: projecting-kept-money
---

# Projecting “kept money”

Now, let’s start using these inputs to calculate how much money we keep from our paycheck.

All companies and individuals face a question: how should I make sense and structure my thinking around finances? Should I list expenses first and add income? Or should I list income and then deduct costs.

The answer can be found by drawing out how money literally flows to us. Like in programming, let’s draw it how money actually flows in real life:

```
Kept money = [Get check from employer] - [employer withholds taxes] - [pay ISA] - [put some money in savings] - [personal expenses]
```

For this reason we start with income and reduce that income total by costs.

# Calculate Retained Income

To format this function effectively, financial modelists often write “less” in descriptions of line items to clearly note when an item is deducting from the original income.

>[action]
> Let’s calculate how much of your income you retain per **month** given ISA, taxes, savings, intended saving ratio.
>
> **Reminder:** To keep up with spreadsheet best practices, like in OOP, write the formulas ONLY by referencing the variables in the input boxes. Again, by pointing back to the inputs, we keep our spreadsheet modular and our data clean of duplication errors.
>
> 1. Start your calculation by creating a month column to the right of your input box. Put “Month 1” in the top cell of the column G. Standard finance practices puts time increments (months or years) as columns and different line items (rent, salary, etc) as rows.
> 1. Write functions in the yellow cells for your Month 1 income. Note, ALWAYS reference the input box instead of writing inputs from scratch.
> 1. **SKIP** filling in the “Interest,” “Savings” and “Total accumulated savings” boxes. We’ll cover this later in the tutorial … there’s a bit more nuance since these cells must reference previous months.

If modeled correctly, and your “inputs” are as listed above, you should have a **“Kept income” total of $6,344 for Month 1.**
