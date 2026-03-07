# dog

Learning HTML --- lesson 16

## Spacing and Offset Principles

For parent element's if we want to make offset of elements we need to do it by paddings.

**Example:**

- Section one ends - some padding in bottom
- New section starts - some padding top

In another words:

- If we need offset of child elements we need to use padding of parent element
- Use margin for offset between child elements

**Example:**

- Child `<p>` then another child `<p>` with margin-top

## Z-index works only with elm with positions not static (relative, absolute, fixed)

## Transform common use
 - transform: rotate(180deg); // rotate;
 - transform: translateX: 100% // offset ouf screen;
 on click, move back to screen
 - transform: translateX: 0;

 ## checkbox
 - we cannot style it, we should visually hide checkbox input, and leave label.
 - then we need to create wrapper with relative position and add absolute position before to the label an style it

 ## Hot keys
CMD + M // wrap with div for example