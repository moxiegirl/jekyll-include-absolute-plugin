# Jekyll include_absolute Tag

A Jekyll's liquid tag plugin to include a file from its path relative to Jekyll's source folder. Why? Because Jekyll's built-in `include` tag does not support including files outside of `_includes` folder.

Syntax: `{% include_absolute path %}`

## Installation

Copy `include_absolute.rb` into `/_plugins`

## Examples

js/common.js

```
{% include_absolute js/jquery.js %}
{% include_absolute js/bootstrap.js %}
```

css/common.css

```
{% include_absolute css/bootstrap.css %}
{% include_absolute css/ionicons.css %}
```

## License

MIT
