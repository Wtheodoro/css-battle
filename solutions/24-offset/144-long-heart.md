# Battle #24 - Offset

## #144 - Long Heart

[Challenge link](https://cssbattle.dev/play/144)

![result](./images/144-long-heart.png)

```html
<div class="vertical" />
<div class="horizontal" />
<div class="corner" />
<div class="anti-corner" />
<style>
  body {
    background: #62306d;
  }

  div {
    position: absolute;
    bottom: 0;
    left: 0;
    background: #f7ec7d;
  }

  .vertical {
    width: 75px;
    height: 200px;
    border-radius: 37.5px 37.5px 0 0;
  }

  .horizontal {
    width: 200px;
    height: 75px;
    border-radius: 0 37.5px 37.5px 0;
  }

  .corner {
    bottom: 75px;
    left: 75px;
    width: 50px;
    height: 50px;
  }

  .anti-corner {
    bottom: 0;
    left: 0;
    width: 50px;
    height: 50px;
    background: #62306d;
    border-radius: 0 0 0 50%;
  }
</style>
```
