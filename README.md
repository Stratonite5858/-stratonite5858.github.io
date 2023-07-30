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

body {
  font-family: 'Roboto', sans-serif;
  background: linear-gradient(to right, #F2709C, #FF9472);
  color: white;
}

h1 {
  margin-bottom: 15px;
  text-align: center;
}

.box1 p, .box2 p, .box3 p {
  border: 1px solid black;
  background-color: rgba(69, 137, 225, 0.8);
  width: 90%;
  height: 150px;
  margin-right: auto;
  margin-left: auto;
  color: black;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  padding: 10px;
  border-radius: 10px;
  
}

.box1 p span, .box2 p span, .box3 p span {
  align-self: flex-end;
  background-color: #5AA52A;
  padding: 2px 5px;
  border-radius: 5px;
}

.box2 p span {
  background-color: #2A5AA5;
}

.box3 p span {
  background-color: #A52A2A;
}

/* Simple Responsive Framework. */
.row {
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: flex-start;
  flex-wrap: wrap;
}

.col {
  border: 1px solid transparent;
  box-sizing: border-box;
  margin: 10px;
}

/********** Large devices only **********/
@media (min-width: 1200px) {
  .col {
    width: 30%;
  }
}

/********** Medium devices only **********/
@media (min-width: 992px) and (max-width: 1199px) {
  .col {
    width: 45%;
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
  <div class="col box1">
    <p>
      <span>Friday</span>
      <br/>
      Sunny with a high of 85°F.
    </p>
  </div>

  <div class="col box2">
    <p>
      <span>Saturday</span>
      <br/>
      Partly cloudy with a high of 78°F.
    </p>
  </div>
  <div class="col box3">
    <p>
      <span>Sunday</span>
      <br/>
      Thunderstorms with a high of 72°F.
    </p>
  </div>
</div>

</body>
</html>
