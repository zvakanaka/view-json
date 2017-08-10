# view json
[demo](https://zvakanaka.github.io/view-json)

## Usage
### Default
JSON within the element is prettyfied and colorized:
```html
<view-json>
  { "jsonStuff": "is great stuff" }
</view-json>
```
## no-parse
```html
<view-json no-parse>
  Put whatever in here, but you lose color
</view-json>
```
| Attribute | Behavior |
| :------------- | :------------- |
| inline | Looks `like this` |
| no-parse | Don't parse as JSON |
| no-scroll | Don't show scrollbar (ugly sometimes) |
