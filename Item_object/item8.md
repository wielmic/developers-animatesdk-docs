## item.linkageExportForRS

#### Availability

Flash MX 2004.

#### Usage

item.linkageExportForRS

#### Description

Property; a Boolean value. If this property is true, the item is exported for run-time sharing. You can also set the
[item.linkageExportForAS](#_bookmark669) and [item.linkageExportInFirstFrame](#item.linkageExportInFirstFrame) properties to true.
If you set this property to true, the [item.linkageImportForRS](#_bookmark673) property must be set to false. Also, you must specify an identifier ([item.linkageIdentifier](#_bookmark672)) and a URL ([item.linkageURL](#_bookmark674)).

#### Example

```javascript
The following example sets this property for the specified library item:
fl.getDocumentDOM().library.items\[0\].linkageExportForRS = true;

<span id="item.linkageExportInFirstFrame" class="anchor"></span
```