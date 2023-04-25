# Ada-Carpet-Emporium-Challenege
A quote calculator for a carpet store
Ada's Flooring Superstore aims to run the best full-service flooring shop in the neighborhood. Ada boasts a range of elegant flooring materials and additional services and promotional discounts... Ada will NOT be undersold! With your help, Ada’s Flooring Superstore will have the speediest quote calculator in the industry.

- A quote is for only one room and one type of carpet. The options are berber, texture, or pattern. The respective prices per square foot are listed below.
- A quote has or more options. The options are 10 year warranty, delivery, installation, and stain guard. Their respective prices, which are a flat rate, i.e. not dependent on square footage, are listed below.
- Ada's Flooring is running a special on free installation for customers with the discount code "ADAROCKS". So, if a customer has a coupon code, don't include the installation cost in the quote total.
- The function called `carpet_quote_estimator` accepts four parameters:
  - `room`, a list of numbers representing the room's length and width in feet
  - `carpet_type`, a string representing the type of carpeting
  - `options`, a list of strings, representing 0 or more options 
  - `promo_code`, a string representing the discount code
- The function must print the price of the order in dollars (i.e., with two decimal places). Refer to the example output for the specific formatting.

### Carpet Type
|Name|Price ($) per square foot|
|----|---------|
| berber | 5.09 |
| texture | 3.69 |
| pattern | 2.89 |


### Options
|Name|Price ($)|
|----|---------|
| 10yr warranty | 100.00 |
| delivery | 35.00 |
| installation | 75.00 |
| stain guard | 30.00 |
