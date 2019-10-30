# task3.1
assignment 3
<!DOCTYPE html>
<html>
<head>
    <style>
/* Write your code here */
/*CSS*/
.letters{
  display:flex;
  justify-content:space-between;
  background:white;

  color:white;
  font-size:45px;
  border:1px solid red;
}

.letters > div{
  background-color: brown;
  border-radius:30px;
  width:55px;
  height:55px;
  shape-outside:circle();
  margin:5px;
  text-align:center;
}

@media (max-width: 500px) {
 article{
  margin: 0 500px;
 }
}
</style>

/*HTML*/
</head>
<body>
<div class="letters">
    <div>A</div>
    <div>B</div>
    <div>C</div>
    <div>D</div>
    <div>E</div>
    <div>F</div>
    <div>G</div>
    <div>H</div>
    <div>I</div>
    <div>J</div>
    <div>K</div>
    <div>L</div>
</div>
</body>
</html>
