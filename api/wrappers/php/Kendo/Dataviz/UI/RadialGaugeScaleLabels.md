---
title: RadialGaugeScaleLabels
slug: php-RadialGaugeScaleLabels
tags: api, php
publish: true
---

# \Kendo\Dataviz\UI\RadialGaugeScaleLabels

A PHP class representing the labels setting of RadialGaugeScale.


## Methods

### background
The background color of the labels.
Any valid CSS color string will work here, including hex and rgb
#### Parameters

##### $value `string`



#### Example 
    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $labels->background('value');

### border

#### Parameters

##### $value `\Kendo\Dataviz\UI\RadialGaugeScaleLabelsBorder|array`

The border of the labels.


#### Example - using \Kendo\Dataviz\UI\RadialGaugeScaleLabelsBorder

    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $border = new \Kendo\Dataviz\UI\RadialGaugeScaleLabelsBorder();
    $color = 'value';
    $border->color($color);
    $labels->border($border);

#### Example - using array

    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $color = 'value';
    $labels->border(array('color' => $color));

### color
The text color of the labels.
Any valid CSS color string will work here, including hex and rgb.
#### Parameters

##### $value `string`



#### Example 
    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $labels->color('value');

### font
The font style of the labels.
#### Parameters

##### $value `string`



#### Example 
    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $labels->font('value');

### format
The format of the labels.
#### Parameters

##### $value `string`



#### Example 
    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $labels->format('value');

### margin
The margin of the labels.
#### Parameters

##### $value `float|`



#### Example  - using float
    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $labels->margin(1);

### padding
The padding of the labels.
#### Parameters

##### $value `float|`



#### Example  - using float
    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $labels->padding(1);

### position
The labels positions.
#### Parameters

##### $value `string`



#### Example 
    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $labels->position('value');

### template
The label template.
Template variables:
#### Parameters

##### $value `string|\Kendo\JavaScriptFunction`



#### Example  - using string
    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $labels->template('value');

#### Example  - using \Kendo\JavaScriptFunction
    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $labels->template(new \Kendo\JavaScriptFunction('function() { }'));

### visible
The visibility of the labels.
#### Parameters

##### $value `boolean`



#### Example 
    $labels = new \Kendo\Dataviz\UI\RadialGaugeScaleLabels();
    $labels->visible(true);
