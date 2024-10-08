## Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   Mobile-first workflow

## What was done

### 2024.08.25

-   Remembering how to set up the variables, resets, and identifying problems that occurred during the initial portfolio build
-   Try not to set up tailwind classes without using tailwind yet. For example, setting a `flex-vertical` class only to have to undo it at larger screens is not good practice
-   Only set up the tailwind classes if they are consistent among all screen sizes
-   Need to set up variables more intelligently. Identify what the sizes are from the style guide and have a system for referencing them ie. Kevin Powell's 400
-   Find out of the `fontsize: 62.5%` is bad practice

### 2024.08.27
- forgetting what everything is called
- you never know what to name anything
- New property: `clip-path`
	- This property 
- Need to understand `position: reative, absolute` better
- Will figure out how to do the image overlaps and background botom curves

### 2024.08.28
- Less is more.
- Spent most of the day figuring out the bottom curve. Lesson is, you don't have to position relative or absolute a bunch of stuff. Sometimes it's just creating a property with the shape, then repositioning 1 element to overlap it.
- Careful were you name your background colors. They get tricky with the curves if you're doing it this way.
- Be cautious where you declare your spacing as well. Had to find the "gap" that was separating the background colors because it was in the `flex-wrapper`

### 2024.08.29

- Completed section two. Remember to look at the desktop designs to set up the html for all screens before adding the flex propeties to the appropriate html tags
- Struggling with positioning elements and not sure which method is best practice for which situation. Currently undergoing constant trial and error. Will look up solutions to see the different methods.

### 2024.08.30
- Continue work with section 2 and understand the solution to centering the relatively positioned elements whilst keeping the design pattern (9:08)
- split right with `cmd + \`
- Completed all the responsiveness and alignments. It was really all about just playing with the numbers until I reached the placements I was happy with (9:57)
- Completed the image pattern absolutes. Remember that the positioned absolute elements are relative to the closest ancestor. At first the bg-pattern in the third section changed significantly when moving to a screen with different aspect ratios. (1:05 - 1:30)

### 2024.08.31
- Finished the design yesterday.
- Just noticed the fonts were in the assets folder, did not need to import from google.

### Continued development

### Useful resources

-   [Shape divider](https://www.shapedivider.app/) - I didn't use thi, but this website helps create an svg shape divider can could have been an option for creating the curves

### Author

-   Website - [Julius Foo](https://www.julius.foo)
-   Linkedin - [linkedin.com/juliusfoo](https://www.linkedin.com/juliusfoo)

### Acknowledgments

-   Thank you to Gemini
