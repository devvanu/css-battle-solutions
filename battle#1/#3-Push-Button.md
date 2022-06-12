# Target #3- Push Button

### Output & Target:

<img src="https://raw.githubusercontent.com/devvanu/hosted-assets/main/css-battles/target3-Push-button.JPG" width="600">

### Code:

```HTML
<div class="box" id="box1"></div>
<div class="clip" id="clip1"></div>
<div class="box" id="box2"></div>
<div class="clip" id="clip2"></div>
<div class="circle">
  <div id="inner-circle"></div>
</div>
<style>
  body{
    background: #6592CF;
  }
  div{
    position: absolute;
  }
  .box{
    background: #243D83;
    width: 50px;
    height: 150px;
  }
  #box1 {
    top: 75px; left: 50px;
  }
  #box2{
    top: 75px; left: 300px;
  }
  .clip{
    background: #6592CF;
    width: 100px;
    height: 175px;
    border-radius: 50%;
  }
  #clip1{
    top: 60px; left: 75px;
  }
  #clip2{
    top: 60px; left: 225px;
  }
  .circle{
    background: #243D83;
    width: 150px;
    height: 150px;
    top: 75px; left: 125px;
    border-radius: 50%;
  }
  #inner-circle{
    background: #EEB850;
    height: 50px;
    width: 50px;
    top: 50px; left: 50px;
    border-radius: 50%;
  }
</style>
```
