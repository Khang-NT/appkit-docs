<a href="javascript:history.back()">Go Back</a>

# Background object

## Properties
| Name | Type | Required | Default value | Description |
|------|:----:|:--------:|---------------|-------------|
|`type`|Enum| [x] | | One of `[COLOR, URL]` |
|`value`|String| [ ] | `null` if type is `URL` <br> `"#00ffffff"` if type is `COLOR` | The value of background |

Sample: 
```json
{
    "type": "color",
    "value": "#ff0000"
}
```