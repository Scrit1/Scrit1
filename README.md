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

![svgviewer-output (7)](https://github.com/user-attachments/assets/7e34b885-3423-40eb-ad16-612deda72132)
<svg width="500" height="300" style="border:1px solid red;" xmlns="http://www.w3.org/2000/svg">
    <style>
        /* Animation for the foreignObject */
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-20px);
            }
            60% {
                transform: translateY(-10px);
            }
        }

        .node {
            animation: bounce 2s infinite;
        }

        /* Transition effect on hover */
        .node:hover {
            background-color: lightblue;
            transition: background-color 0.5s ease-in-out;
        }
    </style>
    <foreignObject class="node" x="46" y="22" width="100" height="100">
        <body xmlns="http://www.w3.org/1999/xhtml">
            <p style="margin: 0;">Hi! I'm a developer</p>  
        </body>
    </foreignObject>
</svg>
