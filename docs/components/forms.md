## Input single

```html
<div class="flex flex-wrap pa0 pa4-ns">
  <form class="w-100">
    <section class="pv2 black-80 w-100 fl">
      <label for="password" class="f6 b db mb2">Enter your name</label>
      <div class="shadow-hover">
        <input id="password" placeholder="Name" class="mb2 input-reset bg-transparent b--black-20 pv3 ph1 bt-0 bl-0 br-0 bw1 bb w-100" type="text" aria-describedby="pass-desc">
      </div>
    </section>
  </form>
</div>
```
## Input example

```html
<div >
  <form class="flex flex-wrap pa0 pa4-ns">
    <section class="pv3 pr3-ns black-80 w-100 w-50-ns fl">
      <label for="name" class="f6 b db mb2">Name <span class="normal black-60">(optional)</span></label>
      <input id="name" class="mb2 input-reset bg-transparent b--black-20 pv3 ph1 bt-0 bl-0 br-0 bw1 bb w-100" type="text" aria-describedby="name-desc">
      <small id="name-desc" class="f6 black-60 db mb2">Default form</small>
    </section>

    <section class="pv3 pl3-ns black-80 w-100 w-50-ns fl">
      <label for="password" class="f6 b db mb2">Password</label>
      <input id="password" value="hunter2" class="mb2 input-reset bg-transparent b--c-red pv3 ph1 bt-0 bl-0 br-0 bw1 bb w-100" type="password" aria-describedby="pass-desc">
      <small id="password-desc" class="f6 c-red db mb2">Error message</small>
    </section>

    <section class="pv3 black-80 w-100 w-100-ns fl">
      <label for="password" class="f6 b db mb2">Placeholder example</label>
      <input id="password" placeholder="Placeholder" class="mb2 input-reset bg-transparent b--black-20 pv3 ph1 bt-0 bl-0 br-0 bw1 bb w-100" type="text" aria-describedby="pass-desc">
    </section>

    <section class="pv3 black-80 w-100 w-100-ns fl">
      <label for="password" class="f6 b db mb2">Full width form</label>
      <input id="password" class="mb2 input-reset bg-transparent b--black-20 pv3 ph1 bt-0 bl-0 br-0 bw1 bb w-100" type="text" aria-describedby="pass-desc">
    </section>
    <a href="javascript:;" class="pv3 ph4 bg-c-blue white link dim dib">Log in</a>

  </form>

</div>
```


```html
<div class="flex flex-wrap pa0 pa4-ns">
  <form class="w-100">
    <fieldset class="mv3 bt bb-0 bl-0 br-0 bw1 b--black-20 b--solid">
      <legend class="f6">Title of fieldset</legend>
      <section class="pv3 pr3-ns black-80 w-100 w-50-ns fl">
        <label for="name" class="f6 b db mb2">Name <span class="normal black-60">(optional)</span></label>
        <input id="name" class="mb2 input-reset bg-transparent b--black-20 pv3 ph1 bt-0 bl-0 br-0 bw1 bb w-100" type="text" aria-describedby="name-desc">
        <small id="name-desc" class="f6 black-60 db mb2">Default form</small>
      </section>

      <section class="pv3 pl3-ns black-80 w-100 w-50-ns fl">
        <label for="password" class="f6 b db mb2">Password</label>
        <input id="password" value="hunter2" class="mb2 input-reset bg-transparent b--c-red pv3 ph1 bt-0 bl-0 br-0 bw1 bb w-100" type="password" aria-describedby="pass-desc">
        <small id="password-desc" class="f6 c-red db mb2">Error message</small>
      </section>
    </fieldset>

    <section class="pv3 black-80 w-100 w-100-ns fl">
      <label for="password" class="f6 b db mb2">Placeholder example</label>
      <input id="password" placeholder="Placeholder" class="mb2 input-reset bg-transparent b--black-20 pv3 ph1 bt-0 bl-0 br-0 bw1 bb w-100" type="text" aria-describedby="pass-desc">
    </section>

    <section class="pv3 black-80 w-100 w-100-ns fl">
      <label for="password" class="f6 b db mb2">Full width form</label>
      <input id="password" class="mb2 input-reset bg-transparent b--black-20 pv3 ph1 bt-0 bl-0 br-0 bw1 bb w-100" type="text" aria-describedby="pass-desc">
    </section>
  </form>
  <a href="javascript:;" class="pv3 ph4 bg-c-blue white link dim dib">Log in</a>
</div>
```
