# Decoration

| Category | Version | Requires |
|:--------:|:-------:|:--------:|
|Utilities|1|API 19 | Android 4.4 - 4.4.4 KitKat|

:mag: {>>Non-visible component<<}

## Overview

A non-visible component that modifies other components'' padding, margins, and other visual properties.

## Methods

### SetMargin

_Block preview not available_

??? tip "Parameters"

    | Name | Type |
    |------|------|
    |component|`component`|
    |values|`text`|


Margin is a way for a component to enforce some distance from others components. By specifying margin for a component, we say that keep this much distance from this component.

### SetPadding

_Block preview not available_

??? tip "Parameters"

    | Name | Type |
    |------|------|
    |component|`component`|
    |values|`text`|


The padding around the component. Padding is the space inside the border, between the border and the actual component content. Use single number like 5 to specify padding for top, left, bottom, righ. You can also use 4 different numbers like 5,0,10,0 for top, left, bottom right.

### SetShape

_Block preview not available_

??? tip "Parameters"

    | Name | Type |
    |------|------|
    |component|`component`|
    |background Color|`number`|
    |border Color|`number`|
    |is Round|`boolean`|


This block allows you to create a rectangle or round shape for the visible component. You can use Color for backgroundColor and borderColor.