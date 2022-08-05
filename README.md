# javascript-building-blocks-events

You should begin by reading the Mozilla page [JavaScript Building Blocks: Introduction to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events). Then you should be ready to tackle the [*Test your skills*](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Test_your_skills:_Events) for events! But see any notes below for advice/guidance.

As always, submit your work (for review or help) by committing your code here at GitHub.

## Notes

### Task 1

No notes for once!

### Task 2

The WASD keys are used in some keyboard-based games as substitutes for the arrow keys. W represents up, A is left, S is down, and D is right. The idea is that you should appropriately change the (x,y) coordinates of the (center of the) circle each time one of these keys is pressed.  Keep in mind that, in browser graphics, y increases as you move down the page.  That is, the (0,0) coordinate is in the upper left corner of the page.

One tricky part of this is question to decide on what object to call the `addEventListener()` method. What you want is essentially for the entire page to be listening for keyboard events. What object represents the entire page? If you read _Introduction to Events_ carefully, you'll see the answer to this question there, although they don't quite come out and say it.

Because my function for processing the keystrokes was somewhat long, I found it more readable to write a named function to be the keystroke event listener. I then passed the function's name to `addEventListener()` rather than passing an arrow function as an argument. But you can use whatever coding approach works best for you.

### Task 3

As with the previous task, I found it more readable to write a named function to be the event listener. 

I also used the DOM's [`getAttribute()`](https://developer.mozilla.org/en-US/docs/Web/API/Element/getAttribute) method as well as the [`style`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/style) property that every HTML element has. Use of both of these is illustrated in the Mozilla Events page.
