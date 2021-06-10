# III-4-Ahora-trabajaremos-con-la-apariencia-de-los-elementos
@import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');

.wrapper {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5px;
  font-family: 'Lato', sans-serif;
  width: 550px;
}

.container {
  background: turquoise;
  width: 180px;
  height: 180px;
}

.element {
  width: 60px;
  height: 60px;
  text-align: center;
  padding-top: 10px;
  box-sizing: border-box;
}

.element1 {
  @extend .element;
  background: papayawhip;
  width:50px;
   height:50px;
  -webkit-border-radius: 50px 50px 50px 50px ;
    position: absolute;
  margin: auto;
   width:50px;
    height:50px;
    position:relative;
}

.element2 {
  @extend .element;
  background: pink;
  width:80px;
   height:80px;
  -webkit-border-radius: 80px 80px 80px 80px ;
    position: absolute;
  margin: auto;
   width:60px;
    height:60px;
    position:relative;
}

.element3 {
  @extend .element;
  background: lightcyan;
  width:90px;
   height:90px;
  -webkit-border-radius: 90px 90px 90px 90px ;
    position: absolute;
  margin: auto;
   width:50px;
    height:50px;
    position:relative;
}

.container1 {
  @extend .container;
  display: flex;
  width: 180px;
  height: 180px;
  border-radius: 100%;
  // justify-content: ;
  // align-items: ;
}

.container2 {
  @extend .container;
  display: flex;
  width: 180px;
  height: 180px;
  border-radius: 100%;
  // justify-content: ;
  // align-items: ;
}

.container3 {
  @extend .container;
  display: flex;
  width: 180px;
  height: 180px;
  border-radius: 100%;
  background: red;
  // justify-content: ;
  // align-items: ;
}

.container4 {
  @extend .container;
  display: flex;
  width: 180px;
  height: 180px;
  border-radius: 100%;
  // justify-content: ;
  // align-items: ;
}

.container5 {
  @extend .container;
  display: flex;
  width: 180px;
  height: 180px;
   background: red;
  border-radius: 100%;
  // justify-content: ;
  // align-items: ;
}

.container6 {
  @extend .container;
  display: flex;
  width: 180px;
  height: 180px;
  border-radius: 100%;
  // justify-content: ;
  // align-items: ;
}

.container7 {
  @extend .container;
  display: flex;
  width: 180px;
  height: 180px;
  border-radius: 100%;
   background: red;
  // justify-content: ;
  // align-items: ;
}

.container8 {
  @extend .container;
  display: flex;
  width: 180px;
  height: 180px;
  border-radius: 100%;
  // justify-content: ;
  // align-items: ;
}

.container9 {
  @extend .container;
  display: flex;
  width: 180px;
  height: 180px;
  border-radius: 100%;
  // justify-content: ;
  // align-items: ;
}
