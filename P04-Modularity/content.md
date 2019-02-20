---
title: "Modularity"
slug: modularity
---

In programming, clean code is made up of functions that achieve a single objective, rather than one complex function that strings together many many operations. By separating out the functions, we reduce the possibility of errors and our code is easier to read.

In financial models, we separate out individual line items: categories of income/expenses such as salary, contract work … groceries, streaming services, commute, etc. Each of the rows below are a **line item**.

# The Bottom Line

Separating out line items achieves a similar effect as making concise functions. It reduces our  chance of errors and allows one to follow which functions tie to which cells.

The granularity also creates another benefit: we can see how individual items affect our **bottom line** - a financial term referencing the leftover profit after all expenses are deducted. The **bottom line item** - also referenced as **net** meaning what is left over - is typically profit, hence the term “bottom line.”

# Total Income Expense

Combining line items into different buckets is also useful. You can create a **total expense** or **total income** line item that that sums up all the nested line items. This allows us to get a big picture …

>[action]
> Add the following sum line item to the sheet
>
>* Insert new line item `Total income expense` be replacing the "x" in column F, have it equal the sum of that month’s income and tax rate.
