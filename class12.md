# Reading Notes: Class 12

### Various Articles

Using interactive or dynamic data display for charts and graphs can make them much more interesting and effective. Chart.js is a plugin that can be used for animated charts. It's a set of .js files that is highly customizable. You can render bar charts, line graphs, pie charts.

Charts.js relies upon the HTML5 '< canvas >' element, which functions like img but without src and alt attributes. Charts can be styled, but default to 300px x 150px. Some browsers however do not support the canvas tag, so there is fallback content provided by the JS.

Canvas can also be used to render shapes on the page. It can render rectangles and paths and lines. Paths are the simplest -- all shapes rendered on the page are a combination of paths. More complex shapes can be rendered by using the pen on a grid, drawing unconnected paths. This same sort of workflow can be used to style image backgrounds, and surprisingly complex graphic content despite its seeming simplicity.

All paths can also be styled with CSS. A designer can adjust color, transparency, and other attributes. You can select different types of lines for styling too: dash, dot, width, etc.

Text can be rendered on the page with a draw or fill technique. Fill text is what most of us would think of when we picture text -- solid, one-color lettering. Stroke text is the outline of a letter, not filled in. Just like typical fonts can be styled with CSS, there are other properties that can be used to style stroke or fill text.