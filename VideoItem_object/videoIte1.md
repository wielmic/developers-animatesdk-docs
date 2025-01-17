## videoItem.fileLastModifiedDate

#### Availability

Flash CS4 Professional.

#### Usage

videoItem.fileLastModifiedDate

#### Description

Read-only property: a string containing a hexadecimal number that represents the number of seconds that have elapsed between January 1, 1970, and the modification date of the original file (on disk) at the time the file was imported to the library. If the file no longer exists, this value is "00000000".

#### Example

```javascript
Assuming that the first item in the Library is a video item, the following code displays a hexadecimal number as described above.
var libItem = fl.getDocumentDOM().library.items\[0\];
fl.trace("Mod date when imported = " + libItem.fileLastModifiedDate);

```
#### See also

[videoItem.sourceFileExists](#_bookmark1145), [videoItem.sourceFileIsCurrent](#_bookmark1146), [videoItem.sourceFilePath](#_bookmark1147), [FLfile.getModificationDate()](#_bookmark568)
