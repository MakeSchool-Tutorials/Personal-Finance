---
title: "Stretching Money Across Months"
slug: stretching-money-across-months
---

Now, let’s extend our formulas across 12 months to see how our monthly return on savings changes:

>[action]
>
> 1. Next to the column header “Month 1” (G2) add “Month 2” to the right column, then “Month 3” all the way to “Month 12.” Tip, if you highlight both Month 1 and Month 2 at the same time and drag the little blue box in the highlighted cells bottom right corner, Google sheets will automatically realize you are growing months by 1 and will populate the correct cell content!
> 1. Copy these formulas in column G2-G13 for “Month 1” all the way to Month 12. You should see many of the values stay the same but monthly return on savings and total accumulated savings should change.

Have a go at building that into your model. Keep in mind your formula should be

1. Referencing savings rate, savings percentage … and also your monthly income
1. You’ll have to reference the previous months savings in order to add your monthly savings to the total savings

## Tips

**Note:** you will need a new formula to apply to months 2-12 for monthly return on savings and total accumulated savings.

# Copying Formulas

Instead of re-writing your formula over and over, you can easily copy and paste formulas across rows, like we demonstrated in the challenges. To do this, hover over the cell whose formula you want to copy and notice the small blue box in the lower right-hand corner of  the cell. Drag that to the cells right or left of the row to copy the formula into other cells.

# My Formula Broke!

**WAIT MY FORMULA BROKE!** - You’ll notice that when you drag a *formula* one cell right, it also changes the referenced cells mentioned in the formula one cell right too.

But we want to fixate our formula on certain cells (i.e. always reference B4)! For that reason we need to “lock” our cells to ensure that we are always referencing the same cell in the sheet (i.e. tax rate) even as we move right.

Use the “$” sign in the formula to lock the row or column as you drag the formula. If you put the $ before the row of the cell (i.e. $A1) then when you drag the formula it will lock the X. If you put it before the number (i.e. A$1) it will lock the x as you drag it. And if you put the $ before and after the cell (i.e. $A$1) then it will lock that cell,

Using “$” allows us to lock and keep reference on our input cells while doing forecasts.


# Onward

We’ve now projected our incomes and savings across a year! Next, let’s incorporate expenses into our model.
