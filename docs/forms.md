## Input fields

```html|
<div class="flex flex-wrap">
  <form class="pv4 pr3 black-80 w-100 w-50-ns fl">
    <label for="name" class="f6 b db mb2">Name <span class="normal black-60">(optional)</span></label>
    <input id="name" class="input-reset ba b--black-20 pa2 mb2 db w-100" type="text" aria-describedby="name-desc">
    <small id="name-desc" class="f6 black-60 db mb2">Helper text for the form control.</small>
  </form>

  <form class="pv4 pl3 black-80 w-100 w-50-ns fl">
    <label for="password" class="f6 b db mb2">Password</label>
    <input id="password" class="input-reset ba b--red pa2 mb2 db w-100" type="text" aria-describedby="password-desc">
    <small id="password-desc" class="f6 red db mb2">Error message</small>
  </form>

</div>
```

## Checkboxes

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


## Radio Buttons

```html|
<div class="flex flex-wrap">
  <div class="radiobutton flex items-center mr4">
    <input checked class="fl mr2" id="radio-inline-1" type="radio" name="radio-inline-group" value="Yes">
    <label class="fl" for="radio-inline-1">Yes</label>
  </div>
  <div class="radiobutton flex items-center">
    <input class="fl mr2" id="radio-inline-2" type="radio" name="radio-inline-group" value="No">
    <label class="fl" for="radio-inline-2">No</label>
  </div>
</div>
```
