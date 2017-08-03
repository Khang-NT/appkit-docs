# Image component

## Properties

| Name | Type | Required | Description |  
|------|:----:|:--------:|-------------|
|`layout`| [Layout](../common/layout.md) | [x] | Value to determine the bound of this component |  
|`background`| [Background](../common/background.md)| [ ] | Background of this component |  
|`source`| String | [ ] | `URL` for the Image |  
|`scale_type`| Enum | [ ] | `[FIT_XY, FIT_CENTER, CENTER_CROP]`|

## Events

| Event | Params | Description |
|-------|--------|-------------|
|`on_click`|  | When user click on component |


## Default property values
```json
{
    "layout": {
        "width": "50pt",
        "height": "50pt"
    },
    "scale_type": "CENTER_CROP"
}
```
