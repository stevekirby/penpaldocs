# Tabs and selections

## Tabs

There are three tabs at the top of the panel, denoted by symbols: ![](<.gitbook/assets/tabs - paths.svg>)Paths, ![](<.gitbook/assets/tabs - points.svg>)Points and ![](<.gitbook/assets/tabs - tangents.svg>)Tangents. Clicking on these tabs displays different groups of buttons, and highlights the relevant elements in the canvas. [Path functions](path-tab.md) affect the path as a whole - it will maintain it’s proportions and essential shape. [Point functions](points-tab.md) affect the points within one or more shapes. [Tangent functions](tangents-tab.md) affect the tangents.

## Selections

You can select elements by dragging a marquee over them, or by clicking on them one-by-one. [Paths](path-tab.md) can only be selected by the drag-marquee method. Hold `Shift` or `Cmd/Ctrl` to add to or remove from a selection.

Selecting elements in the canvas is not dependent on tabs - you can still select points while you're in the tangents tab, and so on.

Selected points and tangents are displayed with a filled icon (squares for points and circles for tangents), whereas unselected points and tangents are displayed with an empty, stroked icon. Selected paths are slightly thicker in the points and tangents tabs, and blue when in the paths tab.

{% hint style="warning" %}
Unlike Adobe software generally, selecting a point does **not** automtically select it’s tangents. In Penpal, they are treated as separate things. To select both tangents of a pair, you need to drag the marquee over both of them, or Shift-click on them one-by-one.
{% endhint %}
