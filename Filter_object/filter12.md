## filter.knockout

#### Availability

Flash 8.

#### Usage

filter.knockout

#### Description

Property; a Boolean value that specifies whether the filter is a knockout filter (true) or not (false). This property is defined for Filter objects with a value of "bevelFilter", "dropShadowFilter", "glowFilter", "gradientBevelFilter", or "gradientGlowFilter" for the [filter.name](#filter.name) property.

#### Example

```javascript
The following example sets the knockout property to true for the Glow filters on the selected object(s):
var myFilters = fl.getDocumentDOM().getFilters(); for(i=0; i \< myFilters.length; i++){
if(myFilters\[i\].name == 'glowFilter'){ myFilters\[i\].knockout = true;
}
}
fl.getDocumentDOM().setFilters(myFilters);

```
#### See also

[document.setFilterProperty()](#_bookmark289)

<span id="filter.name" class="anchor"></span>
