# Target #6- Missing Slice

### Output & Target (Attempt-2):

<img src="https://user-images.githubusercontent.com/93486013/180930439-48e5bc69-a486-49c9-8e0f-9c33cb8cc88b.PNG" alt="target6- missing slice" width="600">

### Code:

```HTML
<div id="circle"></div>
<style>
  body{
    background: #E3516E;    
  }
  #circle{
    background: conic-gradient(#FADE8B 90deg, #E3516E 90deg 180deg, #F7F3D7 180deg 270deg, #51B5A9 270deg);
    position: absolute;
    top: 50px; left: 100px;
    width: 200px; height: 200px;
    border-radius: 50%;
  }
</style>
```


### Output & Target (Attempt-1):

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
