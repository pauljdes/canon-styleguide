## Desktop
Buttons communicates actions that can be made by the user.
```html|
<a href="javascript:;" class="pv3 ph4 bg-c-red white bw1 link dim dib">Primary Button</a>
```

```html|
<a href="javascript:;" class="pv3 ph4 b--gray b--solid gray bw1 link dim dib">Secondary Button </a>
```

```html|
<a href="javascript:;" class="pv3 ph4 c-blue bw1 link dim dib">Tertiary Button →</a>
```

```html|dark
<a href="javascript:;" class="pv3 ph4 white bw1 link dim dib">Tertiary Button →</a>
```

## Mobile
Buttons on mobile will span 100% of it's parents or the viewport
```html|span-3
<a href="javascript:;" class="pv3 w-100 tc ph4 bg-c-red white bw1 link dim dib">Primary Button</a>
```
```html|span-3
<a href="javascript:;" class="pv3 w-100 tc ph4 gray b--solid bw1 link dim dib">Secondary Button</a>
```

## Button group
Button groups should be displayed when the intended action correlates with eachother. For instance a button group may be used to show and hide content depending on the selected button
```html|
<div class="flex items-center justify-center flex-column">
  <div class='cf dib'>
    <a class="f6 fl link bb bt bl ph3 pv2 dib near-white b bg-black b--black br2 br--left bl" href="javascript:;">Raw</a>
    <a class="f6 fl hover-bg-black hover-white b--black link ba ph3 pv2 dib black" href="javascript:;">Gzipped</a>
    <a class="f6 fl hover-bg-black hover-white b--black link bb bt ph3 pv2 dib black br2 br--right br" href="javascript:;">Minified</a>
  </div>
</div>
```
