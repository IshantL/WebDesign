# Web Design Course

## This web design code is developed to learn web designing steps by steps

1. you can clone the code to test it on your machine.
2. The lessons are divided into sections, so you can learn by refering the commits.

# HTML

## Section 1 -Welcome
- Welcome

## Section 2- HTML Essentials

1. Basic list in html
2. HTML document Structure
3. Linking Pages together

## Section 3 - Adding Media to web pages
 1. image files
 2. Audio files
 3. Video files

 ## Section 4 - Text Basics
 1. Headings
 2. Lists- unordered, ordered and descripition 
 3. Bold and Italic

 ## Section: 5
 1. Semantics & Organization
 2. Navigations
 3. Non-semantic Elements ("div" and "span")
    -div (block level element)
    -span (inline element)
 4. HTML Comments
 5. Sections- Here inside section it will change the size of text depends on sub sections.

 ## Section 6
 1. HTML Forms
 2. Different Types of Inputs
 3. Choosing Between a set of options

 ## Section 7
 1. Table
 2. Do not use table for layout

# CSS

## Section 8 -CSS Essential
1. Introduction to CSS --> h1{}.. here h1 is selector
2. CSS selector
    -Type Selector
    -Descendant Selector - inside other e.g: 
    ```
    p span{}
    ```
    -Class Selector -e.g 
    ```
    .highlight{}
    ```
3. Box Model-
    A box is nothing more than an area that takes up space on the web page to create space within the inside of that box. We use padding to draw an outline around the outer edge of that box.
    We use border and then to push or create space around the outside of the box we use margin.

4. Creating a Page layout with float
5. Beatify the page Layout.

## Section 9 - Intermediate CSS
1. Styling Navigation Menu
2. Overlapping content & Transparent background:

    Absolute lets us provide x and y coordinates or horizontal and vertical coordinates to position the element in a very particular fashion. However by doing this it also removes the content from the regular flow of the page. This means that as far as every other element on the page is concerned this content no longer exists So very quickly let's remove this code just to prove a point. So we saw that by default this text sat underneath the image.Now as soon as is positioned absolutely.Watch how this text as soon as I refresh watch this text simply move up as if that text no longer exists at all.

    Now you may be wondering why would I ever use position absolute if it completely removes the content from the flow of the page.How is that every useful. The answer is that nine times out of 10 in order for a position absolute to be useful it needs to be used in conjunction with position relative.So for example when we specified that this text should sit 50 pixels from the top and 50 pixels from the left. The question that we need to ask ourselves is 50 pixels from the left of what or 50 pixels from the top of what.

    Now by default the browser will use the Web browser window as our frame of reference for the top and left values.However an element that uses position absolute will search up its family tree or up its Russian stacking doll model for the closest ancestor element that uses position relative. And once it finds that element it will use it as its frame of reference for these values.So we know that in our HMO there's bannered description element which is what is housing this text.We know that it has a parent element of image banner.So if I change image banner to use position relative watch what happens when we refresh this text is now positioning itself 50 pixels from the top of the image banner and 50 pixels from the left of the image banner.
    
    If we look very closely we can see that the bottom of our text box is not lining up perfectly with the bottom of the image.Our text box is about two or three pixels too low. The reason this is happening is because the overall height of our image banner parent element is being determined obviously by the size of the image and by default images are inline elements.

    So this means when the browser tries to calculate the height it can use things like font size and line height values and it's not as precise. So we really want this image to be a block level element. So in our CSS I'm going to target any image elements that live within image banner and then I will simply tell them to be block level. So if we refresh can see that the two elements are now perfectly aligned.

    So here's a quick review.
    
    Absolute lets you remove an element from the natural flow of the page and instead position it in relation to an ancestor element absolutely positioned elements will look for the closest ancestor element that uses position relative and it will use that element as its frame of reference. If the absolutely positioned element does not have any ancestors which use position relative it will use the Web browser window as a whole as its frame of reference if multiple elements are overlapping each other and you want to have fine grained control over which element stacks on top of the other. You can use the z index property to establish a stacking order.

## Section 10 - Neccesary CSS tasks
1. Styling Data tables
2. Styling Forms

## Section 11 - CSS Typography
1. CSS typography
2. Using Custom web fonts

## Section 12- Developer Tools

## section 13 - CSS Background
1. Background Images
2. Gradient Background
3. CSS Sprites
4. Full Width Backgrounds - Fixed Width Content

## section 14 -CSS preprocessor
1. SCSS
