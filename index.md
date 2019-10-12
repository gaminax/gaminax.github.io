Gaminax Home/

A Blog and a Description of some computing topics.

### [Computing Blog/](computingBlog/index.html)
- [2019-10-11-initial-post](computingBlog/2019-10-11-initial-post.html)


### [Computing/](computing/index.html )

#### [Editors/](computing/editors/index.html)
- [Emacs/](computing/editors/emacs/index.html)
- [Vim/ ](computing/editors/vim/index.html)

#### [Formatting/](computing/formatting/index.html)
- [AsciiDoc/](computing/formatting/asciidoc/index.html)
- [Rimu/](computing/formatting/rimu/index.html)

#### [Languages/](computing/languages/index.html)
- [JavaScript](computing/languages/javascript/index.html)

#### [Web/](computing/web/index.html)
- [SVG](computing/web/svg/index.html)

## Moon Flowers

<div>
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="400" height="100" viewBox="0 0 800 200" >
<defs>
<symbol id="sun" viewBox="0 0 20 20" >
<circle cx="10" cy="10" r="5" style="fill:yellow" />
</symbol>
<symbol id="flower" viewBox="0 0 20 20" >
<rect width="2" height="12" x="11" y="8" style="fill:brown;" />
<circle cx="10" cy="08" r="4" style="fill:green;" />
<circle cx="10" cy="08" r="2" style="fill:yellow;" />
</symbol>
<symbol id="flowerGrowing" viewBox="0 0 20 20" >

</symbol>
</defs>
<rect x="0" y="0" width="800" height="150" >
\\<animate attributeName="fill" begin="5s" dur="20s" values="#112; #224; #44f; #224; #112; #112;" fill="freeze" repeatDur="indefinite" />
</rect>
<rect x="0" y="150" width="800" height="50" style="fill:#660;" />
<use xlink:href="#sun" width="30" height="30" >
<animateMotion path="M-60 0 M -30 100 Q 400 -100 800 100 Q 1200 -100 1600 100" begin="10s" dur="20s" fill="freeze" repeatDur="indefinite" />
</use>
<use xlink:href="#flower" x="20" y="100" width="100" height="100" >
<animateTransform attributeType="XML"
    attributeName="transform" type="skewY"
    // from="30" to="45"
    values="30;60;30; 10; 30; 10; 10; 10; 10;"
    begin="2s" dur="20s" fill="freeze"
    repeatDur="indefinite" />
</use>
<use xlink:href="#flower" x="130" y="180" width="20" height="20" >
<animate attributeName="y" attributeType="XML"
    begin="10s" dur="20s"
    values="200;180;200"
    //from="200" to="180"
    fill="freeze" repeatDur="indefinite" />
</use>
<use xlink:href="#flower" x="20" y="80" width="20" height="20" >
<animate attributeName="y" attributeType="XML"
  // from="200" to="180"
  values="200;180;200"
  begin="0s" dur="20s" fill="freeze"
  repeatDur="indefinite" />
</use>
</svg>
</div>

## Formatting Method
As an experiment, these Github Pages have been entered directly on the website with the Github editor, and without the use of an offline page generator.

## Revisions
2019-10-12, 2019-10-11, 2019-10-10, 2016-03-15, 2016-03-10
