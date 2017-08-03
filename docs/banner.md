# Banner component

## Preview
![](img/banner_component.png)

## Properties
|Name|Type|Description|Sample|
|:----:|:----:|-----------|------|
|`layout`|JSON object| Bunch of Yoga properties| `{"width":"100%","aspect_ratio":2}` |
|`background`|String|Backround image url|`"https://example.com/abc.png"`|
|`category`|String|The category|`"NEW FILM"`|
|`category_color`|Color|Background color of category text|`#E9414C`|
|`title`|String|The title|`"Le Détour"`|
|`subtitle`|String|The title|`"Un film de Michel Goudry"`|

## Events
Banner component events inherit from `Component` base, plus with:

|Name|Description|
|:----:|-----------|
|`on_play_click`|Trigger when User click on play icon|