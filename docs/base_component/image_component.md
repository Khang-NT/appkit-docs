# Image component


## Properties
|Name|Type|Required|Description|
|----|:--:|:------:|-----------|
|`layout`| [Layout](../common/layout.md) | [x] | Value to determine the bound of this component |
|`background`| [Background](../common/background.md)|[ ]| Background of this component|
|`data`| String | [ ] | `URL` for the Image |
|`scale_type`| Enum | [x] | `[FIT_XY, FIT_CENTER, CENTER_CROP]`|

## Events

| Event | Type | Params | Description |
|--------|:------|:-----|
|`on click`|  |  | When user click on component|


## Default property values
```json
{
  "layout": {},
  "background": {},
  "source": "http://linktoimage.here",
  "scale_type": "CENTER_CROP"
}
```
