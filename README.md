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
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image01.jpg)

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
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image02.jpg)

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
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image03.jpg)

**site02**
https://codepen.io/sarn1/pen/pdmwVo
- flex

![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image04.jpg)

**site03**
https://codepen.io/sarn1/pen/OOYgwr
- flex-direction

![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image05.JPG)

**site04**
https://codepen.io/sarn1/pen/QORgJL
- order

![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image06.JPG)

**site05**
https://codepen.io/sarn1/pen/pdmrzg
- xx

![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image07.jpg)

