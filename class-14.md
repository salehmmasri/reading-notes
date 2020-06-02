
### Transforms :
#### Transform Syntax :

- transform type :
    - div { Webkit-transform scale(1.5); -moz-transform scale(1.5); -o-transform: scale(1.5); transform: scale(1.5) }
    - 2D Transforms : Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.
    - f rotation is the center of the element, 50% 50%, both horizontally and vertically.

    - Ex: .box-1 { transform: rotate(20deg); } .box-2 { transform: rotate(-55deg); }

**2D Scale Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1 therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.**

**EX : .box-1 { transform: scale(.75); } .box-2 { transform: scale(1.25); }**

**The scaleX value will scale the width of an element while the scaleY value will scale the height of an element.**

- EX: .box-1 { transform: scaleX(.5); } .box-2 { transform: scaleY(1.15); } .box-3 { transform: scale(.5, 1.15); }

- 2D Translate -Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.

- EX : .box-1 { transform: translateX(-10px); } .box-2 { transform: translateY(25%); } .box-3 { transform: translate(-10px, 25%); }
2D Skew

- Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.

- EX : .box-1 { transform: skewX(5deg); } .box-2 { transform: skewY(-20deg); } .box-3 { transform: skew(5deg, -20deg); }

**To start, animations need a duration declared using the animation-duration property.A timing function and delay can be declared using the animation-timing-function and animation-delay properties respectively.Animation Iteration**
**To have an animation repeat itself numerous times the animation-iteration-count property may be used.Values for the animation-iteration-count property include either an integer or the infinite keyword. Animation Direction**

- declare the direction an animation completes using the animation-direction property.
- Values for the animation-direction property include normal, reverse, alternate, and alternate-reverse.

- Animation Play State
    - The animation-play-state property allows an animation to be played or paused using the running and paused keyword values respectively.
