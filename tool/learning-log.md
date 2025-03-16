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


<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
