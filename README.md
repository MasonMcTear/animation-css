**CSS Transform**
- Changes the shape and position of the affected content without disrupting the normal document flow by modifying the coordinate space.

---

**CSS Transition**
- Allows changes in a property to take place over time.

---

**CSS Keyframe Animation**
- Defines an animation sequence of states within the @keyframes rule.

**Two Step CSS @keyframe Animation**
- Defining the animation keyframes in @keyframes rule.
- Assign the keyframes to an element.

**0% of "from" keyframe** is the start of the animation.

**100% or "to" keyframe** is the end of the animation.

---

**animation-delay**
- Specifies the amount of time to wait before beginning to perform the animation.

**animation-fill-mode**
- Lets you control what happens during delays before an animation starts actively playing, and/or what happens after an animation's duration has ended.

---

**animation-direction**
- Lets you control what order our keyframes are executed in.
- Values: normal, reverse, alternate and alternate-reverse.

---

**Easing**
- Easing is what describes the speed changes of your animation over the course of its duration.

**Three Options for animation-timing-function**
- Easing keywords
- The steps() function
- Custom cubic-bezier curves

**Keyword Easing Options**
- ease
- ease-in-out
- ease-in
- ease-out
- linear

[cubic-bezier](https://cubic-bezier.com/#.17,.67,.83,.67) <br />
[easings](https://easings.net/)

---

**steps()**
- Plays an animation back in a defined number of steps, pausing briefly at each, instead of smoothly interpolating between keyframes states.

---

**animation-play-state**
- Controls whether an animation is playing or paused.

---

**transform-origin**
- The point around which a transformation is applied.

---

**Tip**
- Look for distinct and complete shapes for the objects you want to animate.
- Name the layers and/or paths you'll be animating so it's easier to find them later.