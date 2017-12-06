# example-flexbox
#### Examples using Flexbox

CSS Flexbox
https://webdesign.tutsplus.com/courses/css-flexbox-essentials
 
- https://caniuse.com/#feat=flexbox

**site01**
https://codepen.io/sarn1/pen/ZaNyxb
```css
.container {
    background-color: #555;
    width: 800px;
    height: 400px;
    margin: 0 auto;
}

.item { }

.item1 { background-color: red; }
.item2 { background-color: blue; }
.item3 { background-color: green; }
.item4 { background-color: orange; }
```
![alt text](image01.jpg)

```css
.container {
    background-color: #555;
    width: 800px;
    height: 400px;
    margin: 0 auto;
    display: flex; /* look */
}

.item { }

.item1 { background-color: red; }
.item2 { background-color: blue; }
.item3 { background-color: green; }
.item4 { background-color: orange; }
```
![alt text](image02.jpg)

```css
.container {
    background-color: #555;
    width: 800px;
    height: 400px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
}

.item {
    flex-basis: 150px; /* default, like width: 150px */
    flex-grow: 1; /* grows to relative to the rest of the item, thus fills parent */
}

/* shorthand of the above lines 
.item { flex: 1 1 150px; }
 */

.item1 { background-color: red; }
.item2 { background-color: blue; }
.item3 { background-color: green; }
.item4 { background-color: orange; }
```
![alt text](image03.jpg)

**site02**
https://codepen.io/sarn1/pen/pdmwVo
- flex
![alt text](image04.jpg)

**site03**
https://codepen.io/sarn1/pen/OOYgwr
- flex-direction
![alt text](image05.jpg)

**site04**
https://codepen.io/sarn1/pen/QORgJL
- order
![alt text](image06.jpg)

**site05**
- xx
https://codepen.io/sarn1/pen/pdmrzg
![alt text](image07.jpg)

