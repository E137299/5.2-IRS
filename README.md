# 5.2 IRS

## Java Documentation
[Control Flow](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/flow.html)

## Java Tutorial
[Control Flow](https://runestone.academy/ns/books/published/apcsareview/Conditionals/toctree.html)

## Background:
Federal income tax rates can be calculated using tax rate schedules. The following are tax rates for
two out of the four categories used by the IRS in 2001:

Schedule X - Single

If your taxable income is:
| **Minimum Income**   | **Maximum Income** | **Tax Rate**            | **Of the Amount Over** |
|------------|------------------|----------------------------|------------------------|
| $0         | $27,050           | 15%                        | $0                     |
| $27,050    | $65,550           | $4,057.50 + 27.5%          | $27,050                |
| $65,550    | $136,750          | $14,645.00 + 30.5%         | $65,550                |
| $136,750   | $297,350          | $36,361.00 + 35.5%         | $136,750               |
| $297,350   | --------          | $93,374.00 + 39.1%         | $297,350               |





Schedule Y-1 - Married filing jointly
    If your taxable income is:
| **Minimum Income**   | **Maximum Income** | **Tax Rate**            | **Of the Amount Over** |
|------------|------------------|----------------------------|------------------------|
| $0         | $45,200           | 15%                        | $0                     |
| $45,200    | $109,250          | $6,780.00 + 27.5%          | $45,200                |
| $109,250   | $166,500          | $24,393.75 + 30.5%         | $109,250               |
| $166,500   | $297,350          | $41,855.00 + 35.5%         | $166,500               |
| $297,350   | --------          | $88,306.00 + 39.1%         | $297,350               |

To test your understanding, follow this example of a single person with taxable income of
    $68,000:
    
- Tax is $14,645.00 + 0.305*(68000-65550) = $14,645.00 + $747.25 = $15,392.25

## Assignment:
1. One of the biggest mistakes that beginning programmers tend to make is to attempt solving
the problem within their code before they really understand how to work the problem. Use the
following values and solve each of them before you begin to write your program out.
    1. $50,000 Married __________
    2. $25,000 Single __________
    3. $300,000 Married __________
    4. $170,000 Single __________
    5. $30,000 Married __________
    6. $500,000 Single __________
    7. $170,000 Married __________
    8. $45,000 Single __________
    9. $130,000 Married __________
    10. $120,000 Single __________

2. Write a class that:
    - Prompts the user for the following information:
        - Filing status: Single or Married (entered as 1 for Single and 2 for Married)
        Taxable income
    - Calculates and prints:
        - Filing status
        - Taxable income
        - Federal tax
3. Example run:
    - Enter marital status (1=single, 2=married): 1
    - Enter taxable income: $ 35125
    - Your Federal tax = $ 6,278.13
4. Use these values for your run output:
    - Single, $15,500
    - Single, $100,000
    - Single, $ 480,000
    - Married, $50,000
    - Married, $125,000
    - Married, $ 400,000