# CSS

## Flexbox

* #container {  display: flex;} gives the container flex property, allowing items to be organized along the main axis and cross axis. Main axis is horizontal by default.

* #container {  display: flex;  flex-direction: column;} changes the orientation of the main axis so it runs vertically. Does NOT align items along the previous cross axis.

* #container {  display: flex;  flex-direction: row;  justify-content: COMMAND;} allows the content to be justified in various ways along the main axis:

1. flex-start
2. flex-end
3. center
4. space-between (equal space between objects, not at outside margins)
5. space-around (equal margins around all objects. Furthest sides are half as far)

* {  display: flex;  flex-direction: row;  align-items: COMMAND;} similar to justify content, this acts on the cross axis:

1. flex-start
2. flex-end
3. center
4. stretch (items take up the entirety of the cross axis. Height must be set to auto)
5. baseline (bottom of paragraph tags are aligned. If no p tags, then bottom of containers)

* .square#one {  align-self: center;} allows us to only target a specific child within the parent container.