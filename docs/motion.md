```html|plain,span-3,no-source
<div class="h5 w-100 relative">
  <div class="loader">
    <div class="dot"></div>
    <div class="dot"></div>
    <div class="dot"></div>
  </div>
</div>
```
```html|plain,span-3,no-source
<p class="f3 lh-copy">
Motion brings pages to life, delights the user and brings familiarity from the physical world. But more importantly helping users understand the spatial relationship between elements.
</p>

<ul class="list pa0">
  <li class="lh-copy pv3 ba bl-0 bt-0 br-0 b--solid b--black-10">Delighting the users with silky smooth animations.</li>
  <li class="lh-copy pv3 ba bl-0 bt-0 br-0 b--solid b--black-10">Guiding the users focus on what's happening on their screens.</li>
  <li class="lh-copy pv3 ba bl-0 bt-0 br-0 b--solid b--black-10"> Keeping the users attention.</li>
</ul>
```

## Animation timings

```html|plain,no-source
<div class="mt4 w-100 f7">
  <div class="flex justify-between flex-column flex-column-m flex-row-l mb3">
    <code>.transition-linear</code><code class="gray">Not to be used in production</code>
  </div>
  <div class="h2 bg-near-white mb2 overflow-hidden">
    <span class="transition-linear bg-measure-h transform-origin-reset w-100 h2 dib"></span>
  </div>
</div>
```

```html|plain,no-source
<div class="mt4 w-100 f7">
  <div class="flex justify-between flex-column flex-column-m flex-row-l">
    <code>.transition-cubic</code><code class="ba ph2 pv1 br2 b--black-10">cubic-bezier(0, 0.72, 0.24, 0.96)</code>
  </div>
  <div class="h2 bg-near-white overflow-hidden mt3">
    <span class="transition-cubic bg-measure-h transform-origin-reset w-100 h2 dib"></span>
  </div>
</div>
```
```html|plain,no-source
<div class="mt4 w-100 f7">
  <div class="flex justify-between flex-column flex-column-m flex-row-l">
    <code>.transition-warp</code><code class="ba ph2 pv1 br2 b--black-10">cubic-bezier(0,1,0,1)</code>
  </div>
  <div class="h2 bg-near-white overflow-hidden mt3">
    <span class="transition-warp bg-measure-h transform-origin-reset w-100 h2 dib"></span>
  </div>
</div>
```
```html|plain,no-source
<div class="mt4 w-100 f7">
  <div class="flex justify-between flex-column flex-column-m flex-row-l">
    <code>.transition-in-out</code><code class="ba ph2 pv1 br2 b--black-10">cubic-bezier(.5,0,0,1)</code>
  </div>
  <div class="h2 bg-near-white overflow-hidden mt3">
    <span class="transition-in-out bg-measure-h transform-origin-reset w-100 h2 dib"></span>
  </div>
</div>
```
