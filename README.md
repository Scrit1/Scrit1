![svgviewer-output (11)](https://github.com/user-attachments/assets/a9d0bd71-093d-4c8d-a3a5-07e047115721)╭───────────────────────────────────────╮ 

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


# My SVG Example

This is an example of an SVG that showcases a hover effect. 

```html
<svg width="500" height="300" style="border:1px red solid" xmlns="http://www.w3.org/2000/svg">
    <style>
        .node {
            border: 1px solid black;
            border-radius: 10px;
        }
        .node:hover {
            background-color:red;
        }
    </style>
    <foreignObject class="node" x="0" y="0" width="100" height="100">
        <body xmlns="http://www.w3.org/1999/xhtml">
            <p>Hi! I'm a developer</p>  
        </body>
    </foreignObject>
</svg>
