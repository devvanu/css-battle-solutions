# Target #6- Missing Slice

### Output & Target:

<img src="https://user-images.githubusercontent.com/93486013/180926061-dc8d5093-19d5-4884-8095-70df46daef0a.PNG" alt="target6- missing slice" width="600">

### Code:

```HTML
<div id="box1"></div>
<div id="box2"></div>
<div id="box3"></div>
<style>
  body{
    margin: 0;
    background: #E3516E;
  }
  div {
    width: 100px;
    height: 100px;
    position: absolute;
    border-top-left-radius: 100%;
  }
  #box1{
    background: #51B5A9;
    top: 50px; left: 100px;
  }
  #box2{
    background: #FADE8B;
    top: 50px; left: 200px;
    transform: rotate(90deg);
  }
  #box3{
    background: #F7F3D7;
    top: 150px; left: 100px;
    transform: rotate(-90deg);
  }
</style>
```
