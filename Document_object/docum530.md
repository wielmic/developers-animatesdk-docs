## document.setFilters()

#### Availability

Flash 8.

#### Usage

document.setFilters(filterArray)

#### Parameters

**filterArray** The array of filters currently specified.

#### Returns

Nothing.

#### Description

Method; applies filters to the selected objects. Use this method after calling document.getFilters() and making any desired changes to the filters.

#### Example

```javascript
The following example gets the filters on the selected object and sets the blurX property for all Blur filters to 50:
var myFilters = fl.getDocumentDOM().getFilters(); for (i=0; i \< myFilters.length; i++) {
if (myFilters\[i\].name == "blurFilter"){ myFilters\[i\].blurX = 50;
}
}
fl.getDocumentDOM().setFilters(myFilters);

```
#### See also

[document.addFilter()](#!wielmic/developers-animatesdk-docs/test/Document_object/documen3.md), [document.getFilters()](#!wielmic/developers-animatesdk-docs/test/Document_object/docume79.md), [document.setFilterProperty()](#!wielmic/developers-animatesdk-docs/test/Document_object/docum520.md), [Filter object](#!wielmic/developers-animatesdk-docs/test/Filter_object/filter_summary.md)
