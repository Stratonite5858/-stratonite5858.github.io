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
}

/********** Large devices only **********/
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3 {
    float: left;
    border: 1px solid green;
    box-sizing: border-box;
    margin: 10px;
  }
  .col-lg-1 {
    width: 33.33%;
  }
  .col-lg-2 {
    width: 33.33%;
  }
  .col-lg-3 {
    width: 33.33%;
  }
}

/********** Medium devices only **********/
@media (min-width: 992px) and (max-width: 1199px) {
  .col-md-1, .col-md-2, .col-md-3 {
    float: left;
    border: 1px solid green;
    box-sizing: border-box;
    margin: 10px;
  }
  .col-md-1 {
    width: 33.33%;
  }
  .col-md-2 {
    width: 33.33%;
  }
  .col-md-3 {
    width: 33.33%;
  }
}

</style>
</head>
<body>
<h1>3-Day Forecast</h1>

<div class="row">
  <div class="col-lg-3 col-md-6"><p>Item 1</p></div>
  <div class="col-lg-3 col-md-6"><p>Item 2</p></div>
</div>
<div class="row">
  <div class="col-lg-3 col-md-6"><p>Item 3</p></div>
</div>

</body>
</html>
