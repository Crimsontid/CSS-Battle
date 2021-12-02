# Battle #1 - Pilot Battle

## #3 - Push Button

[Link to the problem](https://cssbattle.dev/play/3)

![result](./images/3-push-button.png)

```html
<div class="wrapper">
  <div class="circle circle-outer"></div>
  <div class="circle circle-center"></div>
</div>
<style>
  body {
    background: #6592cf;
  }
  .wrapper {
    width: 300px;
    height: 150px;
    background: #243d83;
    margin: 75px auto;
    /* margin처리 */
    position: relative;
  }
  .circle {
    border-radius: 50%;
  }
  .circle-outer {
    position: absolute;
    left: 25px;
    top: -50px;
    width: 250px;
    height: 250px;
    background: transparent;
    box-sizing: border-box;
    border: 50px solid #6592cf;
    /* "border-width: 50px" */
  }
  .circle-center {
    position: absolute;
    width: 50px;
    height: 50px;
    left: 125px;
    top: 50px;
    background: #eeb850;
  }
</style>
```

```html
<div id="a">
  <div id="b">
    <div id="c">
      <div id="d"></div>
    </div>
  </div>
</div>

<style>
  body {
    margin: 0;
    background: #6592cf;
  }
  #a {
    position: absolute;
    top: 75px;
    left: 50px;
    width: 300px;
    height: 150px;
    background: #243d83;
  }
  #b {
    position: absolute;
    top: -50px;
    left: 25px;
    width: 250px;
    height: 250px;
    background: #6592cf;
    border-radius: 50%;
  }
  #c {
    position: absolute;
    top: 50px;
    left: 50px;
    width: 150px;
    height: 150px;
    background: #243d83;
    border-radius: 50%;
  }
  #d {
    position: absolute;
    top: 50px;
    left: 50px;
    width: 50px;
    height: 50px;
    background: #eeb850;
    border-radius: 50%;
  }
</style>
```
