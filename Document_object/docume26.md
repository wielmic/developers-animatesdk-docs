## document.canRevert()

#### Availability

Flash MX 2004.

#### Usage

document.canRevert()

#### Parameters

None.

#### Returns

A Boolean value: true if you can use the document.revert() or fl.revertDocument() methods successfully;
false otherwise.

#### Description

Method; determines whether you can use the [document.revert()](#_bookmark262) or [fl.revertDocument()](#_bookmark528) method successfully.

#### Example

```javascript
The following example checks whether the current document can revert to the previously saved version. If so,
fl.getDocumentDOM().revert() restores the previously saved version.
if(fl.getDocumentDOM().canRevert()){ fl.getDocumentDOM().revert();
}

```