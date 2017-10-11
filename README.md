# QTie
***

## The most minimalistic, responsive grid on the interwebz
Even works on IE8 (I hope)


### Kudos to André Schiemann


### How to use

```HTML
<!-- Responsive Grid -->
<div class="row">
	<div class="column grid-10"></div>
	<div class="column grid-2"></div>
</div>
```

```HTML
<!-- omit column class for non responsive grids -->
<div class="row">
       <div class="grid-10"></div>
       <div class="grid-2"></div>
</div>
```

```HTML
<!-- Center -->
<div class="row">
       <div class="grid-11 center column">
       <p>grid-11</p>
       </div>
</div>
```

```HTML
<!-- Responsive -->
<div class="row">
       <div class="grid-12 column medium-split-3"><p>grid-12</p></div>
       <div class="grid-11 column medium-split-3"><p>grid-11</p></div>
       <div class="grid-1 column medium-split-3"><p>grid-1</p></div>
                
       <div class="grid-10 column medium-split-3 small-split-2"><p>grid-10</p></div>
       <div class="grid-2 column medium-split-3 small-split-2"><p>grid-2</p></div>
                
       <div class="grid-9 column medium-split-3 small-split-2"><p>grid-9</p></div>
       <div class="grid-3 column medium-split-3 small-split-2"><p>grid-3</p></div>
                
       <div class="grid-8 column medium-split-3 small-split-2"><p>grid-8</p></div>
       <div class="grid-4 column medium-split-3 small-split-2"><p>grid-4</p></div>
         
       <!-- TABLET/MEDIUM WILL SPLIT TO 50% BY DEFAULT -->
       <div class="grid-7 column small-split-2"><p>grid-7</p></div>
       <div class="grid-5 column small-split-2"><p>grid-5</p></div>
                
       <div class="grid-6 column split-2"><p>grid-6</p></div>
       <div class="grid-6 column split-2"><p>grid-6</p></div>
</div>
```
