# Battle #24 - Offset

## #146 - Streaks

[Challenge link](https://cssbattle.dev/play/146)

![result](./images/146-streaks.png)

```html
<div class="wrapper">
  <div class="track"></div>
  <div class="track"></div>
</div>
<style>
  body {
    background: #998235;
  }
  .wrapper {
    position: absolute;
    bottom: 0;
    right: -115px;
    transform: rotate(135deg);
  }
  .track {
    width: 350px;
    height: 50px;
    background: linear-gradient(to top, #fcbe5c 50%, #0b2429 50%);
  }
  .track + .track {
    margin-top: 25px;
  }
</style>
```
