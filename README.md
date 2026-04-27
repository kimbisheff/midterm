# midterm
MIDTERM PRACTICUM: News Story Card

**Overview**
You're building a news story card from scratch: creating the folder, files and linking them together. This tests whether you understand HTML, CSS, file structure and responsive design.

**Assignment**

1. Create a new folder called "story-card-midterm"

2. Inside that folder, create two blank files:
   - index.html
   - style.css

3. Copy the HTML code into index.html
   Copy the CSS code into style.css

4. In index.html, find the comment that says "ADD YOUR LINK TAG HERE"
   Write the <link> tag that connects index.html to style.css

5. Open index.html in Chrome (File > Open File)
   Your story card should render with styling: red category badge, serif fonts, nice layout

6. Find a story you like on mustangnews.net or KCPR.org 

7. Customize the content
   Replace "Politics" with a beat that fits the story (Sports, Education, Local News, etc.)
   Change the headline to the story headline
   Change the byline to the author's name
   Change the date to the story's publication date
   Write a new excerpt that summarizes the story (2-3 sentences)
   Link "Read the full story" to the story URL 

9. Customize the style
   Change the color of the category badge by finding .story-category and change background-color
   Find .story-card and change the border-left to match the category badge color (badge & border must match) 
   Change the font-family to Arial, sans-serif 

10. Test responsive design
   Use Chrome DevTools (right-click, Inspect, click device toggle)
   Test at iPhone SE (mobile) and iPad Air (tablet)
   Your card should look good at all three sizes
   The border, padding and text should all adjust smoothly

11. Screenshot at two sizes
   Desktop width: full browser window
   Mobile width: iPhone SE in DevTools
   Submit both screenshots

**Common Issues**

- Page loads but has no styling? Your <link> tag is wrong. Check the file path and syntax
- Styling loads but your content changes broke things? Make sure you didn't delete HTML tags, just changed the text
- Card looks broken on mobile? That's what media queries are for. They're already in the CSS, so this shouldn't be an issue
- Can't open the page in Chrome: Make sure you're using File> Open File
