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

p {
  border: 1px solid black;
  background-color: #A52A2A;
  width: 90%;
  height: 150px;
  margin-right: auto;
  margin-left: auto;
  font-family: Helvetica;
  color: white;
}

/* Simple Responsive Framework. */
.row {
  width: 100%;
  display: flex;
  justify-content: left;
  flex-wrap: wrap;
}

.col {
  float: left;
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
  <div class="col"><p>Friday</p></div>
  <div class="col"><p>Saturday</p></div>
  <div class="col"><p>Sunday</p></div>
</div>

</body>
</html>
