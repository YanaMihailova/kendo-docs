---
title: Segment
page_title: API reference for Kendo UI Drawing API Segment
---

# kendo.dataviz.drawing.Segment : kendo.Class
Defines a path segment with an anchor point and optional curve control points.

Segments are created implicitly by the [Path](path) lineTo and curveTo commands.

#### Example - accessing path segments
    <div id="surface"></div>
    <script>
        var d = kendo.dataviz.drawing;
        var geo = kendo.dataviz.geometry;

        var path = new d.Path()
            .moveTo(100, 100)  // Creates segment #0
            .lineTo(200, 100)  // Creates segment #1
            .stroke("red", 1);

        // Moves the line starting point 50px to the left
        path.segments[0].anchor().translate(50, 0);

        var surface = d.Surface.create($("#surface"));
        surface.draw(path);
    </script>

## Constructor Parameters

### anchor `kendo.dataviz.geometry.Point`
The anchor point of this segment.

If no control points are defined the path will pass through this point.

### controlIn `kendo.dataviz.geometry.Point` *optional*
The first curve control point of this segment, if any.

### controlOut `kendo.dataviz.geometry.Point` *optional*
The second curve control point of this segment, if any.

## Methods

### anchor
Gets or sets the segment anchor point.

The setter returns the current Segment to allow chaining.

#### Parameters

##### value `kendo.dataviz.geometry.Point`
The new anchor point.

#### Returns
`kendo.dataviz.geometry.Point` The current anchor point.


### controlIn
Gets or sets the first curve control point of this segment.

The setter returns the current Segment to allow chaining.

#### Parameters

##### value `kendo.dataviz.geometry.Point`
The new control point.

#### Returns
`kendo.dataviz.geometry.Point` The current control point.


### controlOut
Gets or sets the second curve control point of this segment.

The setter returns the current Segment to allow chaining.

#### Parameters

##### value `kendo.dataviz.geometry.Point`
The new control point.

#### Returns
`kendo.dataviz.geometry.Point` The current control point.

