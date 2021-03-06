# \<get-lazy\>

Lightweight lazy loading content component for Polymer.

## Demo

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="get-lazy.html">
    <style>
      img {
        max-width: 100%;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<dom-bind>
    <template is="dom-bind">
        <get-lazy data-id="{{demoId}}"
                  data-src="image/default.jpg"
                  data-src-xs="image/xs.jpg"
                  data-src-sm="image/sm.jpg"
                  data-src-md="image/md.jpg"
                  data-src-lg="image/lg.jpg"
                  data-src-xl="image/xl.jpg"
                  data-src-hd="image/hd.jpg"
                  data-class-id="{{demoClass}}"
                  data-class="animate fadeIn"
        ></get-lazy>
        <img title="Demo Image" src$="{{demoId}}" class$="{{demoClass}}"/>
    </template>
</dom-bind>
```


## Demo 2

<!---
```
<custom-element-demo>
    <dom-bind>
        <template>
        <script src="../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="get-lazy.html">
        <style>
              img {
                max-width: 100%;
              }
        </style>
        <next-code-block></next-code-block>
        </template>
    </dom-bind>
</custom-element-demo>
```
-->
```html
<get-lazy data-id="{{demoId}}"
          data-src="image/default.jpg"
          data-src-xs="image/xs.jpg"
          data-src-sm="image/sm.jpg"
          data-src-md="image/md.jpg"
          data-src-lg="image/lg.jpg"
          data-src-xl="image/xl.jpg"
          data-src-hd="image/hd.jpg"
          data-class-id="{{demoClass}}"
          data-class="animate fadeIn"
></get-lazy>
<img title="Demo Image" src$="{{demoId}}" class$="{{demoClass}}"/>
```