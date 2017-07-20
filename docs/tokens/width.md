The widths module contains both a five-step width scale based on powers of two as well as a series of percentage values that can be combined with floats for an infinitely nestable and fully responsive grid system.




### Static
```html|plain


<div class="flex">
  <div class="mr3">
    <div class="f6 h1 mb2 lh-solid fw3 code">
      .w1 (1rem)
    </div><div class="f6 h1 mb2 lh-solid fw3 code">
      .w2 (2rem)
    </div><div class="f6 h1 mb2 lh-solid fw3 code">
      .w3 (4rem)
    </div><div class="f6 h1 mb2 lh-solid fw3 code">
      .w4 (8rem)
    </div><div class="f6 h1 mb2 lh-solid fw3 code">
      .w5 (16rem)
    </div>
  </div>
  <div class="flex-auto">
    <div data-index="0" class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w1" style="transform: scaleX(1);"></div>
    <div data-index="1" class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w2" style="transform: scaleX(1);"></div>
    <div data-index="2" class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w3" style="transform: scaleX(1);"></div>
    <div data-index="3" class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w4" style="transform: scaleX(1);"></div>
    <div data-index="4" class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w5" style="transform: scaleX(1);"></div>
  </div>
</div>

```

### Percentage


```html|plain
<div class="flex">
  <div class="mr3">
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-10 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-20 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-30 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-33 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-34 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-40 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-50 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-60 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-70 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-80 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-90 </div>
    <div class="f6 h1 mb2 lh-solid fw3 code">.w-100</div>
  </div>
  <div class="flex-auto">
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-10"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-20"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-30"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-33"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-34"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-40"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-50"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-60"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-70"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-80"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-90"></div>
    <div class="tc h1 origin-0-0 bb b--c-red mr3 mb2 w-100"></div>
  </div>
</div>
```
