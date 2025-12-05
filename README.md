╭───────────────────────────────────────╮ 

│ Hello! And welcome to my Github page! │ 

╰───────────────────────────────────────╯
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```

# New Document

<svg width="100" height="100">
    <circle cx="50" cy="50" r="40">
        <animate attributeName="fill" values="blue;red;green;blue" dur="3s" repeatCount="indefinite" />
    </circle>
</svg>
