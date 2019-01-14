# Features

## Code Highlighting
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

## Built-in Variables

page.title = {{ page.title }}

## Custom variables

Can't figure out how to do it.

my_variable = {{ variables.my_variable }}

## Import Other Files (README.md)

----------
{% include "./README.md" %}
----------
