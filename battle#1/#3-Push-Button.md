# Target #3- Push Button

### #2 My Output & Target (2nd Attempt): 
<img src="https://raw.githubusercontent.com/devvanu/hosted-assets/main/css-battles/target3-Push-button1.JPG" width="600">

### Code:
*(Box-shadow and Border in circle class has made huge a difference- took help from internet 😆)*
```HTML
<div class="rect"></div>
<div class="circle"></div>
<style>
  body{
    background: #6592CF;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .rect{
    background: #243D83;
    width: 300px;
    height: 150px;
  }
  .circle{
    position: absolute;
    background: #EEB850;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    box-shadow: 0 0 0 50px #6592CF;
    border: 50px solid #243D83;
}
</style>
```


### #1 My Output & Target (1st Attempt):
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
