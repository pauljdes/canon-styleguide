```html|plain,span-4,no-source
<div class="f4 mb4 lh-copy">
The colours represent the brand. As showed the most important colour is the Canon Red, sourced from the logo. To complement this colour we've picked colours that help users complete their tasks.
</div>
```




## Brand & Digital colours

```html|plain
<span class="mr4 mb4 dib"><span class="bg-c-red white br-pill pv1 ph2">Red</span> for marketing.</span>
<span class="mr4 mb4 dib"><span class="bg-c-blue white br-pill pv1 ph2">Blue</span> for call-to-actions.</span>
<span class="mr4 mb4 dib"><span class="bg-c-green white br-pill pv1 ph2">Green</span> for purchases.</span>
```

```color-palette|span-2
colors:
   - {name: "Canon Red Light", value: "#ffdada"}
   - {name: "Canon Red Lighten", value: "#ff6075"}
   - {name: "Canon Red", value: "#cc0000"}
   - {name: "Canon Red Darken", value: "#830000"}
   - {name: "Canon Red Dark", value: "#390000"}
```
```color-palette|span-2
colors:

   - {name: "Link Blue Light", value: "#e4f1fc"}
   - {name: "Link Blue Lighten", value: "#87d3f8"}
   - {name: "Link Blue", value: "#1e8cea"}
   - {name: "Link Blue Darken", value: "#0e5a9b"}
   - {name: "Link Blue Dark", value: "#00284a"}
```
```color-palette|span-2
colors:

   - {name: "Canon Green Light", value: "#e1f8e7"}
   - {name: "Canon Green Lighten", value: "#74ea84"}
   - {name: "Canon Green", value: "#27a249"}
   - {name: "Canon Green Darken ", value: "#19682f"}
   - {name: "Canon Green Dark", value: "#003810"}
```
## UI colours
```color-palette|span-3
colors:
   - {name: "White", value: "#ffffff"}
   - {name: "Canon Near white", value: "#f6f6f6"}
   - {name: "Canon Off white", value: "#f6f7f1"}
   - {name: "Canon Light Grey", value: "#e2e7e8"}
   - {name: "Canon Silver", value: "#bbbbbb"}
   - {name: "Canon Grey", value: "#83868a"}
   - {name: "Canon Mid Grey", value: "#4B4F54"}
   - {name: "Canon Dark Grey", value: "#333333"}
   - {name: "Canon Near black", value: "#111111"}
   - {name: "Black", value: "#000000"}
```


## SASS code to generate new colours

```code
$canon-red : #cc0000;
$canon-blue : #1e8cea;
$canon-green : #27a249;
$canon-teal : #41bdbb;
$canon-purple : #5c369e;
$canon-yellow : #ecd340;


@function color-palette($color) {  
  $map: (
     light: scale-color($color, $lightness: 88%),
     lighter: adjust-hue(scale-color($color, $lightness: 48%, $saturation: 32%), -8%),
     base: $color,
     darker: adjust-hue(scale-color($color, $lightness: -36%), 0%),
     dark: scale-color($color, $lightness: -72%, $saturation: 100%)
  );
  @return $map;
}

$colors: (
  canon-red: color-palette($canon-red),
  canon-blue: color-palette($canon-blue),
  canon-green: color-palette($canon-green),
  canon-teal: color-palette($canon-teal),
  canon-purple: color-palette($canon-purple),
  canon-yellow: color-palette($canon-yellow)
);

// retrieve color from map ie. `color(primary, base)`
@function color($color-name, $color-variant:null) {
  // color variant is optional
  @if ($color-variant != null) {
    // map inception

    @return map-get(map-get($colors, $color-name), $color-variant);
  } @else {
    @return map-get(map-get($colors, $color-name), base);
  }
}

.c-red-light { background: color(canon-red, light); }
.c-red-lighter { background: color(canon-red, lighter); }
.c-red { background: color(canon-red); }
.c-red-darker { background: color(canon-red, darker); color:#fff;}
.c-red-dark { background: color(canon-red, dark); color:#fff;}

.c-blue-light { background: color(canon-blue, light); }
.c-blue-lighter { background: color(canon-blue, lighter); }
.c-blue { background: color(canon-blue); }
.c-blue-darker { background: color(canon-blue, darker); color:#fff;}
.c-blue-dark { background: color(canon-blue, dark); color:#fff;}

.c-green-light { background: color(canon-green, light); }
.c-green-lighter { background: color(canon-green, lighter); }
.c-green { background: color(canon-green); }
.c-green-darker { background: color(canon-green, darker); color:#fff;}
.c-green-dark { background: color(canon-green, dark); color:#fff;}

.c-teal-light { background: color(canon-teal, light); }
.c-teal-lighter { background: color(canon-teal, lighter); }
.c-teal { background: color(canon-teal); }
.c-teal-darker { background: color(canon-teal, darker); color:#fff;}
.c-teal-dark { background: color(canon-teal, dark); color:#fff;}

.c-purple-light { background: color(canon-purple, light); }
.c-purple-lighter { background: color(canon-purple, lighter); }
.c-purple { background: color(canon-purple); }
.c-purple-darker { background: color(canon-purple, darker); color:#fff;}
.c-purple-dark { background: color(canon-purple, dark); color:#fff;}

.c-yellow-light { background: color(canon-yellow, light); }
.c-yellow-lighter { background: color(canon-yellow, lighter); }
.c-yellow { background: color(canon-yellow); }
.c-yellow-darker { background: color(canon-yellow, darker); color:#fff;}
.c-yellow-dark { background: color(canon-yellow, dark); color:#fff;}


.columns {
  display:flex;
  flex-wrap: wrap;
}
.column {
  display:flex;
  flex-direction: column;
  margin-right: 24px;
}
[class^='c-'] {
  width: 160px;
  display:inline-block;
  padding: 24px;
  i {
    font-family: sans-serif;
    font-size: 16px;
    font-style: normal;
  }  
}
```
