# Reading: Class 14a

### CSS Transforms

CSS3 can use the *transform* property as an alternative way to size, position, and change elements. Transform can work in both two and three dimensions. Transform uses vendor prefixes based on the browser used.

2d transforms can rotate by x-and-y coordinates. An example would be 'transform: rotate(20deg)'. You can also scale up/down with 2d transform. Another property, skew, can distort shapes rendered on the page. A cool feature of transform is that these features can combined!

Transform origin allows you to set the alignment of the element on the page. Perspective allows you to simulate a 3d "vanishing point" for objects. There are numerous other properties that can be adjusted.

*Transition* property allows you to animate these elements by timing state-changes on your rendered page. Like Transforms, they have vendor prefixes, but an important point to note is that NOT all properties can be transitioned. The duration and delay properties determine most of how the transition moves in time. This property, like transform, is deep and powerful.