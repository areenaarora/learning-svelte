# Learning Svelte!
- A JavaScript library
- An open-source front end compiler
- Instead of using a virtual DOM, Svelte will directly update the DOM in an efficient way --> I don't understand what this means YET🤔
- we have HTML that looks like HTML, CSS that looks like CSS, and JavaScript that looks like JavaScript, all packed in a single svelte file

## FAQs/web dev life lessons
1. What is a build system for a data journalist?
It's a series of tools and templates designed to make sure work is consistent across the board. Think of it as a sort of styleguide but for data work. 
Here's some examples:
> [The Pudding's build system](https://github.com/the-pudding/starter)
> [Reuters'](https://reuters-graphics.github.io/graphics-svelte-components/)
> [NPR's](https://github.com/nprapps/dailygraphics)

2. Where do you put the `<script>` tag?
When a browser loads a website, it first looks for the html page `index.html` page. When the browswer encounters a `<script>` tag, it looks for the other external file and executes it. This can cause a bad, slower user experience— because the website stops loading until all the script tags are executed. So! What's the fix?

## Getting started
1. Components: These are the building blocks of Svelete. 
Uhhh okay? What does that even mean? For this and more confusing questions, please refer to my FAQs doc— a handy dandy guide of sorts!