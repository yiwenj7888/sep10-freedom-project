# Tool Learning Log

## Tool: **AnimateCSS**

---

### 3/7/2025:
* I started using AnimateCSS today to implement some animations on a project I’m working on. I found the documentation on AnimateCSS super helpful, especially the section on how to apply different classes for various types of animations (like fade-ins and bounces).
* I also watched a YouTube tutorial called "How to Use AnimateCSS for Beginners" to get a better grasp of the basics. It showed how to easily add animations by simply adding classes like `animate__fadeIn` or `animate__bounce`.
* I experimented by applying animations to a button on my page. I added the animate__fadeIn class to my button and it worked perfectly, when the page loads, the button fades in.
* One challenge I faced was figuring out how to make the animation run only once on page load. I had to look into using `animate__animated` along with the specific animation class, which solved the problem.
* A-ha moment: I learned that you can chain multiple animations by adding more classes, for example: `animate__fadeIn` `animate__delay-1s` `animate__bounce`. This gave me more control over the timing of my animations.
* A question I still have: Is there a way to customize the duration or speed of the animations beyond just adding delay classes, or do I need to adjust this in the CSS itself?
* Next, I’m going to experiment with adding more complex animations to my webpage, like `animate__zoomIn` and `animate__slideInUp`, and see how I can combine them creatively. 


### 3/12/2025:
* Today, I dove deeper into Animate.css and experimented with more advanced features. I revisited the official Animate.css documentation and found it really helpful in explaining how to use animation delays, timing functions, and the different ways to control animations. I also found a great article called, "How to Create Advanced Animations with CSS" that explained how to use animation delays and timing functions in more detail. It was really helpful to see all the different options and combinations you can use to control animations.
* I tried adding an `animate__pulse` animation to an image on my webpage. At first, I couldn’t figure out how to make the animation run only once, so I had to revisit the documentation. I eventually discovered that I could use the class `animate__fadeOut` along with `animate__delay-2s` to control the sequence of animations better.
* My biggest challenge today was figuring out how to make animations trigger only when the element enters the viewport. I had to dig into Google and found a couple of resources on combining Animate.css with the IntersectionObserver API. After some trial and error, I managed to make the animations play when the user scrolls to that part of the page.
* A-ha moment: I learned that using `animate__infinite` causes the animation to loop, but combining it with `animate__delay` can let me control the timing of when animations start or stop. This gave me much more flexibility in deciding when and how things animate.
* A question I still have: How can I optimize animations for mobile devices? I want to make sure that animations run smoothly without affecting performance, especially for users on older devices.
* Next, I’m going to try combining more complex animations, like `animate__zoomIn` and `animate__rotateIn`, to create more dynamic effects. I’m also considering adding media queries to fine-tune the animations for smaller screens.


### 3/18/2025
* Today, I continued experimenting with Animate.css, specifically focusing on adding more complex animations to my webpage. I revisited both the official Animate.css documentation and the tutorial I watched last week. It was great to refresh my understanding of the different animation options and how to combine them for more dynamic effects.
* I tried implementing `animate__zoomIn` and `animate__rotateIn` together for a section of my homepage. I was pleasantly surprised by how well they worked together. The zoomIn animation made the section grow larger while rotateIn made it spin slightly. I added a slight delay with `animate__delay-0.5s` to sequence the animations, making the effect feel more natural.
* One challenge I faced was ensuring the animations didn’t clash with each other or feel too overwhelming. I had to experiment with timing and delays to get everything to sync properly without it feeling too busy or distracting.
* A-ha moment: I discovered that using `animate__delay` in combination with `animate__once` allowed me to control the sequence of animations without them repeating. This was exactly what I needed to ensure that some elements only animated once on page load, while others triggered based on user interaction.
* A question I still have: How can I integrate more advanced interaction-based animations (like triggering animations when a user clicks or hovers over an element)? Is there a simple way to use Animate.css with trigger events without writing custom JavaScript?
* Next, I plan to integrate more interactivity into my project, possibly by using user actions to initiate specific animations. I also want to explore how to combine Animate.css with other libraries like ScrollMagic for more complex scroll-based animations.


### 4/2/2025
* Today, I spent some time diving into the Animate.css documentation to understand the animation-fill-modeproperty, which I had heard about but never fully explored. This property controls how the styles applied by an animation are maintained before and after it runs. It was interesting to learn that there are four possible values: `none`, `forwards`, `backwards`, and both. This property allows you to control whether the element stays in its initial or final state after the animation ends.
* I tried experimenting with `animation-fill-mode: forwards;` on one of my elements, and it worked perfectly! The element maintained the final state of the animation, which was exactly what I needed for a button that should stay enlarged after a hover animation.
The documentation mentioned that when using `animation-fill-mode: forwards;`, the element retains the styles of the animation’s last keyframe after the animation finishes. This was really helpful since I often found that elements would revert back to their initial state after an animation, and now I know how to fix that.
* To deepen my understanding, I decided to explore the MDN Web Docs on the `animation-fill-mode` property. I found an article titled "animation-fill-mode - CSS: Cascading Style Sheets | MDN" that explains in more detail how this property works in various scenarios, including how it interacts with other animation properties. It also provided useful examples on how to use it in combination with different timing functions and keyframes.
* A-ha moment: I realized that using `animation-fill-mode: backwards;` can be just as useful when you want the element to take on the style defined in the first keyframe before the animation starts. This was a great discovery because it gave me more control over how my animations behave at the start of an interaction.
* A question I still have: Is it possible to combine `animation-fill-mode` with custom JavaScript events to dynamically change the behavior of an animation depending on user interactions? I want to make sure the animations feel as interactive and smooth as possible.
* Next, I’m going to continue experimenting with `animation-fill-mode` on different elements, especially in combination with more complex animations. I also want to learn how to trigger these animations based on user input like clicks or scrolls, while ensuring that the final state of the animation is preserved without needing extra custom code.



<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
