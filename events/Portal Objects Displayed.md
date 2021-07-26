# Portal Objects Displayed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData2607 = window.appEventData2607 || [];
appEventData2607.push({
  "event": "Portal Objects Displayed",
    "portalDisplayed": {
        "portalObject": [
            {
                "isDisplayed": "<isDisplayed>",
                "portalObjectId": "<portalObjectId>"
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|isDisplayed|boolean|Helper node used by AA Product String Builder to set product scoped events|true|||||||
|portalObjectId|string|Unique identifier of a portal object|My Accounts, Transactions, Messages, My Reports|||||||
