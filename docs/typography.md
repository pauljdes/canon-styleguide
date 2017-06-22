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


```html
<pre class="mt4">.f-headline</pre>
<div class="f-headline lh-solid tungsten">Headline</div>

<pre class="mt4">.f-subheadline</pre>
<div class="f-subheadline lh-title tungsten">Subheadline</div>

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
```


## Typography example

```html
<div class="measure center mv4">
  <div class="f-subheadline lh-solid tungsten mb4">Capture more light</div>
  <div class="f4 mb4 lh-copy">For premium results, Canon’s PowerShot G series cameras have a 1.0-type sensor with a light-sensitive area over 4 times larger than conventional compacts.</div>
  <p class="lh-copy">Enjoy complete creative freedom, from composition to editing. Our large sensor compacts offer customisable controls that give immediate access to useful functions, plus advanced features like RAW file support and built-in optical ND filter.</p>
</div>
```
