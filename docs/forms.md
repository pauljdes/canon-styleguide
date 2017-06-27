## Input single

```html|plain
<div class="flex flex-wrap pa4">
  <form class="pv2 black-80 w-100 fl">
    <label for="password" class="f6 b db mb2">Enter your name</label>
    <input id="password" class="mb2 input-reset bg-transparent b--black-20 pv3 ph3 ba w-100" type="text" aria-describedby="pass-desc">
  </form>
</div>
```
## Input example

```html|plain
<div class="flex flex-wrap pa4">
  <form class="pv4 pr3-ns black-80 w-100 w-50-ns fl">
    <label for="name" class="f6 b db mb2">Name <span class="normal black-60">(optional)</span></label>
    <input id="name" class="mb2 input-reset bg-transparent b--black-20 pv3 ph3 ba w-100" type="text" aria-describedby="name-desc">
    <small id="name-desc" class="f6 black-60 db mb2">Default form</small>
  </form>

  <form class="pv4 pl3-ns black-80 w-100 w-50-ns fl">
    <label for="password" class="f6 b db mb2">Password</label>
    <input id="password" value="hunter2" class="mb2 input-reset bg-transparent b--c-red pv3 ph3 ba w-100" type="password" aria-describedby="pass-desc">
    <small id="password-desc" class="f6 c-red db mb2">Error message</small>
  </form>

  <form class="pv4 black-80 w-100 w-100-ns fl">
    <label for="password" class="f6 b db mb2">Placeholder example</label>
    <input id="password" placeholder="Placeholder" class="mb2 input-reset bg-transparent b--black-20 pv3 ph3 ba w-100" type="text" aria-describedby="pass-desc">
  </form>

  <form class="pv4 black-80 w-100 w-100-ns fl">
    <label for="password" class="f6 b db mb2">Full width form</label>
    <input id="password" class="mb2 input-reset bg-transparent b--black-20 pv3 ph3 ba w-100" type="text" aria-describedby="pass-desc">
  </form>
  <a href="javascript:;" class="pv3 ph4 bg-c-red white link dim dib">Log in</a>
</div>
```
