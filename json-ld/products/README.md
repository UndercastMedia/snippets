# Products

This is an example of how to mark up a product page using Jekyll so that Google can display rich snippets. 

If you're using [CloudCannon](http://cloudcannon.com/) add the following to your `_config.yml`.

```
product_number_types:
  - SKU
  - MPN
  - GTIN8
  - GTIN13
  - GTIN14

conditions:
  - New
  - Used
  - Refurbished

availabilities:
  - Discontinued
  - InStock
  - InStoreOnly
  - LimitedAvailability
  - OnlineOnly
  - OutOfStock
  - PreOrder
  - PreSale
  - SoldOut
```

Visit [Google's Documentation](https://developers.google.com/search/docs/data-types/products) for more guides and examples.