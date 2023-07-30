<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>3-Day Forecast</title>
<style>

/********** Base styles **********/
* {
  box-sizing: border-box;
}
h1 {
  margin-bottom: 15px;
}

.box1 p, .box2 p, .box3 p {
  border: 1px solid black;
  background-color: #A52A2A;
  width: 90%;
  height: 150px;
  margin-right: auto;
  margin-left: auto;
  font-family: Helvetica;
  color: white;
  display: flex;
  align-items: flex-start;
  justify-content: flex-end;
  padding: 10px;
}

.box1 p span, .box2 p span, .box3 p span {
  background-color: #5AA52A;
  padding: 2px 5px;
  border-radius: 5px;
}

.box2 p span {
  background-color: #2A5AA5;
}

.box3 p span {
  background-color: #a59d2a;
}

/* Simple Responsive Framework. */
.row {
  width: 100%;
  display: flex;
  justify-content: flex-end;
  align-items: flex-start;
  flex-wrap: wrap;
}

.col {
  border: 1px solid green;
  box-sizing: border-box;
  margin: 10px;
}

/********** Large devices only **********/
@media (min-width: 1200px) {
  .col {
    width: 33.33%;
  }
}

/********** Medium devices only **********/
@media (min-width: 992px) and (max-width: 1199px) {
  .col {
    width: 33.33%;
  }
}

/********** Small devices only **********/
@media (max-width: 991px) {
  .col {
    width: 90%;
  }
}

</style>
</head>
<body>
<h1>3-Day Forecast</h1>

<div class="row">
  <div class="col box1"><p><span>Item 1</span></p></div>
  <div class="col box2"><p><span>Item 2</span></p></div>
  <div class="col box3"><p><span>Item 3</span></p></div>
</div>

</body>
</html>
