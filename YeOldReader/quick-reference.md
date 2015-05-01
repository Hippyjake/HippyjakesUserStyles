# YeOldReader userstyles.org
## Quick reference for YeOldReader Theme

```CSS
Color Options
/*[[highlight]]*/
/*[[background]]*/
/*[[button-bg]]*/
/*[[textcolor]]*/
/*[[labletext]]*/
Blockquote Options
/*[[blockquote]]*/
   stock
   fancy
Remove Social Options
/*[[sociallinks]]*/
   True
   False
Hover Top Menu-Search bar
/*[[hovertop]]*/
```

## Default Option Values
|Name|Value|
|:---|:----|
|highlight |#0099CC|
|background|#2d2d2d|
|button-bg |#636363|
|textcolor |#f1f1f1|
|labletext |#ffffff|
|blockquote |stock|
|sociallinks |visible|

# Optional CSS snippets

## Blockquote styles

### Fancy blockquote
```css
.post blockquote {
    background-color: rgba(0, 0, 0, .3);
    width: 85%;
    quotes: "\201C" "\201D" "\2018" "\2019"
}

.well blockquote {
    border-color: transparent;
    border-radius: 4px;
    padding: 15px;
}

blockquote:before {
    color: /*[[highlight]]*/;
    content: open-quote;
    font-size: 5em;
    line-height: .1em;
    margin-right: .25em;
    vertical-align: -.4em
}

blockquote:after {
    color: /*[[highlight]]*/;
    content: close-quote;
    font-size: 5em;
    line-height: .1em;
    margin-left: .25em;
    vertical-align: -.5em
}

blockquote p {
    display: inline
}
```
### Stock style blockquote
```css
.post blockquote {
    background-color: rgba(0, 0, 0, .3);
    width: 75%;
}

.well blockquote {
    padding: 15px;
    border-color: /*[[highlight]]*/;
}
```
## Remove Social Links

```css
.sidebar-nav > ul.nav-list:nth-child(1) {
    display: none;
    }
```
## Hide top Bar Show on hover

```CSS
div.navbar-fixed-top:not(:hover) {
    margin-top: -50px !important
}

div.container-fluid {
    margin-top: -54px !important
}
```