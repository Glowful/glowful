<div align="center"><span style="font-size:32px;">✨Glowful website for fun things you want to get around to!! ✨</span>

I am often writing to-do lists and realising I keep thinking "oh yeah I really want to do that thing....."

This is the app my brain needs!!!
For fun ideas!!!!!

Let's see how it goes using AI<sup>*</sup>! Try it out!!! https://glowful.github.io/glowful/
</div> 


   <sup>*</sup>*Very concerned about AI with the data center unethical impacts to people and environments, as well as systematic perpetuation of bias, inaccuracy, and uncredited use of source data*
     

<img width="300"  alt="image1" src="https://github.com/user-attachments/assets/b65c67c6-8712-4eab-8d86-89dd0a6dc04f" />
<img width="300"  alt="image0" src="https://github.com/user-attachments/assets/44bc9cc6-d83c-4869-a919-8fd94751b75a" />
<img width="300"  alt="image2" src="https://github.com/user-attachments/assets/492d0cfb-4c71-477c-9d24-a66523a4dabd" />



The initial prompt from my brain:
```
Local storage
Runs in browser
Can be used on mobile (instructions as here) but with sensible equivalents if on desktop
To do list items are stored as 'a text', the text each has the following attributes: glowfulness: a number, a position in the list in 'list view' and a position in 2d space in the 'field view'
In non-editing mode only the rendered text is displayed, in editing one of the texts mode you can edit text and also there is a dial for glowfullness from 1 to 9 you can spin and you can click enter to save and exit editing mode
Very dark blue background
Snazz design/fonts, friendly, (maybe a bit like an old pixelated game)
Opens by default to list view
You can click to toggle to the other view 'field view' at the top
There is a hamburger menu for getting to settings

In both views you can pinch etc to zoom in and out, two finger drag to move the canvas
To revert to original zoom click a small rectangle symbol on the menu

There are 2 viewing modes for the whole list
One is 'list view' a list which can be dragged and dropped, if you hold for a moment then drag
It's a centred list, a bit of space in between each entry
A few little sparkles in the background like a star
You can scroll
The other is 'field view' all the texts in 2d space which can each be dragged and dropped.
You can add edit or remove a text from either viewing mode. The glowfulness is editable in the editing display. The position in 2d space is not visible in the editing mode but is stored and updated depending on where it is dragged in the field view. They start by default at the bottom left, not overlapping with existing texts (so they will have to be added below the one that is already there if there is one)
In field view, the texts are draggable and double click to edit
It's also possible to add headings in the 2d space which are also editable/removable but they are in a different font and slightly bigger than the text. (Headings aren't used in list view)
When you add a new text in Field view via clicking 'add item' it appears in the middle of the window and you already get the keyboard up to start typing. Pressing enter means it's done.
Double click to edit text
Drag to move

Glowfulness is used to render the text, same in both views. They are all like a neon sign in a nice font. A low number has low glowfulness and a higher number has higher glowfulness. A low number is blue then it goes up to green purple pink for high glowfulness (as well as more neon glow affect behind the text)

In a settings menu, there is a way to export and important the whole data stored. That also includes the headings

You can important a text or multiple texts - if you just paste - if you paste in multiline text it will interpret each one as a a text. For imports they default to lowest glow and appear at top of list and bottom left of field view
To be able to paste, you can hold down on a non-text area and then from a dropdown that appears click paste

Include other common conventions for this app, eg making it configurable and user friendly and nicely spaced out 

If a duplicate is added, the existing one goes up in glowfulness number. an animation comes up of the existing item increasing in glowfulness to the new one. Just the displayed text not the number itself. You are then taken to where in the view that text is so it's in the middle of the screen

Lets add a bonus view accessible in settings which is a table, of the texts, which includes their glow number and is editable directly. Sorted by list view order.


There are undo /redo  buttons which just go back /forth  through the website state of what you did
```
