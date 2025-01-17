## stroke.length

#### Availability

Flash MX 2004.

#### Usage

stroke.length

#### Description

Property; a string that specifies the length of a hatch line. This property is available only if the stroke.style property is set to hatched (see [stroke.style](#_bookmark898)). Acceptable values are "equal", "slight variation", "medium variation", and "random". (The value "random" actually maps to "medium variation".)

#### Example

```javascript
The following example sets the length property to slight for a stroke style of hatched:
var myStroke = fl.getDocumentDOM().getCustomStroke(); myStroke.style = "hatched";
myStroke.curve = "straight"; myStroke.space = "close"; myStroke.jiggle = "wild"; myStroke.rotate = "free"; myStroke.length = "slight variation"; myStroke.hatchThickness = "thin";
fl.getDocumentDOM().setCustomStroke(myStroke);

```