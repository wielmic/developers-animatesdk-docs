## text.maxCharacters

#### Availability

Flash MX 2004.

#### Usage

text.maxCharacters

#### Description

Property; an integer that specifies the maximum number of characters the user can enter in this Text object.
This property works only with input text; if used with other text types, the property generates a warning.

#### Example

```javascript
The following example sets the value of the maxCharacters property to 30:
fl.getDocumentDOM().selection\[0\].maxCharacters = 30;

```