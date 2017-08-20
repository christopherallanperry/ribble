# Notes on this repo

Repo URL: [https://github.com/christopherallanperry/ribble](https://github.com/christopherallanperry/ribble)

## Purpose

Code the body of a sample page for Ribble Cycles (or sections of page depending on your available time) using methods and technologies you deem appropriate.

## To view

Download the repo onto your local machine and then open up the `index.html` file in your browser.

## Todo

1. Build out sub-menu structure - ran out of time.
2. Refactor for RWD purposes (`@media` queries etc.) - ran out of time.
3. Review accessibility features.

## Issues

1. Needed to use `!important` on 'Sale' menu item to override text colour
2. The R872 button isn't clearing the example price table above it - likely due to this table being floated out of the document flow.
3. The `view-more` example package button isn't currently operable - most likely due to the example package images sitting at a higher index level than the button is.

## Challenges

1. Getting the images used for the example packages placed was the hardest part of what's currently presented here. Initially, a `clip-path` was used, but I was unable to find a workable method of getting the parent `<div>` to fit to the visible part of the image. The work shown here is the result of modifying the supplied images with Photoshop and Illustrator.
2. Making the valley-light background image look correct had me scratching my head for a while. That was eventually solved when I found the trick demonstrated at Ref #2 below.
3. I did make an attempt at the sub-menu structure, but given time-constraints, it became obvious that I'd be unable to comete it to any degree of satisfaction. I removed the markup I had created, to leave the remaining work looking presentable. I'm assuming that this would normally be built out through a CMS, rather than created manually.

## Feedback

1. Looking at the 'FAQ' section, it is likely that the blocks of centred text would cause a potential accessibility issue for those with dyslexia.
2. Similarly, the line length on the earlier items describing the Cycle Scheme, are likely longer than would be considered ideal.
3. From a personal perspective, I found the grey on black text lacking contrast, though apparently the combination checks out OK on the [WebAIM Contrast Checker](http://webaim.org/resources/contrastchecker/).

## Resources/References Used

1. [Keeping it simple: coding a carousel](https://christianheilmann.com/2015/04/08/keeping-it-simple-coding-a-carousel/) by [Christian Heilmann](https://christianheilmann.com/)
2. [How to Change a CSS Background Image's Opacity](https://codepen.io/ncerminara/pen/eFzJI) a Codepen by [Nicholas Cerminara](https://codepen.io/ncerminara/)
3. [Inclusive Design Patterns](https://shop.smashingmagazine.com/products/inclusive-design-patterns) by [Heydon Pickering](https://twitter.com/heydonworks)
4. [MDN Web Docs](https://developer.mozilla.org/en-US/) by [Moz://a Foundation](https://www.mozilla.org/)
5. [Manage large CSS projects with ITCSS](http://www.creativebloq.com/web-design/manage-large-css-projects-itcss-101517528) by [Harry Roberts](https://twitter.com/csswizardry)
6. [Fontawesome](http://fontawesome.io/icons/) used for iconography
7. And last, but not least, reference was made to the current [Ribble Cycles website](https://www.ribblecycles.co.uk/) to establish relevant detail about the header/menu and footer sections.
