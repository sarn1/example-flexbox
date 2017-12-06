# example-flexbox
#### Examples using Flexbox
https://webdesign.tutsplus.com/courses/css-flexbox-essentials

**sample website**
https://codepen.io/sarn1/pen/yPWKNr

**thai flag**
https://codepen.io/sarn1/pen/GOadma

**Notes**
- Vendor prefix - "autoprefixer" available for Brackets 
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
- `flex`

![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image04.jpg)

**site03**
https://codepen.io/sarn1/pen/OOYgwr
- `flex-direction`

![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image05.jpg)

**site04**
https://codepen.io/sarn1/pen/QORgJL
- `order`

![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image06.jpg)

**site05**
https://codepen.io/sarn1/pen/pdmrzg
- `flex-wrap`
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image07.jpg)

![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image08.jpg)

**site06**
https://codepen.io/sarn1/pen/xPNpRY
- `flex-flow`
- `flex-content`
    - center - centers the items
    - space-around - centers the items but have spacing on the ends
    - space-between - centers the items but not spacing on the ends
    - flex-start - flush right
    - flex-end - flush to the right
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image09.jpg)
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image09-2.jpg)
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image09-3.jpg)
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image09-4.jpg)

**site07**
https://codepen.io/sarn1/pen/mqYpvd
- Same as site06 but by row.
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image10.jpg)

**site08**
https://codepen.io/sarn1/pen/aVrEeQ
- `align-content` which is similar to `justify-content` and it deals with column and rows.
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image11.jpg)

**site09**
https://codepen.io/sarn1/pen/BmeYwZ
- `align-items`
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image12.jpg)
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image12-2.jpg)
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image12-3.jpg)
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image12-4.jpg)

**site10**
https://codepen.io/sarn1/pen/WXBMmy
- `align-self`
![alt text](https://github.com/sarn1/example-flexbox/blob/master/readme-images/image13.jpg)


