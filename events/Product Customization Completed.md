# Product Customization Completed

### 

## Javascript Code
```js
window.appEventData2607 = window.appEventData2607 || [];
appEventData2607.push({
  "event": "Product Customization Completed",
    "product": [
        {
            "productInfo": {
                "brand": "<brand>",
                "productID": "<productID>"
            }
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|brand|string|Describes the brand of a product or offering.|Ford, Chevrolet, Dodge, Levis, Columbia, Patagonia|||||||
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||
