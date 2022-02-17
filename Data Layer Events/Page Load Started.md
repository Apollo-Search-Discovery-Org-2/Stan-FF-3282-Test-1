# Page Load Started

### 

## Javascript Code
```js
window.appEventData000 = window.appEventData000 || [];
appEventData000.push({
  "event": "Page Load Started",
    "page": {
        "breadcrumbs": "<breadcrumbs>",
        "pageName": "<pageName>",
        "platform": "<platform>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|breadcrumbs|string|A delimited list of hierarchical sections that describe the current page's location within the navigation of the site.|Home&gt;Women&gt;Tops&gt;Sweaters, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Checkout &gt; Order Thank You|||||||
|pageName|string|Describes the page and its content specifically. |product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|platform|string|The technology platform version of the site that the user is experiencing.||||||||




