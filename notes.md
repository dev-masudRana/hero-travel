1. Centering text with position: absolute;

<div class="container">
  <div class="text">Your text</div>
</div>

<!-- CSS -->

.container {
position: relative;
width: 400px; /** optional **/
height: 400px; /** optional **/
}

.text {
position: absolute;
top: 0;
width: 100%;
height: 100%;

display: flex;
align-items: center;
justify-content: center;
}
