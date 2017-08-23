## \<show-more>

This element makes additional content collapsible.
It implements expand/collapse animations with the [scale & counter-scale transform technique](https://codelabs.developers.google.com/codelabs/expand-collapse-animations/),
and pushes up/down `<show-more>` siblings using position transforms, achieving buttery-smooth, 
60fps animations.

```html
<iron-list>
  <template>
    <show-more show>
      <p slot="main" onclick="toggleShow(event)">Main content</p>
      <div slot="more">More content</div>
    </show-more>
  </template>
</iron-list>
```

![show-more](https://user-images.githubusercontent.com/6173664/29624173-b3892e46-8828-11e7-83af-7fcb14021c9a.gif)
