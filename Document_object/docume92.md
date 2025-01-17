## document.id

#### Availability

Flash CS3 Professional.

#### Usage

document.id

#### Description

Read-only property; a unique integer (assigned automatically) that identifies a document during a Flash session. Use this property in conjunction with [fl.findDocumentDOM()](#_bookmark483) to specify a particular document for an action.

#### Example

```javascript
The following example displays the document ID for the current document:
fl.trace("Current doc's internal ID is: " + fl.getDocumentDOM().id);

```
#### See also

[fl.findDocumentDOM()](#_bookmark483)
