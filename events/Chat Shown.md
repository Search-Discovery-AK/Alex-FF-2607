# Chat Shown

### 

## Javascript Code
```js
window.appEventData2607 = window.appEventData2607 || [];
appEventData2607.push({
  "event": "Chat Shown",
    "chat": {
        "isProactive": "<isProactive>",
        "isReactive": "<isReactive>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|isProactive|boolean|Indicates whether a chat was offered proactively \(i.e. based on a behavioral rule or algorithm\)|true, false|||||||
|isReactive|boolean|Indicates whether a chat was offered in response to a user request \(i.e. user clicked the chat button\)|true, false|||||||
