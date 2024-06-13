[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/W8Voo9LP)
# dmit1530-lab-01

## In Class Lab #1 - Flexbox Layout
**Weight**: 5% of your final grade

## Instructions

Clone a copy of this repository to your device so that you can develop locally. When you are finished, make sure to push your latest commit to GitHub Classroom. 

On Moodle, in your Lab 01 instructions, you have been provided with a series of screenshots. You are tasked with adding the HTML and CSS needed to create the provided layout.  

### The Build Methodology 

#### Writing the HTML

1.	Add the HTML elements required to create a layout matching the screenshots. Use semantic HTML 5 elements and check the document structure in the HTML 5 outliner tool. There should be no _Untitled Sections_ and the heading structure should match the provided example below. 

> Responsive Flex Layout
>> Fluid & Responsive Flex Items
>> Sub-Heading
>> Sub-Heading
>> Sub-Heading
>> Sub-Heading
>>  Archive

2.	For the images, use placeholder images with a 500px by 400px dimension. 

3.	Give the first column and the final column two paragraphs of filler text (either generic lorem ipsum or a generator of your choice). Use only one paragraph of filler text for the other two columns.

4.  Add an aside with a simple unordered list and one paragraph of filler text. This will become a sidebar, which is a common feature in many online blogs.

5.	In your footer, add a link to the following article: 

`` https://css-tricks.com/snippets/css/a-guide-to-flexbox/ `` 

6.	Validate your HTML and repair any deficiencies. Any lab that throws a validation error will not be accepted.

#### Writing the CSS

7.	Starting with the styles needed for the smallest view, add the necessary CSS.

8.	The font sizing should render as follows: h1 heading 40px, h2 heading 30px, h3 heading 24px, and the body paragraph text 16px. 

**Note**: Do not use pixel values in your code. Your fonts should be sized in _relative units_. The only exceptions are for things that do not need to change their size depending upon the user's device and/or settings (ex. a rounded corner on a container).

9.	Style the header element to roughly match the screenshots. Give the header a bottom margin. It should render as 24px, but your code must use relative units.

10.	Each column will have a 1px border and 1rem of padding. On the smallest screen the columns will stack vertically, and they will need 1rem of margin on the top and the bottom to separate them.

11.	Inside the columns, the images will be placed on the left with the text on the right. The image should be vertically aligned to the centre. Give the images 40% of the available space and add 1rem of margin on the right side to move the text over. The text will take up the remaining room on the row.

12. In the footer, centre your text and ensure there is at least 2rem of padding on the top and bottom.

#### Adding Media Queries

13.	When the screen is wide enough to fit two columns across horizontally, create a media query for that width and change the layout of the columns. In this view, each column will take up 49% of the space on the row with the remaining 2% of space in-between them.

14.	Once the browser viewport is wide enough and the website layout changes, the layout inside of the columns will change too. Instead of being beside the text, the images will be on top (i.e. like a polaroid photo) with the text below. The images must be flexible, responsive, and they cannot be larger than the container element they are in.

15. Now that there's enough room, the sidebar should go to the side of the layout. We will let flexbox figure out how to size this element on its own.

16. Write a final media query for when the viewport reaches its largest size. The layout should **stop growing** or shrinking (i.e. switch to a fixed-width layout) and be **centred**. 

**Hint**: How can you horizontally centre a block-level element? Check out this guide: https://css-tricks.com/centering-css-complete-guide/

The **background colours** should still span the entire width of the viewport, no matter what its size is. 

16. Push your assignment files back up to GitHub Classroom.
