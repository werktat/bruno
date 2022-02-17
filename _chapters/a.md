---
layout: 339
title:  "A md"
weight: 20
---

# A

aaaaaa

## AA

aaaaa


# TEST

Paragraphs are separated by a blank line.

2nd paragraph. *Italic*, **bold**, and monospace. Itemized lists
look like:

  * this one
  * that one
  * the other one

Note that --- not considering the asterisk --- the actual text
content starts at 4-columns in.

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

Use 3 dashes for an em-dash. Use 2 dashes for ranges (ex., "it's all
in chapters 12--14"). Three dots ... will be converted to an ellipsis.
Unicode is supported. ☺

```
class Products {
    public double Price { get; set; } 
    public double Discount { get; set; } 
    public string CalcDiscount(CheckBox checkNonProfit, CheckBox bulkPurchase) {
      double discountedPrice = Price; 
      if (checkNonprofit.IsChecked == true) 
        discountedPrice = discountedPrice  * 0.9;
      if (bulkPurchase.IsChecked == true) 
        discountedPrice = discountedPrice * 0.9;
      return discountedPrice.ToString(); 
    }
}
```
