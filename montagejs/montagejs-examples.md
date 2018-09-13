---

layout: docs
title: MontageJS Examples

this-page: montagejs-examples

redirect_from:
    - /docs/examples.html
    - /docs/kitchen-sink/
    - /docs/kitchen-sink.html

---


# MontageJS Examples

Follow the links on this page to explore demos and source code of MontageJS ui components and features in [Mfiddle](http://montagejs.github.com/mfiddle/).

## MontageJS Components
The following examples use prebuilt MontageJS components.

#### Text
* [Hello World](http://montagejs.github.io/mfiddle/#!/5904314)
* [Set text programmatically](http://montagejs.github.io/mfiddle/#!/5904331)
* [Set text with a binding](http://montagejs.github.io/mfiddle/#!/6343006)

#### Page Controls
* [Simple repetition](http://montagejs.github.io/mfiddle/#!/07a089a44c73a908cb40)
* [Simple substitution](http://montagejs.github.io/mfiddle/#!/5906283)

#### Converters
* [Number converters](http://montagejs.github.io/mfiddle/#!/5904344)

#### Composers
* [Press composer](http://montagejs.github.io/mfiddle/#!/7852383)
* [Translate composer](http://montagejs.github.io/mfiddle/#!/7854041)

#### Pattern
* [Sorting a Repetition](http://montagejs.github.io/mfiddle/#!/aeffafd1efbdd80530d4)

#### Controllers
* [Tree Controller](http://montagejs.github.io/mfiddle/#!/2e012d82ddd3d040cf74)

## UI Components (Digit)
The following examples use components that are part of the touch-optimized Digit UI set.

#### Button
* [Button with an explicit identifier](http://montagejs.github.io/mfiddle/#!/5906286) (used to link to a handler method)
* [Button with a default identifier](http://montagejs.github.io/mfiddle/#!/5906289) (serialization label is the default identifier)
* [Submit button without a specific handler](http://montagejs.github.io/mfiddle/#!/5906291) (the `handleAction()` method will be called when the "action" event is dispatched)

#### TextField
* [A simple text field](http://montagejs.github.io/mfiddle/#!/5906293)
* [A text field with a placeholder](http://montagejs.github.io/mfiddle/#!/5906294)
* [A disabled text field enabled by a button click](http://montagejs.github.io/mfiddle/#!/5906296)
* [A text field action](http://montagejs.github.io/mfiddle/#!/5906297)

#### TextArea
* [A simple text area](http://montagejs.github.io/mfiddle/#!/5904443)

#### Slider
* [A simple slider](http://montagejs.github.io/mfiddle/#!/5904461)
* [Two-way binding](http://montagejs.github.io/mfiddle/#!/5904468) (between a slider and a text field)

#### NumberField
* [A simple number field](http://montagejs.github.io/mfiddle/#!/5904473)
* [Bindings between number fields](http://montagejs.github.io/mfiddle/#!/5904479)

#### Select
* [A simple select](http://montagejs.github.io/mfiddle/#!/5904481)
* [A select powered by a range controller](http://montagejs.github.io/mfiddle/#!/5904482)
* [A select synchronized with a repetition](http://montagejs.github.io/mfiddle/#!/179e3a459daf280dabe1)

#### Checkbox
* [A simple checkbox](http://montagejs.github.io/mfiddle/#!/5904488)

#### RadioButton
* [A radio button group](http://montagejs.github.io/mfiddle/#!/5904493)

#### Image
* [An image](http://montagejs.github.io/mfiddle/#!/5904495)

#### List
* [A list of categories](http://montagejs.github.io/mfiddle/#!/85e4c0b3986c31e0a2e3)


## Draw Cycle
The draw cycle is a loop that allows components to change their element's DOM structure without troublesome reflow issues.

* Changing the background color of an element with a [slider](http://montagejs.github.io/mfiddle/#!/5904498)
