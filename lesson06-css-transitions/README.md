# Working with CSS Transitions
Animate CSS Properties from an original value to a new value over time.
- Initial change is instantaneous (< 16ms) **Immediate change** 
- CSS Transitions allows smooth animation of CSS Properties thus less jarring movements

**Explanation**
- `transition-property`: The property to be transitioned (in this case, the background property). Only properties specified here will be animated. All other properties will be change instantly. We can specify which css property to be transitioned e.g border, background, color

- `transition-duration`: How long the transition should last (1 seconds) ..
//default value is 0

- `transition-timing-function`: How fast the transition happens over time (ease) 

**Transition Shorthand** <br/>
The transition property is a shorthand property used to represent up to four transition-related longhand properties:

`transition: [transition-property] [transition-duration] [transition-timing-function] [transition-delay];`

## Reference
- [List of Animatable Properties for Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties)
- [Understanding Transition Easing Effects](https://developer.mozilla.org/en-US/docs/Web/CSS/transition-timing-function)
- [Visual Reference of Easing Effects](https://easings.net/)
- [Cubic Bezier and Comparision Tool](https://cubic-bezier.com/)
- [CSS Easing Animation Tool](https://matthewlein.com/tools/ceaser)
- [More on Transitions & Transforms](https://www.joshwcomeau.com/animation/css-transitions/)