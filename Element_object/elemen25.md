## element.width

#### Availability

Flash MX 2004.

#### Usage

element.width

#### Description

Property; a float value that specifies the width of the element in pixels.
Do not use this property to resize a text field. Instead, select the text field and use [document.setTextRectangle()](#_bookmark313). Using this property with a text field scales the text.

#### Example

```javascript
The following example sets the width of the specified element to 100:
fl.getDocumentDOM().getTimeline().layers\[0\].frames\[0\].elements\[0\].width= 100;

```