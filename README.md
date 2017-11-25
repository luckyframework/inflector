# LuckyInflector

This project is still new. Guides will be posted when things are more complete.

## Installation

Add this to your application's `shard.yml`:

```yaml
dependencies:
  lucky_inflector:
    github: luckyframework/lucky_inflector
```

## Usage

```crystal
require "lucky_inflector"

LuckyInflector::Inflector.pluralize("word") # "words"
LuckyInflector::Inflector.singularize("categories") # "category"
```

## Contributing

1. Fork it ( https://github.com/luckyframework/lucky_inflector/fork )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Testing

To run the tests:
* Run the tests with `crystal spec`

## Contributors

- [paulcsmith](https://github.com/paulcsmith) Paul Smith - creator, maintainer
- [actsasflinn](https://github.com/actsasflinn) Flinn Mueller - contributor

## Thanks & attributions

* Inflector is based on [Rails](https://github.com/rails/rails). Thank you to the Rails team!
