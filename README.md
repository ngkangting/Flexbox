# Introduction to Flexbox

The Flexible Box Module, usually referred to as Flexbox, was designed as a one-dimensional layout model, and as a method that could offer space distribution between items in an interface and powerful alignment capabilities. Thus, providing a more efficient way to lay out, align and distribute space among items in a container, even when their size is unknown and/or dynamic.

The main idea behind the Flexbox layout is to give the container the ability to alter its items' width/height in order to best fill the available space. A Flex container expands items to fill available free space, or shrinks them to prevent overflow in the container.

Most importantly, the Flexbox layout is direction-agnostic as opposed to the regular layouts of block, which is vertically-based, and inline, which is horizontally-based, as they lack the flexibility to support large or complex applications when it comes to orientation changing, resizing, stretching, shrinking on different devices.

With this powerful layout system available in CSS, it can replace float layouts, using less, more readable, and logical HTML and CSS for a single-direction layout concept.

## Flexbox Terminology

Before diving into the concepts of Flexbox, it is important to understand the terminology as the terms are conceptually similar. Thus, to avoid confusion, it is worthwhile spending a few minutes understanding Flexbox Terminologies.

- **Flex Container**

```
Parent element that holds the entire Flexbox.
```

- **Flex Item**

```
Element that is the direct child of the Flexbox Container.
```

- **Flex Direction**

```
Direction of Flex items that are placed in the Flex container.
```

- **Justify Content (Flex Container)**

```
Position Flex items along the Main Axis (Horizontally).
```

- **Align Items (Flex Container)**

```
Position Flex items along the Cross Axis (Vertically).
```

- **Align Self (Flex Item)**

```
Position Flex item along the Cross Axis (Vertically).
```

- **Order (Flex Item)**

```
Arrange Flex item in order. A higher number positions the Flex item to the end, and vice-versa.
```

- **Flex (Flex Item)**

```
Grow, Shrink and Setting the width of the Flex item.
```

- **Flex Wrap (Flex Items)**

```
Add a new row when there are too many Flex items.
```

**Note:** When the direction of Flex Items change, the direction of the Main Axis and Cross Axis will also be changed.

## Flexbox Properties

<img src="./img/CSS Properties.PNG" width="1000px" height="500px" title="CSS Properties Image">
