# Label Component

## Properties

| Name | Type | Required | Description |  
|------|:----:|:--------:|-------------|  
| *`layout` | [Layout](../common/layout.md) | **yes** | Value to determine the bound of this component |  
| `background` | [Background](../common/background.md) | no | Background of this component. |  
| `font` | [Font](../common/font.md) | no | The typography |  

## Events

| Name | Params | Description |
|------|--------|-------------|
| `on_click` | | Trigger when user click |

## Default property values

```json
{
    "layout": {
        "width": "auto",
        "height": "auto"
    },
    "font": {
        "color": "#000000",
        "size": "12pt"
    }
}
```