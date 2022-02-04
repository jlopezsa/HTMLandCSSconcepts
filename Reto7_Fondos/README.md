# Introduction (index_reto7.html and styles_reto7.css files)

Challenge

<img src="./figuresReadme/challenge_7_make_it_real_html_fondos.jpg" width="500"/>

Answer

<img src="./figuresReadme/challenge_6_answer_make_it_real_html_cajas.jpg" width="400"/>

# Background propesties (index.html and styles.css files)

```css
.background{
    width: 100%;
    height: 500px;
    background-color: blueviolet;
    background-image: url(./figuresReadme/world-comm_640x453.png);
}
```
<img src="./figuresReadme/img_background_repeat.jpg" width="400"/>

```css
.background{
    width: 100%;
    height: 500px;
    background-color: blueviolet;
    background-image: url(./figuresReadme/world-comm_640x453.png);
    background-repeat: no-repeat;
}
```
<img src="./figuresReadme/img_background_no_repeat.jpg" width="400"/>

```css
.background{
    width: 100%;
    height: 500px;
    background-color: blueviolet;
    background-image: url(./figuresReadme/world-comm_640x453.png);
    background-position: 50% 50%;
}
```
<img src="./figuresReadme/img_background_no_repeat_centering.jpg" width="400"/>

```css
.background{
    width: 100%;
    height: 500px;
    background-color: blueviolet;
    background-image: url(./figuresReadme/world-comm_640x453.png);
    background-repeat: no-repeat;
    background-position: 50% 50%;
    background-size: 100% 100%; /*x(width) - y (heigh), units also may be cm, mm, px*/
}
```
<img src="./figuresReadme/img_background_no_repeat_same_size_box.jpg" width="400"/>

## background-attachment

```css
.background{
    width: 100%;
    height: 500px;
    background-color: blueviolet;
    background-image: url(./figuresReadme/world-comm_640x453.png);
    background-repeat: no-repeat;
    background-position: 50% 50%;
    background-size: 100% 100%; /*x(width) - y (heigh), units also may be cm, mm, px*/
    background-attachment: fixed;
}
```
<img src="./figuresReadme/img_background_scroll_efec_1.jpg" width="400"/>
<img src="./figuresReadme/img_background_scroll_efec_2.jpg" width="400"/>
