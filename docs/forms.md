## Input single

```html|plain
<div class="flex flex-wrap pa4">
  <form class="pv2 black-80 w-100 fl">
    <label for="password" class="f6 b db mb0">Enter your name</label>
    <input id="password" class="mb2 input-reset bg-transparent bw1 b--black-40 pv3 ph1 bb bt-0 br-0 bl-0 w-100" type="text" aria-describedby="pass-desc">
  </form>
</div>
```
## Input example

```html|plain
<div class="flex flex-wrap pa4">
  <form class="pv4 pr3-ns black-80 w-100 w-50-ns fl">
    <label for="name" class="f6 b db mb0">Name <span class="normal black-60">(optional)</span></label>
    <input id="name" class="mb2 input-reset bg-transparent bw1 b--black-40 pv3 ph1 bb bt-0 br-0 bl-0 w-100" type="text" aria-describedby="name-desc">
    <small id="name-desc" class="f6 black-60 db mb2">Default form</small>
  </form>

  <form class="pv4 pl3-ns black-80 w-100 w-50-ns fl">
    <label for="password" class="f6 b db mb0">Password</label>
    <input id="password" value="hunter2" class="mb2 input-reset bg-transparent bw1 b--c-red pv3 ph1 bb bt-0 br-0 bl-0 w-100" type="password" aria-describedby="pass-desc">
    <small id="password-desc" class="f6 c-red db mb2">Error message</small>
  </form>

  <form class="pv4 black-80 w-100 w-100-ns fl">
    <label for="password" class="f6 b db mb0">Placeholder example</label>
    <input id="password" placeholder="Placeholder" class="mb2 input-reset bg-transparent bw1 b--black-40 pv3 ph1 bb bt-0 br-0 bl-0 w-100" type="text" aria-describedby="pass-desc">
  </form>

  <form class="pv4 black-80 w-100 w-100-ns fl">
    <label for="password" class="f6 b db mb0">Password</label>
    <input id="password" class="mb2 input-reset bg-transparent bw1 b--black-40 pv3 ph1 bb bt-0 br-0 bl-0 w-100" type="text" aria-describedby="pass-desc">
  </form>
  <a href="javascript:;" class="pv3 ph4 bg-c-red white bw1 link dim dib">Log in</a>
</div>
```

## Checkboxes Horizontal

```html|
<div class="flex flex-wrap">
  <div class="checkbox flex items-center mr4">
    <input checked class="fl mr2" id="checkbox-inline-1" type="checkbox" name="checkbox-inline-group" value="Yes">
    <label class="fl" for="checkbox-inline-1">Yes</label>
  </div>
  <div class="checkbox flex items-center">
    <input class="fl mr2" id="checkbox-inline-2" type="checkbox" name="checkbox-inline-group" value="No">
    <label class="fl" for="checkbox-inline-2">No</label>
  </div>
</div>
```


## Radio Buttons Inline & Stacked

```html
<h3 class="ma0 mb4">Do you agree?</h3>
<div class="flex flex-wrap">
  <div class="radiobutton flex items-center mr4">
    <input checked class="fl mr2" id="radio-inline-1" type="radio" name="radio-inline-group" value="Yes">
    <label class="fl" for="radio-inline-1">Yes</label>
  </div>
  <div class="radiobutton flex items-center mr4">
    <input class="fl mr2" id="radio-inline-2" type="radio" name="radio-inline-group" value="No">
    <label class="fl" for="radio-inline-2">No</label>
  </div>
</div>
```

```html
<h3 class="ma0 mb4">Do you agree?</h3>
<div class="flex flex-column">
  <div class="radiobutton flex items-center mb3">
    <input checked class="fl mr2" id="radio-inline-3" type="radio" name="radio-stacked-group" value="Yes">
    <label class="fl" for="radio-inline-3">Yes</label>
  </div>
  <div class="radiobutton flex items-center">
    <input class="fl mr2" id="radio-inline-4" type="radio" name="radio-stacked-group" value="No">
    <label class="fl" for="radio-inline-4">No</label>
  </div>
</div>
```
