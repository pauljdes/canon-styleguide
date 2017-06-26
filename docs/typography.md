Canons typographical workhorse Gotham must be used throughout the all of Canons digital and print media. The recently introduced supplemental font Tungsten can be used in marketing context, but also in UI elements that need extra emphasis. Please refer below for the font sizes that may be used.

<!-- #### Gotham Book Used in body copy and smaller headings
```type
{
  "headings": [24,20,16,14,12],
  "font": "gotham-book",
  "weight": 100,
  "color": "#000"
}
``` -->

<!-- #### Gotham Bold — Used in heading
```type
{
  "headings": [48,36],
  "font": "gotham-bold",
  "weight": 100,
  "color": "#000"
}
``` -->

<!-- #### Tungsten Semibold — Only to be used on H1 and H2 in marketing context
```type|kern,smoothen,single
{
    "headings": [88, 64],
    "color": "#000",
    "font": "tungsten",
    "textTransform" : "uppercase"
}
``` -->


## Typographical ratio


```html|plain
<div class="cf pa5">

  <div class="w-50 fl">
    <pre class="mt4">.f-headline</pre>
    <div class="f-headline lh-solid tungsten">Headline</div>

    <pre class="mt4">.f-subheadline</pre>
    <div class="f-subheadline lh-title tungsten">Subheadline</div>
  </div>

  <div class="w-50 fl">
    <pre class="mt4">.f1</pre>
    <div class="f1">Display 1</div>

    <pre class="mt4">.f2</pre>
    <div class="f2">Display 2</div>

    <pre class="mt4">.f3</pre>
    <div class="f3">Display 3</div>

    <pre class="mt4">.f4</pre>
    <div class="f4">Heading 4</div>

    <pre class="mt4">.f5</pre>
    <div class="f5">Heading 5</div>

    <pre class="mt4">.f6</pre>
    <div class="f6">Heading 6</div>

    <pre class="mt4">.f7</pre>
    <p class="f7">Heading 7</p>
  </div>

</div>
```


## Typography example

```html|plain
<header class="dt w-100">
  <div style="background:url(assets/images/genericimage.jpg) no-repeat center right;background-size: cover;" class="dtc v-mid cover">
    <div class="pa4 pa5-ns">
      <h1 class="f2 f-subheadline-l tungsten white lh-title fw9 ma0">A Night Taking Photos at San Francisco’s Spooky Ruins of the Sutro Baths</h1>
      <h2 class="f4 fw6 white ma0 mt3">A story by Nancy Drew</h2>
    </div>
  </div>
</header>
<div class="ph3 ph4-m ph5-l pv4">
  <div class="cf">
    <p class="f7 tc ttu tracked center">Cameras</p>
    <div class="f1 f-headline-l lh-solid tungsten mb4 tc center">Premium</div>
    <div class="f4 mb4 lh-copy tc center measure-wide">For premium results, Canon’s PowerShot G series cameras have a 1.0-type sensor with a light-sensitive area over 4 times larger than conventional compacts.</div>

  </div>
  <div class="flex flex-column flex-row-ns">
    <p class="w-50-ns mr3-ns fl lh-copy">What you produce changes from day to day. So you need tools that are versatile enough to tackle any job, and that can handle the most challenging requests for customisation and personalisation. With our innovative UV flatbed, finishing and 3D printing technology, you can not only meet customer demand with ease, but attract more business by developing exciting new applications.</p>
    <p class="w-50-ns ml3-ns fl lh-copy">Enjoy complete creative freedom, from composition to editing. Our large sensor compacts offer customisable controls that give immediate access to useful functions, plus advanced features like RAW file support and built-in optical ND filter.</p>
  </div>
</div>

<article class="flex flex-column flex-row-ns ph3 ph4-m ph5-l pv4">
  <header class="w-50-ns mr3-ns fl lh-copy">
    <h1 class="tungsten f2 f-subheadline-l lh-title fw9 mb3 mt0 pt4 bt bw2">
      Type
    </h1>
    <div class="f4 lh-copy">
      An excerpt from the Form of the Book by Jan Tschichold
    </div>
    <div class="f7 ttu tracked mt3">Sometime before 1967</div>
  </header>
  <div class="w-50-ns ml3-ns fl lh-copy">
    <p class="f5 lh-copy measure mt0-ns">
      TYPOGRAPHY, even when poorly executed, can never be taken for granted;
      nor is it ever accidental. Indeed, beauti- fully typeset pages are always
      the result of long experience. Now and then they even attain the rank of
      great artistic achievement. But the art of typesetting stands apart from
      ex- pressive artwork, because the appeal is not limited to a small
      circle. It is open to everyone's critical judgment, and nowhere does this
      judgment carry more weight. Typography that can- not be read by everybody
      is useless. Even for someone who constantly ponders matters of
      readability and legibility, it is difficult to determine whether
      something can be read with ease, but the average reader will rebel at
      once when the type is too small or otherwise irritates the eye; both are
      signs of a certain illegibility already.
    </p>
    <p class="f5 lh-copy measure">
      All typography consists of letters. These appear either in the form of a
      smoothly running sentence or as an assembly of lines, which may even have
      contrasting shapes. Good typog- raphy begins, and this is no minor
      matter, with the typeset- ting of a single line of text in a book or a
      newspaper. Using exactly the same typeface, it is possible to create either
      a pleasant line, easily read, or an onerous one. Spacing, if it is too wide
      or too compressed, will spoil almost any typeface.
    </p>
  </div>
</article>
```
