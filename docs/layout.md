Canon uses a grid logic to help keep things tidy.

It's quite simple really. When designing keep in mind: **multiples of 4**.
```html|plain,no-source
<div class="flex flex-column">
  <pre class="ma0 pb1">4 + 4  = <span class="shadow-1 pv0 br1 bg-white ph1">8</span> </pre>
  <pre class="ma0 pb1">4 + 8  = <span class="shadow-1 pv0 br1 bg-white ph1">12</span></pre>
  <pre class="ma0 pb1">4 + 12 = <span class="shadow-1 pv0 br1 bg-white ph1">16</span></pre>
</div>

```

And the padding and margin scale ratio is based on the *2^n* ratio.



```html|plain,no-source
<div class="dib bg-measure b--black-20 ba w6 h6 flex items-center justify-center">
  <span class="absolute top-0 right-0 f7 c-red right-1 top-1">.32rem</span>
  <div class="pa6 b--black-20 ba absolute flex items-center justify-center">
    <span class="absolute top-0 right-0 f7 c-red right--1 top--1">.16rem</span>
     <div class="pa5 b--black-20 ba absolute flex items-center justify-center">
       <span class="absolute top-0 right-0 f7 c-red right--1 top--1">8rem</span>
       <div class=" pa4 b--black-20 ba absolute flex items-center justify-center">
         <span class="absolute top-0 right-0 f7 c-red right--1 top--1">4rem</span>
         <div class=" pa3 b--black-20 ba absolute flex items-center justify-center">
           <span class="absolute top-0 right-0 f7 c-red right--1 top--1">2rem</span>
           <div class=" pa2 b--black-20 ba absolute flex items-center justify-center">
             <div class=" pa1 b--black-20 ba absolute flex items-center justify-center">
             </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```

Below you'll find some common units that can be used for either; **padding** or **margin** or **widths** or **heights**.
**Font sizes** as well.


```html|plain,no-source
<span class="f2 f1-ns c-red flex flex-wrap">
  <span class="pa3 shadow-1 mb2 mr2 dib">4 <span class="f7">Units</span></span>
  <span class="pa3 shadow-1 mb2 mr2 dib">8 <span class="f7">Units</span></span>
  <span class="pa3 shadow-1 mb2 mr2 dib">12 <span class="f7">Units</span></span>
  <span class="pa3 shadow-1 mb2 mr2 dib">16 <span class="f7">Units</span></span>
  <span class="pa3 shadow-1 mb2 mr2 dib">20 <span class="f7">Units</span></span>
  <span class="pa3 shadow-1 mb2 mr2 dib">24 <span class="f7">Units</span></span>
  <span class="pa3 shadow-1 mb2 mr2 dib">28 <span class="f7">Units</span></span>
  <span class="pa3 shadow-1 mb2 mr2 dib">32 <span class="f7">Units</span></span>
  <span class="pa3 shadow-1 mb2 mr2 dib">36 <span class="f7">Units</span></span>
  <span class="pa3 shadow-1 mb2 mr2 dib">40 <span class="f7">Units</span></span>
  <span class="pa3 shadow-1 mb2 mr2 dib">44 <span class="f7">Units</span></span>
</span>
```


<!-- ```html|plain,no-source
<div class="dib w5 h5 bg-measure-grid">
 <div class="cf bg-c-red o-20 w-100">
   <div class="pa3">
     <div class="fl w3 pa1 bg-white"></div>
     <div class="fr w1 pa1 bg-white"></div>
   </div>
 </div>
 <div class="ph3 pt3">
   <div class="h1 w3 pa2 bg-c-red o-20"></div>
 </div>
 <div class="pa2 cf flex flex-wrap">
   <div class="fl w-100 pa2 o-20">
     <div class="bg-c-red h3">

     </div>
   </div>
   <div class="fl w-50 ph2 o-20">
     <div class="bg-c-red h3">
     </div>
   </div>
   <div class="fl w-50 ph2 o-20">
     <div class="bg-c-red h3">

     </div>
   </div>
 </div>
</div>
``` -->
