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


