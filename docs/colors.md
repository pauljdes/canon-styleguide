```html|plain,span-4,no-source
<div class="f4 mb4 lh-copy">
The colours represent the brand. As showed the most important colour is the Canon Red, sourced from the logo. To complement this colour we've picked colours that help users complete their tasks.
</div>
```




## Brand & Digital colours


```color-palette|span-2
colors:
   - {name: "Canon Red Light", value: "#f3a5ba"}
   - {name: "Canon Red Lighten", value: "#ff0000"}
   - {name: "Canon Red", value: "#cc0000"}
   - {name: "Canon Red Darken", value: "#7a1000"}
   - {name: "Canon Red Dark", value: "#140300"}
```
```color-palette|span-2
colors:

   - {name: "Link Blue Light", value: "#def2f6"}
   - {name: "Link Blue Lighten", value: "#43aaed"}
   - {name: "Link Blue", value: "#1e8cea"}
   - {name: "Link Blue Darken", value: "#104da7"}
   - {name: "Link Blue Dark", value: "#082248"}
```
```color-palette|span-2
colors:

   - {name: "Canon Green Light", value: "#b7deb7"}
   - {name: "Canon Green Lighten", value: "#2fc34e"}
   - {name: "Canon Green", value: "#27a249"}
   - {name: "Canon Green Darken ", value: "#176035"}
   - {name: "Canon Green Dark", value: "#040e08"}
```
## Monotone colours
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

// color variable map

@function color-palette($color) {
  $map: (
     light: desaturate(adjust-hue(lighten($color, 40%), -16%), 24%),
     lighter: adjust-hue(lighten($color, 8%), -4%),
     base: $color,
     darker: adjust-hue(darken($color, 16%), 8%),
     dark: desaturate(adjust-hue(darken($color, 36%), 8%), 4%)
  );
  @return $map;
}

$colors: (
  canon-red: color-palette($canon-red),
  canon-blue: color-palette($canon-blue),
  canon-green: color-palette($canon-green)
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
.c-red { background: color(canon-red, base); }
.c-red-darker { background: color(canon-red, darker); }
.c-red-dark { background: color(canon-red, dark); }

.c-blue-light { background: color(canon-blue, light); }
.c-blue-lighter { background: color(canon-blue, lighter); }
.c-blue { background: color(canon-blue, base); }
.c-blue-darker { background: color(canon-blue, darker); }
.c-blue-dark { background: color(canon-blue, dark); }

.c-green-light { background: color(canon-green, light); }
.c-green-lighter { background: color(canon-green, lighter); }
.c-green { background: color(canon-green, base); }
.c-green-darker { background: color(canon-green, darker); }
.c-green-dark { background: color(canon-green, dark); }

[class^='c-'] {
  height: 60px;
  width: 300px;
  display:inline-block;
  float:left;
}
```
