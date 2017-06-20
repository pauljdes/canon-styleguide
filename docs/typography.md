Canons typographical workhorse Gotham must be used throughout the all of Canons digital and print media. The recently introduced supplemental font Tungsten can be used in marketing context, but also in UI elements that need extra emphasis. Please refer below for the font sizes that may be used.

#### Gotham Medium — Used in body copy and smaller headings
```type
{
  "headings": [24,20,16,14,12],
  "font": "gotham-medium",
  "weight": 500,
  "color": "#000"
}
```
#### Gotham Light — Used in heading
```type
{
  "headings": [48,36],
  "font": "gotham-light",
  "weight": 500,
  "color": "#000"
}
```

## Marketing typeface

#### Tungsten Semibold — Only to be used on H1 and H2 in marketing context
```type|kern,smoothen,single
{
    "headings": [88, 64],
    "color": "#000",
    "font": "tungsten",
    "textTransform" : "uppercase"
}
```


## code


```html
<div class="f-headline lh-solid tungsten">Hero header 1</div>
<div class="f-subheadline lh-title tungsten">Hero header 1</div>

<div class="f1"> Heading 1 </div>
<div class="f2">Heading 2</div>
<div class="f3">Heading 3</div>
<div class="f4">Heading 4</div>
<div class="f5">Heading 5</div>
<div class="f6">Heading 6</div>
<p class="f7">Heading 7</p>
```
