# What Google Learned From Its Quest to Build the Perfect Team :
its found that its better to work as teams, you will have to do that at work,

Studies show that groups tend to innovate faster, see mistakes more quickly, and find better solutions to problems. Studies also show that people working in teams tend to achieve better results and report higher job satisfaction.

Five years ago, Google — one of the most public proselytizers of how studying workers can transform productivity — became focused on building the perfect team. In the last decade, the tech giant has spent untold millions of dollars measuring nearly every aspect of its employees’ lives. Google’s People Operations department has scrutinized everything from how frequently particular people eat together (the most productive employees tend to build larger networks by rotating dining companions) to which traits the best managers share (unsurprisingly, good communication and avoiding micromanaging is critical; more shocking, this was news to many Google managers).

In 2012, the company embarked on an initiative — code-named Project Aristotle — to study hundreds of Google’s teams and figure out why some stumbled while others soared. Dubey, a leader of the project, gathered some of the company’s best statisticians, organizational psychologists, sociologists and engineers. He also needed researchers. Rozovsky, by then, had decided that what she wanted to do with her life was study people’s habits and tendencies. After graduating from Yale, she was hired by Google and was soon assigned to Project Aristotle.


# CSS Transforms:

**2D Rotate**
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. Later we will discuss how you can change this default point of rotation.

**2D Scale**
Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.


**2D Skew**
The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both


you can also make a cube !

# CSS Transitions & Animations:


**Transitions**
an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.



Transition Timing
The transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration. A few of the more popular keyword values for the transition-timing-function property include linear, ease-in, ease-out, and ease-in-out.

Animations Keyframes
To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated

Transition Delay
On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property. The delay sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing. As with all other transition properties, to delay numerous transitions, each delay can be declared as comma separated values.


# 8 simple CSS3 transitions that will wow your users:
 I chose my favorate four :
1. Fade in


```.fade```
```{```
     ```   opacity:0.5;```
```}```
```.fade:hover```
```{```
      ```  opacity:1;```
```}```


2. Change color


```.color:hover```
```{```
       ``` background:#53a7ea;```
```}```

3. Grow & Shrink

```.grow:hover```
```{```
     ```   -webkit-transform: scale(1.3);```
      ```  -ms-transform: scale(1.3);```
      ```  transform: scale(1.3);```
```}```

shrink :
```.shrink:hover```
```{```
     ```   -webkit-transform: scale(0.8);```
       ``` -ms-transform: scale(0.8);```
      ```  transform: scale(0.8);```
```}```


4. Rotate elements


```.rotate:hover```
```{```
    ```    -webkit-transform: rotateZ(-30deg);```
     ```   -ms-transform: rotateZ(-30deg);```
     ```   transform: rotateZ(-30deg);```
```}```






