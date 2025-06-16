# Entry 6

### Context

For my Freedom Project, I was assigned to create a website around the topic of Business. My goal was to show how technology has evolved in the business world, from past tools like mainframes to future concepts like emotion based data analytics. 

[You can view my project here.](https://yiwenj7888.github.io/sep10-freedom-project/)

I created this site by following an MVP (Minimum Viable Product) approach. First, I planned everything out, including what sections I would include, the context of business, a timeline of tech innovations, and future innovation predictions. I planned out wireframes to guide how the site would be laid out and made sure the design would work on both laptops and mobile devices using Wireframe.cc.

[My mobile wireframe.](https://wireframe.cc/10FPGG)

[My computer wireframe.](https://wireframe.cc/2RPzRp)

For the actual website, I used Bootstrap to help with responsiveness and layout. I used components like navbars, cards, rows, columns, and accordions. I also designed a custom color palette using soft gray backgrounds and purple tones to give the site a modern and professional feel.

---

### Challenges

One major challenge I faced was making the website fully responsive across different screen sizes. When I first built the layout, everything looked fine on my laptop, but when I tested it on a phone, some of the content didn’t align properly. For example, the cards in the timeline section would stack unevenly or the images would overflow outside their containers. At first, I wasn’t sure how to fix it, but then I remembered that Bootstrap has built-in grid classes for responsiveness. I used `row-cols-1 row-cols-md-2` to make sure my cards stacked vertically on small screens and displayed in two columns on medium to large screens. I also adjusted padding and margins using Bootstrap utility classes like `mt-3`, `mb-5`, and `p-2` to improve spacing.

Here's an example of what I used:

```java
<div class="row row-cols-1 row-cols-md-2 g-4">
```

#### Takeaways

After testing again on different screen sizes, the layout looked much better. This challenge taught me how important it is to constantly preview your site on multiple devices, not just the one you're coding on.

One major thing I learned during the MVP stage was the importance of organizing code. I used HTML comments like this:

```java
<!-- Present Technologies Section -->
```

This helped me find sections faster and kept me from getting overwhelmed with long blocks of code—especially in areas like the business technology timeline.

Another takeaway was the value of using images that enhance understanding. Each technology I mentioned had a visual to match, which helped make the information easier to remember.

---

### Engineering Design Process
I’m  currently building the prototype of our website to test how well it functions and looks across devices. Before starting the development, I created a clear plan that included a timeline of tasks and a wireframe to map out the structure of the site. I used [Wireframe.cc](https://wireframe.cc/) to design both a desktop and mobile version, making sure the layout would be responsive. This planning stage helped me stay organized and visualize how the content would be arranged. Once I had the wireframes done, I began coding the actual site using HTML, CSS, and Bootstrap components, following the plan I laid out. Now that my MVP is complete, I’ll be reviewing the website and identifying areas for improvement, especially focusing on responsiveness, spacing, and visual design. My next step is to refine the prototype and make sure it meets all the goals of the project.

---

### Skills
Some key skills I gained from this project were:
* Web development: I became much more confident using HTML and CSS and got better at integrating Bootstrap components like accordion, navbars, and cards.
* Design thinking: I learned how to build a website that's both functional and visually appealing by choosing the right colors and layout.
* Problem solving: When things didn’t work, I didn’t give up. I researched, asked for help, and experimented until I found solutions.

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
