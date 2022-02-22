---
layout: article
title:  "Withcode"
hasCode: true
weight: 2
---
# WithCode

## code

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

## code end
