# Updated Hacker News `news.css`

Updated Hacker News `news.css` file to support dark mode using native features such as CSS Variables and `prefer-color-scheme` Media Query.

See the screenshots for how it looks like. You can override your own user agent's CSS to see it in action too.

## How is it done?

* Replaced all hardcoded colors to use CSS Variables
* Added a `:root` section to define all color and font variables
* Added a media query for `prefer-color-scheme` to update base variables to dark colors

It only relies on user agent's preferences. If someone doesn't like the dark mode, they can turn off the dark mode in their system, their browser or only for this website. 

### No toggles
Having to toggle to turn on/off the dark mode is anti-pattern. Specially for savy HN user that can figure out how to set thier color scheme preference.

## Getting `dang` to merge this 

[`dang`](https://news.ycombinator.com/user?id=dang) have [shown interest](https://news.ycombinator.com/item?id=23199062) in updating the `news.css` file to support dark mode a while ago. This is an attempt to get that change happen. 

I am writing an email to let them know about this effort. 

### Response to my email

> Thanks! I'll take a look!

> Our current thinking is still to add a facility to HN for people to upload their own CSS so they can adjust the look and feel how they want, not only for dark mode but for anything. However, it's nontrivial to make sure that security vulnerabilities aren't introduced that way. We'll get to it eventually!


## Colors 

Picking the colors is probably the hardest part of this work. I'm open to suggestions for improving the color palette in the dark mode. Please send your pull requests with screenshots. 

## HN discussions 

* https://news.ycombinator.com/item?id=30047702
