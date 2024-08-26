html, body {
  height: 100%;
  width: 100%;
}
.container {
  width: 640px;
  margin: 5em auto;
}

.box {
  width: 200px;
  height: 200px;
  background-color: #33f;
  -webkit-transition: background-color 2s;
  transition: background-color 2s;
}

.box:hover {
  background-color: #f33;
  /* what if transitions on hover? doesnt matter 
  -webkit-transition: background-color 2s;
  transition: background-color 2s;
  */
}

.box2{
  width: 200px;
  height: 200px;
  background-color: #33f;
}

.box2:hover{
  background-color: #f33;
}
.box3{
  /* each change divided by the duration time */
  transition-timing-function: steps(5, start);
}
.box,.box2{float: left; display:block;margin-right:10px;}

.box, .box2, .box3{
  line-height:200px;
  text-align: center;
  color: white;
  font-weight: bold;
  font-family: sans-serif;
}