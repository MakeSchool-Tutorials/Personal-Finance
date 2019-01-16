---
title: "Input Box"
slug: input-box
---

Let’s orient ourselves on how to *think* about personal finance.

Building a personal financial model is very similar to programming. In coding we use object oriented programming to make our code modular so changes can ripple through the codebase.

Similarly, in our financial model, we can use an **input box** that includes all the variables we put into the model (such as salary, cost, tax rate, etc), and those inputs ripples through our projections and totals. By having an input box we keep our model clean.

# Creating an Input Box

Let’s start our personal financial model by creating an input box.

>[action]
> In the same spreadsheet you used for the initial challenges, click the `My Personal Finances` tab at the bottom of the sheet.
>
> Set up the input box with the variables listed below. (We’ll use the same variable inputs at the beginning of tutorial to ensure we are all synced and getting the right answers. During the second half of the tutorial you can alter your formulas to calculate your specific financial targets and needs.)
>
> * **Income** = $105,000 - the amount of money you will make from salary
> * **Income 2** - additional income streams such as contracting, driving uber, etc
> * **ISA %** = 25.0% - what is the percentage per year you owe for ISA?
> * **Income Savings Rate** = 10.0% - your decision on the % of your income you want to save
> * **Tax Rate** = 30% - … more on this below
> * **Charitable giving %** = 2.5% - what percentage of your income do you want to give after taxes
> * **Annual Return on Savings** = 5.0% - what is the return rate on your savings?


You’ll notice that a few different inputs are not a constant. They require a **function**.


# Functions

Instead of calculating this over and over again let’s create a function in this one cell - *B6* - that we will later reference in our financial model. In the “coding language” of Google Sheets the following functions help you do basic calculations:

```
=SUM(range [selected cell(s)]:[selected cell(s))
= [cell] - [cell]
= [cell] * [cell]
= [cell] - 5
```

See this [extensive list](https://support.google.com/docs/table/25273) of formulas and this list of top ten most commonly used functions

# Annual Inputs => Monthly Inputs

Believe it or not, just like programming, most calculations in finance are just basic arithmetic.

> [action]
> In your input box:
>
> * Write the inputs values listed above into your input box
> * Write formulas in C2 to C8 to translate annual inputs into monthly inputs
> * Format data: use [these tips](https://gsuite.google.com/learning-center/products/sheets/get-started/#!/section-2) to format your data with the correct units ($, %).

## Stretch Challenge

>[challenge]
> Write a function for progressive income tax into your spreadsheet. Here’s [a link](https://blog.taxact.com/how-tax-brackets-work/) explaining the real way that income taxes are calculated in the United States.
>
> **Hint:** write a formula for a progressive income tax using the tax table in the link below, VLOOKUP and SUMPRODUCT functions. Here’s [a tutorial](https://www.excel-university.com/income-tax-formula/) on how to do so.

# Onward

Now that we have our inputs, let’s use the content of the input box to calculate how much money we keep from our salary per month after paying ISA and taxes.
