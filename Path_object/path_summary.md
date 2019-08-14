## path summary

#### Availability

Flash MX 2004.

#### Description

The Path object defines a sequence of line segments (straight, curved, or both), which you typically use when creating extensible tools. The following example shows an instance of a Path object being returned from the flash object:
path = fl.drawingLayer.newPath();
See also the [drawingLayer object](#!wielmic/developers-animatesdk-docs/test/drawingLayer_object/drawingLayersummary.md).

#### Method summary

The following methods are available for the Path object:

| **Method**                                    | **Description**                                                                                                           |
|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| [path.addCubicCurve()](#!wielmic/developers-animatesdk-docs/test/Path_object/path.md)) | Appends a cubic Bézier curve segment to the path.                                                                         |
| [path.addCurve()](#!wielmic/developers-animatesdk-docs/test/Path_object/path1.md)              | Appends a quadratic Bézier segment to the path.                                                                           |
| [path.addPoint()](#!wielmic/developers-animatesdk-docs/test/Path_object/path2.md)              | Adds a point to the path.                                                                                                 |
| [path.clear()](#!wielmic/developers-animatesdk-docs/test/Path_object/path3.md)                 | Removes all points from the path.                                                                                         |
| [path.close()](#!wielmic/developers-animatesdk-docs/test/Path_object/path4.md)                 | Appends a point at the location of the first point of the path and extends the path to that point, which closes the path. |
| [path.makeShape()](#!wielmic/developers-animatesdk-docs/test/Path_object/path5.md)             | Creates a shape on the Stage by using the current stroke and fill settings.                                               |
| [path.newContour()](#!wielmic/developers-animatesdk-docs/test/Path_object/path6.md)            | Starts a new contour in the path.                                                                                         |

#### Property summary

The following properties are available for the Path object:

| **Property**               | **Description**                                                      |
|----------------------------|----------------------------------------------------------------------|
| [path.nPts](#!wielmic/developers-animatesdk-docs/test/Path_object/path7.md) | Read-only; an integer representing the number of points in the path. |

<span id="path.addCubicCurve()" class="anchor"></span>

