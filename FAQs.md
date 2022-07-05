# FAQs.... why?

I'm new to JavaScript— so new that I never learned it and jumped right into web-mapping and Svelte. It's like I never learned the alphabet and stepped right into the spelling 🐝 bee 🐝
So! If you're in the same boat as me, I figured we could all use some FAQs; one in which the answers are in ... regular people English and not full of more tech jargon!

1. What's the dealio with Node? What is it?
Open source, cross platform, back end JS environment? Node allows developers to write JavaScript code that runs directly in a computer process itself instead of in a browser. A JavaScript library for running web applications outside the client's browser.

2. What is a build system for a data journalist?
It's a series of tools and templates designed to make sure work is consistent across the board. Think of it as a sort of styleguide but for data work. 
Here's some examples:
- [The Pudding's build system](https://github.com/the-pudding/starter)
- [NPR's](https://github.com/nprapps/dailygraphics)
- [Reuters'](https://reuters-graphics.github.io/graphics-svelte-components/)

3. Where do you put the `<script>` tag?
When a browser loads a website, it first looks for the html page `index.html` page. When the browswer encounters a `<script>` tag, it looks for the other external file and executes it. This can cause a bad, slower user experience— because the website stops loading until all the script tags are executed. So! What's the fix? Putting the tag at the very end of the file is your quick-fix solution for this!