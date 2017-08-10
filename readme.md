# view json
[demo](https://zvakanaka.github.io/view-json)

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="view-json.html">
    <view-json>
      { "view json": "native v1 web component", "css variables": ["--background-color","--color","--string-color","--number-color","--boolean-color","--null-color","--key-color"], "attributes": ["inline","no-scroll","no-parse"], "dependencies": null,"lines of code":64 }
    </view-json>
  </template>
</custom-element-demo>
```
-->

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
