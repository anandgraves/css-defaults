Inspired by "[Forget normalize or resets; lay your own css foundation](http://jaydenseric.com/blog/forget-normalize-or-resets-lay-your-own-css-foundation)".


## Demo
[Shows how all HTML elements are default rendered (work in progress)](http://codepen.io/anandgraves/pen/dNbmEj)


## Avoid faux-bold and faux-italic
Resetting elements like ```<strong>``` with ```font-weigh: normal``` has drawbacks.
A preferred approach is:  
[@font-face tip: define font-weight and font-style to keep your CSS simple](http://www.456bereastreet.com/archive/201012/font-face_tip_define_font-weight_and_font-style_to_keep_your_css_simple/)

If you want to deep dive more into the subject:  
[Setting Weights And Styles With The @font-face Declaration](https://www.smashingmagazine.com/2013/02/setting-weights-and-styles-at-font-face-declaration/)

## Todos

* Correct styles for input type search
* Testing if vertical-align: baseline is needed on the universal selector


## Licence

[MIT license](https://en.wikipedia.org/wiki/MIT_License).
