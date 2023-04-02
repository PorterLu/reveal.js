## README
This is my reveal.js repo. In order to meet my need, I customize reveal.js for me.
### reveal.css
Append below code to reveal.css(which is refer to 蒋炎岩)
```css
.zoomed .reveal *,
.zoomed .reveal *:before,
.zoomed .reveal *:after {
  -webkit-backface-visibility: visible !important;
          backface-visibility: visible !important; }

.zoomed .reveal .progress,
.zoomed .reveal .controls {
  opacity: 0; }

.zoomed .reveal .roll span {
  background: none; }

.zoomed .reveal .roll span:after {
  visibility: hidden; }

.reveal .slides {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    margin: auto;
    text-align: center;
    pointer-events: none;
    overflow: visible;
    z-index: 1;
    perspective: 600px;
    perspective-origin: 50% 40%;
}

.reveal .slide-number {
  font-size: 26px;
  border-radius: 5px;
  background-color: rgba(0, 0, 0, .3);
}

.reveal .slides {
  border: 1.5px #ddd solid;
  border-radius: 7px;
  text-align: left;
  font-weight: 300;
}

.reveal h1, .reveal h2, .reveal h3, .reveal h4 {
  font-family: 'Lato', 'SimHei', 'STXihei', 'Droid Sans';
  font-weight: 400;
}
```
### simple.css
I adjust the font size.

### reveal init
I adjust property of vertical-center to false.
