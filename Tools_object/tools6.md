## tools.penDownLoc

#### Availability

Flash MX 2004.

#### Usage

tools.penDownLoc

#### Description

Read-only property; a point that represents the position of the last mouse-down event on the Stage. The tools.penDownLoc property comprises two properties, *x* and *y*, corresponding to the *x,y* location of the mouse pointer.

#### Example

```javascript
The following example determines the position of the last mouse-down event on the Stage and displays the *x* and *y*
values in the Output panel:
var pt1 = fl.tools.penDownLoc;
fl.trace("x,y location of last mouseDown event was " + pt1.x + ", " + pt1.y)

```
#### See also

[tools.penLoc](#tools.penLoc)

<span id="tools.penLoc" class="anchor"></span>
